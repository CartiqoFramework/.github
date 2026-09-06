# .github

The organisation profile for [@CartiqoFramework](https://github.com/CartiqoFramework), plus the community health files that every other CARTIQO repository inherits.

Nothing here ships in a product. If you were looking for our work, that is at [cartiqo.xyz](https://cartiqo.xyz).

## What is in here

| Path | What it does | Where it shows up |
| :-- | :-- | :-- |
| `profile/README.md` | The organisation profile | The front page at [github.com/CartiqoFramework](https://github.com/CartiqoFramework) |
| `profile/assets/` | Brand banner, light and dark | Top of the profile |
| `CODE_OF_CONDUCT.md` | How we expect people to behave | Every repository without its own |
| `CONTRIBUTING.md` | House rules: commits, pull requests, interface conventions | Shown when someone opens an issue or a pull request |
| `SECURITY.md` | How to report a vulnerability | The Security tab |
| `SUPPORT.md` | Where to ask for help | The "Support" link on issues |
| `.github/ISSUE_TEMPLATE/` | Bug, feature and impersonation forms | The "New issue" chooser |
| `.github/PULL_REQUEST_TEMPLATE.md` | Pull request checklist | Prefilled on every new pull request |

## How the inheritance works

GitHub falls back to this repository for any of those files a repository does not have itself. A repository's own copy always wins, so a project with unusual contribution rules just adds its own `CONTRIBUTING.md` and this one stops applying to it.

Two things worth remembering:

- These defaults only reach **public** repositories. Private repositories need their own copies.
- Deleting a file here removes it from every repository that was relying on it.

## Editing the profile

`profile/README.md` is rendered on the organisation page, not inside a repository, so **relative links do not resolve there.** Every link and image has to be an absolute URL, including the banner. That is why the `<picture>` block points at `raw.githubusercontent.com` rather than at `assets/`.

The banners are hand written SVG using the official wordmark geometry, so they need no fonts and no raster export. Colours come from the brand tokens: ink `#111113`, snow `#FFFAFA`, graphite `#0E1013`, and the single violet accent `#7C5CFF` on the trailing period. Change the wordmark in the design system first, then mirror it here, never the other way round.

Check any change to the profile against both GitHub themes before pushing. The dark banner is served through `prefers-color-scheme`, and a light-only asset on a dark profile looks like a mistake because it is one.

## Licence

MIT. See [LICENSE](LICENSE).
