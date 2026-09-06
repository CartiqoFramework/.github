# Contributing to CARTIQO

Thanks for taking the time. These are the defaults for every CARTIQO repository. If a repository carries its own `CONTRIBUTING.md`, that one wins.

## Before you write code

- **Open an issue first** for anything larger than a typo or an obvious bug fix. It saves you building something we were about to change.
- **One issue, one problem.** Two unrelated things in one thread means one of them gets forgotten.
- Ask in [our Discord](https://discord.gg/YTKp4MnN9Q) if you are not sure whether an idea fits. That is a faster no than a pull request is.

## Getting set up

Most of our repositories are TypeScript on pnpm, and a few are Lua for FiveM.

```bash
pnpm install
pnpm dev
```

Copy `.env.example` to `.env` where one exists. Never commit a real `.env`, a token, or a database URL. If you push a secret by accident, tell us immediately at hello@cartiqo.xyz and rotate it, do not quietly force push and hope.

## Commits

Conventional Commits, with a terse subject.

```
type(scope): subject
```

- Subject under 72 characters, present tense, no trailing period.
- Scope is the module or package: `giveaways`, `transcript`, `invites`.
- **One commit per module.** Do not batch two modules into one commit.
- A body only when there is a non-obvious *why*, one to three lines. Reasoning that explains the code belongs in a code comment, not in the log.

```
feat(giveaways): entry button, /gstart, /gend, /greroll

Tickets are stored at entry, not recomputed at draw time, so a role
removed later cannot change odds someone already had.
```

The subject has to stand on its own in GitHub's file list, because that is where the work gets reviewed. `fix: stuff` and `phase 4` tell a reviewer nothing.

Types we use: `feat`, `fix`, `refactor`, `perf`, `docs`, `style`, `test`, `build`, `chore`.

## Pull requests

- Branch from `main`, named `type/short-description`.
- Keep it to one concern. A large pull request that does four things gets reviewed slowly or not at all.
- Fill in the template. "What changed" and "how you tested it" are the parts we actually read.
- Run `pnpm lint` and `pnpm build` before you open it.
- Screenshots or a short clip for anything visual, in both light and dark.

## House rules for the interface

These are not preferences, they are what keeps our products looking like one product.

- **Edit tokens, never components.** Rebranding happens in the token file. A one off colour in a component is a bug.
- **One accent, and it means active state.** Selected, pressed, focused, primary action. Never decoration.
- **No emoji in anything a user sees.** Use the design system's icons, a text label, or nothing. If a decorative mark seems necessary, that is a sign the component is missing an icon.
- **Check contrast before you ship.** Every text and background pair against WCAG AA. Measure it, do not assume a hue swap kept it.
- Type is Geist and Geist Mono. Mono is for numerics and always tabular.

## Code

- TypeScript, no `any` that you cannot justify in a comment.
- Comment the *why*, not the *what*. This codebase already leans on comments heavily, keep that up.
- Match the file you are editing: its naming, its structure, its comment density.
- No new dependency for something the standard library or an existing dependency already does.

## Reporting security problems

Do not open an issue. Read [SECURITY.md](SECURITY.md).

## Licence

By contributing you agree that your contribution is licensed under the repository's licence, MIT unless stated otherwise.
