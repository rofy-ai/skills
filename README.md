# Rofy skills

Instructions that teach an AI assistant to make images and videos with
[Rofy](https://github.com/rofy-ai/rofy-cli). A skill is a manual the assistant
reads: when to use Rofy, which model fits which job, how to write a prompt,
what to ask before spending credits, and how to reply.

## Install

Paste this to your assistant, such as Claude Code:

```
Set up Rofy for me so I can generate images and videos from here.

1. Install the CLI: run `npm i -g @rofy/cli`.
2. Authenticate: run `rofy auth login` and complete the sign-in in the browser it opens.
3. Install the companion skills: run `npx skills add rofy-ai/skills`.

Once that's done, let me know when it's ready.
```

Or run the three commands yourself.

## Skills

| Skill | What it does |
|---|---|
| `rofy-generate` | Images and videos with any Rofy model: choosing the model, its settings and media, the cost, waiting, and delivering the result |

## Two rules every skill keeps

- **The user chooses the workspace.** Each workspace has its own credits. The
  assistant asks which one to use and never picks one itself.
- **The user approves a video's cost.** The assistant states the cost before
  it starts a video.
