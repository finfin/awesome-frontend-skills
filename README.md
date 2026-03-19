# Awesome Frontend Agent Skills

A curated list of frontend-related Agent Skills repositories that include a `SKILL.md` file. Most can be installed via `npx skills add`.

> **Not included:** llms.txt, .cursorrules, AGENTS.md, CLAUDE.md and other formats.

[English](./README.md) | [繁體中文](./README-zh-TW.md)

## Table of Contents

- [Installation](#installation)
- [Frameworks](#frameworks)
- [UI Component Libraries](#ui-component-libraries)
- [Design](#design)
- [Animation](#animation)
- [Testing](#testing)
- [TypeScript](#typescript)
- [Build Tools](#build-tools)
- [Video](#video)
- [Auth](#auth)
- [ORM / Database](#orm--database)
- [Mobile / React Native](#mobile--react-native)
- [Skill Management Tools](#skill-management-tools)

---

## Installation

All skills can be installed via the [Vercel Skills CLI](https://github.com/vercel-labs/skills):

```
# Install a specific skill
npx skills add <owner/repo> --skill <skill-name>

# List all skills in a repository
npx skills add <owner/repo> --list

# Install to specific agents
npx skills add <owner/repo> --skill <name> -a claude-code -a cursor

# Install to all agents
npx skills add <owner/repo> --all
```

---

## Frameworks

### React

| Repository | Skill | Install |
|---|---|---|
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) 🔺 Official | `vercel-react-best-practices` — 62 rules across 8 categories (waterfall elimination, bundle optimization, server-side performance, re-render optimization, etc.) | `npx skills add vercel-labs/agent-skills --skill vercel-react-best-practices` |
| [millionco/react-doctor](https://github.com/millionco/react-doctor) | `react-doctor` — Scans your React codebase for security, performance, correctness, and architecture issues. Outputs a 0–100 score with actionable diagnostics (`npx react-doctor@latest . --verbose --diff`) | `npx skills add millionco/react-doctor --skill react-doctor` |
| [wshobson/agents](https://github.com/wshobson/agents) | `react-state-management` — Comprehensive guide to React state management: Zustand, Redux Toolkit, Jotai, React Query, URL State — decision criteria and patterns | `npx skills add wshobson/agents --skill react-state-management` |
| [softaworks/agent-toolkit](https://github.com/softaworks/agent-toolkit) | `react-dev` — React 19 TypeScript type-safety guide (component patterns, event handlers, hook types, generic components, Server Components, TanStack Router integration) | `npx skills add softaworks/agent-toolkit --skill react-dev` |

### Angular

| Repository | Skill | Install |
|---|---|---|
| [analogjs/angular-skills](https://github.com/analogjs/angular-skills) 🔺 Official | `angular-component` — Standalone components, Signal inputs/outputs, OnPush, host bindings | `npx skills add analogjs/angular-skills --skill angular-component` |
|  | `angular-signals` — Signal-based state, computed, effect, Signal Forms | `npx skills add analogjs/angular-skills --skill angular-signals` |
|  | `angular-forms` — Schema-based validation, field state management, reactive patterns | `npx skills add analogjs/angular-skills --skill angular-forms` |
|  | `angular-routing` — Route configuration, guards, resolvers | `npx skills add analogjs/angular-skills --skill angular-routing` |
|  | `angular-http` — HttpClient, interceptors, error handling | `npx skills add analogjs/angular-skills --skill angular-http` |
|  | `angular-di` — inject(), injection tokens, provider configuration, hierarchical DI | `npx skills add analogjs/angular-skills --skill angular-di` |

> 📌 Targets Angular v20+ with standalone and signal-based defaults.

### Vue

| Repository | Skill | Install |
|---|---|---|
| [hyf0/vue-skills](https://github.com/hyf0/vue-skills) | `vue-best-practices` — Vue development best practices | `npx skills add hyf0/vue-skills --skill vue-best-practices` |
| [antfu/skills](https://github.com/antfu/skills) | `vue` — Vue development skill (maintained by Anthony Fu) | `npx skills add antfu/skills --skill vue` |
| [hyf0/vue-skills](https://github.com/hyf0/vue-skills) | `vue-debug-guides` — Vue debugging guides | `npx skills add hyf0/vue-skills --skill vue-debug-guides` |
| [antfu/skills](https://github.com/antfu/skills) | `vueuse-functions` — VueUse composable function best practices | `npx skills add antfu/skills --skill vueuse-functions` |
| [vuejs-ai/skills](https://github.com/vuejs-ai/skills) | `vue-pinia-best-practices` — Pinia state management best practices | `npx skills add vuejs-ai/skills --skill vue-pinia-best-practices` |
| [vuejs-ai/skills](https://github.com/vuejs-ai/skills) | `create-adaptable-composable` — Reusable composable design patterns | `npx skills add vuejs-ai/skills --skill create-adaptable-composable` |

> 📌 Vue.js has no official SKILL.md yet, but high-quality community skills are available.

### Next.js

| Repository | Skill | Install |
|---|---|---|
| [vercel-labs/next-skills](https://github.com/vercel-labs/next-skills) 🔺 Official | `next-best-practices` — Next.js 15+ file conventions, RSC boundaries, async params, Runtime selection, hydration errors, Suspense, and more | `npx skills add vercel-labs/next-skills` |
| [wshobson/agents](https://github.com/wshobson/agents) | `nextjs-app-router-patterns` — Full App Router patterns: Server Components, Server Actions, Parallel Routes, Streaming, Route Handlers | `npx skills add wshobson/agents --skill nextjs-app-router-patterns` |

### Nuxt

| Repository | Skill | Install |
|---|---|---|
| [antfu/skills](https://github.com/antfu/skills) | `nuxt` — Nuxt development best practices (maintained by Anthony Fu) | `npx skills add antfu/skills --skill nuxt` |
| [nuxt/ui](https://github.com/nuxt/ui) 🔺 Official | `nuxt-ui` — Nuxt UI component development | `npx skills add nuxt/ui --skill nuxt-ui` |
| [onmax/nuxt-skills](https://github.com/onmax/nuxt-skills) | `nuxt` — Comprehensive Nuxt framework development skill | `npx skills add onmax/nuxt-skills --skill nuxt` |
| [onmax/nuxt-skills](https://github.com/onmax/nuxt-skills) | `reka-ui` — Reka UI component library (headless Vue components) | `npx skills add onmax/nuxt-skills --skill reka-ui` |
| [onmax/nuxt-skills](https://github.com/onmax/nuxt-skills) | `nuxt-ui` — Nuxt UI integration | `npx skills add onmax/nuxt-skills --skill nuxt-ui` |

### Svelte / SvelteKit

| Repository | Skill | Install |
|---|---|---|
| [sveltejs/ai-tools](https://github.com/sveltejs/ai-tools) 🔺 Official | `svelte-code-writer` — Svelte code generation (maintained by the official team) | `npx skills add sveltejs/ai-tools --skill svelte-code-writer` |

### TanStack

| Repository | Skill | Install |
|---|---|---|
| [deckardger/tanstack-agent-skills](https://github.com/deckardger/tanstack-agent-skills) | `tanstack-start-best-practices` — TanStack Start full-stack framework best practices | `npx skills add deckardger/tanstack-agent-skills --skill tanstack-start-best-practices` |
| [deckardger/tanstack-agent-skills](https://github.com/deckardger/tanstack-agent-skills) | `tanstack-query-best-practices` — TanStack Query best practices | `npx skills add deckardger/tanstack-agent-skills --skill tanstack-query-best-practices` |

### Remix / React Router

| Repository | Skill | Install |
|---|---|---|
| [remix-run/agent-skills](https://github.com/remix-run/agent-skills) 🔺 Official | `react-router-framework-mode` — Full-stack framework mode (loaders, actions, middleware) | `npx skills add remix-run/agent-skills --skill react-router-framework-mode` |

---

## UI Component Libraries

| Repository | Skill | Install |
|---|---|---|
| [shadcn/ui](https://ui.shadcn.com/docs/skills) 🔺 Official | `shadcn` — Project detection (isRSC, Tailwind version, iconLibrary), strict composition rules (FieldGroup, semantic colors, gap layout, icon `data-icon`), CLI workflow | `npx shadcn@latest add skills` |
| [wshobson/agents](https://github.com/wshobson/agents) | `tailwind-design-system` — Tailwind v4 CSS-first design system (`@theme` config, CVA components, Compound Components, dark mode, native CSS animations) | `npx skills add wshobson/agents --skill tailwind-design-system` |
| [giuseppe-trisciuoglio/developer-kit](https://github.com/giuseppe-trisciuoglio/developer-kit) | `shadcn-ui` — Complete shadcn/ui guide (Radix UI, Zod form validation, charts, controlled components) | `npx skills add giuseppe-trisciuoglio/developer-kit --skill shadcn-ui` |
| [jezweb/claude-skills](https://github.com/jezweb/claude-skills) | `tailwind-v4-shadcn` — Tailwind v4 + shadcn/ui integration | `npx skills add jezweb/claude-skills --skill tailwind-v4-shadcn` |
| [vercel/components.build](https://github.com/vercel/components.build) 🔺 Official | `building-components` — Vercel component building guide | `npx skills add vercel/components.build --skill building-components` |

---

## Design

| Repository | Skill | Install |
|---|---|---|
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | `ui-ux-pro-max` — 50+ styles, 161 color combos, 57 font pairings, 99 UX principles, 25 chart types; supports `--design-system`/`--domain`/`--stack` queries | `npx skills add nextlevelbuilder/ui-ux-pro-max-skill` |
| [supercent-io/skills-template](https://github.com/supercent-io/skills-template) | `frontend-design-system` — Frontend design system construction guide | `npx skills add supercent-io/skills-template --skill frontend-design-system` |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | `web-design-reviewer` — Web design review and feedback | `npx skills add github/awesome-copilot --skill web-design-reviewer` |
| [kimny1143/claude-code-template](https://github.com/kimny1143/claude-code-template) | `ui-ux-pro-max` — UI/UX design best practices | `npx skills add kimny1143/claude-code-template --skill ui-ux-pro-max` |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | `frontend-design` — Enhanced Anthropic frontend-design skill with curated anti-patterns across typography, color, layout, and motion; guides AI to create distinctive, production-grade UI | `npx skills add pbakaus/impeccable --skill frontend-design` |

---

## Animation

| Repository | Skill | Install |
|---|---|---|
| [cloudai-x/threejs-skills](https://github.com/cloudai-x/threejs-skills) | `threejs-animation` — Three.js animation system (AnimationClip, AnimationMixer, skeletal animation, Morph Targets, animation blending) | `npx skills add cloudai-x/threejs-skills --skill threejs-animation` |
| [mblode/agent-skills](https://github.com/mblode/agent-skills) | `ui-animation` — UI animation rules: use only `transform`/`opacity`, 200–300ms timing, prefers-reduced-motion, CSS-first principles | `npx skills add mblode/agent-skills --skill ui-animation` |
| [patricio0312rev/skills](https://github.com/patricio0312rev/skills) | `framer-motion-animator` — Full Framer Motion guide (variants, stagger, page transitions, scroll, gestures, a11y) | `npx skills add patricio0312rev/skills --skill framer-motion-animator` |

---

## Testing

| Repository | Skill | Install |
|---|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) 🔺 Official | `webapp-testing` — Test local web apps with Python Playwright (includes `with_server.py` helper, reconnaissance-then-action pattern) | `npx skills add anthropics/skills --skill webapp-testing` |
| [currents-dev/playwright-best-practices-skill](https://github.com/currents-dev/playwright-best-practices-skill) 🔺 Official | `playwright-best-practices` — Playwright E2E, component, API, visual regression, and a11y testing best practices | `npx skills add currents-dev/playwright-best-practices-skill` |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | `playwright-generate-test` — Generate Playwright test code | `npx skills add github/awesome-copilot --skill playwright-generate-test` |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | `playwright-explore-website` — Automated website exploration with Playwright | `npx skills add github/awesome-copilot --skill playwright-explore-website` |
| [microsoft/playwright-cli](https://github.com/microsoft/playwright-cli) 🔺 Official | `playwright-cli` — Microsoft official Playwright CLI skill | `npx skills add microsoft/playwright-cli --skill playwright-cli` |
| [wshobson/agents](https://github.com/wshobson/agents) | `e2e-testing-patterns` — E2E testing patterns and best practices | `npx skills add wshobson/agents --skill e2e-testing-patterns` |
| [LambdaTest/agent-skills](https://github.com/LambdaTest/agent-skills) 🔺 Official | Multi-framework testing skills: Selenium, Playwright, Cypress, WebdriverIO, Puppeteer | `cp -r agent-skills/playwright-skill .claude/skills/` |

---

## TypeScript

| Repository | Skill | Install |
|---|---|---|
| [bmad-labs/skills](https://github.com/bmad-labs/skills) | `typescript-clean-code` — TypeScript clean code patterns, architecture conventions, refactoring guidelines, and PR review principles | `npx skills add bmad-labs/skills --skill typescript-clean-code` |
| [bmad-labs/skills](https://github.com/bmad-labs/skills) | `typescript-unit-testing` — TS/NestJS unit testing with Jest, DeepMocked, mongodb-memory-server, pg-mem, Kafka, and Redis | `npx skills add bmad-labs/skills --skill typescript-unit-testing` |
| [bmad-labs/skills](https://github.com/bmad-labs/skills) | `typescript-e2e-testing` — TypeScript E2E testing strategy and TDD workflow | `npx skills add bmad-labs/skills --skill typescript-e2e-testing` |

---

## Build Tools

| Repository | Skill | Install |
|---|---|---|
| [antfu/skills](https://github.com/antfu/skills) | `vite` — Vite build tool best practices (maintained by Anthony Fu) | `npx skills add antfu/skills --skill vite` |
| [antfu/skills](https://github.com/antfu/skills) | `vitepress` — VitePress static site generator | `npx skills add antfu/skills --skill vitepress` |
| [wshobson/agents](https://github.com/wshobson/agents) | `monorepo-management` — Monorepo management best practices | `npx skills add wshobson/agents --skill monorepo-management` |
| [nrwl/nx-ai-agents-config](https://github.com/nrwl/nx-ai-agents-config) 🔺 Official | Nx workspace exploration, code generation, task execution, CI monitoring | `npx skills add nrwl/nx-ai-agents-config` |
| [vercel/turborepo](https://github.com/vercel/turborepo) 🔺 Official | Task pipelines, caching, remote cache, CI optimization | `npx skills add vercel/turborepo` |

---

## Video

| Repository | Skill | Install |
|---|---|---|
| [remotion-dev/skills](https://github.com/remotion-dev/skills) 🔺 Official | `remotion` — React-based video production (28 rules: animation, captions, 3D, audio, charts) | `npx skills add remotion-dev/skills` |
| [inferen-sh/skills](https://github.com/inferen-sh/skills) | `remotion-render` — Remotion video rendering best practices | `npx skills add inferen-sh/skills --skill remotion-render` |
| [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) | `remotion` — Stitch + Remotion video production | `npx skills add google-labs-code/stitch-skills --skill remotion` |
| [supercent-io/skills-template](https://github.com/supercent-io/skills-template) | `remotion-video-production` — Remotion video production template | `npx skills add supercent-io/skills-template --skill remotion-video-production` |

---

## Auth

| Repository | Skill | Install |
|---|---|---|
| [better-auth/skills](https://github.com/better-auth/skills) 🔺 Official | `better-auth-best-practices` — Better Auth best practices | `npx skills add better-auth/skills --skill better-auth-best-practices` |
| [clerk/skills](https://github.com/clerk/skills) 🔺 Official | `clerk-nextjs-patterns` — Clerk + Next.js authentication integration patterns | `npx skills add clerk/skills --skill clerk-nextjs-patterns` |
|  | `clerk` — Core Clerk authentication | `npx skills add clerk/skills --skill clerk` |
|  | `clerk-setup` — Clerk initial setup | `npx skills add clerk/skills --skill clerk-setup` |
| [auth0/agent-skills](https://github.com/auth0/agent-skills) 🔺 Official | `auth0-react`, `auth0-nextjs`, `auth0-angular`, `auth0-vue`, `auth0-react-native`, `auth0-mfa` | `npx skills add auth0/agent-skills --skill auth0-react` |

---

## ORM / Database

| Repository | Skill | Install |
|---|---|---|
| [prisma/skills](https://github.com/prisma/skills) 🔺 Official | `prisma-cli`, `prisma-client-api`, `prisma-upgrade-v7`, `prisma-database-setup`, `prisma-postgres` | `npx skills add prisma/skills` |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) 🔺 Official | Postgres best practices, Edge Functions, RLS | `npx skills add supabase/agent-skills` |
| [convex-dev/agent-skills](https://github.com/convex-dev/agent-skills) 🔺 Official | Convex real-time database best practices | `npx skills add convex-dev/agent-skills` |

---

## Mobile / React Native

| Repository | Skill | Install |
|---|---|---|
| [callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills) 🔺 Official | `react-native-best-practices` — 16 rules, 7 chapters (performance, architecture, platform-specific) | `npx skills add callstackincubator/agent-skills --skill react-native-best-practices` |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) 🔺 Official | `react-native-best-practices` — Vercel's React Native best practices | `npx skills add vercel-labs/agent-skills --skill react-native-best-practices` |
| [expo/skills](https://github.com/expo/skills) 🔺 Official | Expo development best practices | `npx skills add expo/skills` |

---

## Skill Management Tools

| Tool | Description | Link |
|---|---|---|
| **skills** (Vercel) | Official CLI — `npx skills add/remove/list`, supports 38+ agents | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| **skills.sh** | Skill directory and leaderboard | [skills.sh](https://skills.sh) |
| **@tanstack/intent** | npm-native skill publishing — skills ship alongside package versions | [tanstack.com/intent](https://tanstack.com/intent) |
| **antfu/skills-npm** | Auto-discovers SKILL.md from node_modules and creates symlinks | [antfu/skills-npm](https://github.com/antfu/skills-npm) |
| **skillkit** | Universal skill manager across 44+ agents | [rohitg00/skillkit](https://github.com/rohitg00/skillkit) |
