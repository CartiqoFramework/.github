<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CartiqoFramework/.github/main/profile/assets/banner-dark.svg">
  <img alt="CARTIQO. Independent product studio. Software worth trusting." src="https://raw.githubusercontent.com/CartiqoFramework/.github/main/profile/assets/banner-light.svg">
</picture>

<br>

[![Website](https://img.shields.io/badge/Website-cartiqo.xyz-7C5CFF?style=flat-square&labelColor=111113)](https://cartiqo.xyz) [![Discord](https://img.shields.io/badge/Discord-Join%20the%20server-2A2D34?style=flat-square&labelColor=111113&logo=discord&logoColor=white)](https://discord.gg/YTKp4MnN9Q) [![Commission](https://img.shields.io/badge/Work%20with%20us-Start%20a%20brief-2A2D34?style=flat-square&labelColor=111113)](https://cartiqo.xyz/commission) [![Location](https://img.shields.io/badge/Based%20in-Denmark-2A2D34?style=flat-square&labelColor=111113)](https://cartiqo.xyz)

</div>

## We run what we build

CARTIQO is a small independent studio in Denmark, self funded and small on purpose. We do two things:

- **We build and run our own software.** Starting with Cartiqo, an all in one Discord bot.
- **We build websites for other people.** You see the real site working, in full, before you pay for it.

Whoever designs a thing builds it, so nothing gets lost in a handover. Launch day is the start of the work, not the end of it.

| The numbers | |
| --: | :-- |
| **33** | modules in Cartiqo, every one running, none coming soon |
| **$0** | what a client pays before seeing their finished site |
| **2026** | independent since |

## What we are building

| Project | What it is | Status |
| :-- | :-- | :-- |
| **Cartiqo** | One app for everything a Discord server runs on: moderation, engagement, utilities, security, analytics and automation, with the config surface of a real product rather than a dashboard bolted onto a script. | Building |
| **CARTIQO Lists** | A directory for Discord bots and communities. Listings, voting and a public API. | Early |
| **CARTIQO Tools** | Free browser tools for people who run communities, including a cover and icon studio that exports PNG and SVG. | Building |
| **[Walu_Cutzz](https://walucutzz.com)** | A booking site for a barbershop in Kolding. Clients pick the cut and a time, no phone call, no DM. | Live |

More detail on all of it at [cartiqo.xyz/projects](https://cartiqo.xyz/projects).

## Open source

The repositories we keep public. Most of our product code is private while it is being built, and moves out here when it is worth someone else's time.

| Repository | What it does |
| :-- | :-- |
| [**discord-transcript**](https://github.com/CartiqoFramework/discord-transcript) | Self contained HTML transcripts of Discord channels, rendered with Discord's own message components. TypeScript. |
| [**CTQCore**](https://github.com/CartiqoFramework/CTQCore) | FiveM core resource: connect queue and configuration, built on CTQBridge. Lua. |
| [**CTQBridge**](https://github.com/CartiqoFramework/CTQBridge) | Connects a FiveM server to the CARTIQO dashboard. QBCore, Qbox, ESX and standalone. Lua. |
| [**CTQui**](https://github.com/CartiqoFramework/CTQui) | A modern NUI kit for FiveM: notifications, text UI, progress bars. JavaScript. |

The three FiveM resources are early and untested. They are published so the work is readable, not because they are ready for a production server. We say so on each one rather than letting you find out.

Everything else we have opened up is in [the repository list](https://github.com/orgs/CartiqoFramework/repositories).

## How we work

| Step | |
| :-- | :-- |
| **01 Define** | Get clear on the problem and who it is for before anything gets drawn. Small scope, high standard. |
| **02 Design** | Draw the real screens, not a rough sketch. What you approve is what gets built. |
| **03 Build** | Built properly and checked over, in pieces that fit together, so it can change later without breaking. |
| **04 Ship and run** | Release it, watch how it behaves, keep improving it. |

For commissioned work the deal is simple: you brief us, we accept or decline, and if we take it on you see a real preview of your site before any money moves. Like it and you pay and it is yours. Do not, and you owe nothing. The quote is fixed before the preview, so there is no moving number. Start at [cartiqo.xyz/commission](https://cartiqo.xyz/commission).

## How we build it

Everything ships on one stack so the studio only has to be excellent at a small number of things.

| Layer | What we use |
| :-- | :-- |
| Language | TypeScript everywhere, Lua for FiveM |
| Web | Next.js 15, React 19, Tailwind CSS |
| Design system | One shared component library and token file per project, vendored rather than linked |
| Data | Prisma, MySQL |
| Discord | discord.js, Sapphire |
| Tooling | pnpm, Turborepo, ESLint, Prettier, GitHub Actions |

House rules live in [CONTRIBUTING.md](https://github.com/CartiqoFramework/.github/blob/main/CONTRIBUTING.md): conventional commits with a subject that stands alone in a file list, one commit per module, tokens edited instead of components.

## Official channels

Anything claiming to be CARTIQO that is not on this list is not us.

| Where | Handle |
| :-- | :-- |
| Web | [cartiqo.xyz](https://cartiqo.xyz), cartiqo.app |
| GitHub | [@CartiqoFramework](https://github.com/CartiqoFramework) |
| Discord | [CɅRTIQO. Support](https://discord.gg/YTKp4MnN9Q) |
| Instagram | [@cartiqo.xyz](https://www.instagram.com/cartiqo.xyz/) |
| Facebook | [CARTIQO](https://www.facebook.com/profile.php?id=61591562471864) |

We never ask for passwords, tokens or payment in a DM. If someone using our name does, report it to [hello@cartiqo.xyz](mailto:hello@cartiqo.xyz) or open an [impersonation report](https://github.com/CartiqoFramework/.github/issues/new?template=impersonation-report.yml).

## Contact

Work, questions, security reports and everything else: [hello@cartiqo.xyz](mailto:hello@cartiqo.xyz).

Security issues have their own route, please read [SECURITY.md](https://github.com/CartiqoFramework/.github/blob/main/SECURITY.md) first.

<div align="center">

<sub>Released under the MIT License unless a repository says otherwise. Copyright CARTIQO.</sub>

</div>
