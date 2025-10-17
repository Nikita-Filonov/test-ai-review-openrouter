# 🤖 AI Review with OpenRouter — Demo Project

This repository demonstrates how to integrate [AI Review](https://github.com/Nikita-Filonov/ai-review) — an open-source
automated code review tool — with [OpenRouter](https://openrouter.ai/), a universal gateway to dozens of modern LLMs.

It shows how to run AI-powered code
reviews [directly inside your CI/CD pipeline](https://github.com/Nikita-Filonov/test-ai-review-openrouter/actions) (e.g.
GitHub Actions):

- ✅ without paid API keys,
- ✅ without vendor lock-in (works with GPT-4o, Claude, Gemini, Mistral, etc.),
- ✅ and fully automatically, right inside Pull Requests.

The demo includes:

- 🔧 Minimal AI Review configuration ([.ai-review.yaml](.ai-review.yaml))
- ⚙️ [GitHub Actions workflow](.github/workflows/ai-review.yml) running AI Review with OpenRouter
- 🧠 Example review
  results — [inline comments](https://github.com/Nikita-Filonov/test-ai-review-openrouter/pull/1#discussion_r2440846830),
  [summary review](https://github.com/Nikita-Filonov/test-ai-review-openrouter/pull/1#issuecomment-3416651995), and even
  [test generation](https://github.com/Nikita-Filonov/test-ai-review-openrouter/pull/1#issuecomment-3416669140)
- 💡 The same setup works with **GitLab**, **Bitbucket**, **Gitea**, or **Jenkins** — just reuse the config and
  environment variables.

With OpenRouter, you can switch between dozens of LLMs (e.g. `gpt-4o`, `claude-3.5`, `mistral-7b`, `gemini-1.5`) by
simply changing one line in `.ai-review.yaml` — no code changes required.

## 📚 Learn more

- 📖 [AI Review documentation](https://github.com/Nikita-Filonov/ai-review/tree/main/docs) — advanced configuration,
  custom prompts, and multi-CI integration
- 🧪 [Example workflow runs](https://github.com/Nikita-Filonov/test-ai-review-openrouter/actions)
- 🛠️ [AI Review GitHub repository](https://github.com/Nikita-Filonov/ai-review)