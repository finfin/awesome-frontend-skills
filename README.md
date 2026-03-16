# Awesome Frontend Agent Skills

> 收錄**含有 `SKILL.md` 檔案**的前端相關 Agent Skills 儲存庫。大部分可透過 `npx skills add` 安裝。
>
> 不收錄： llms.txt、.cursorrules、AGENTS.md、CLAUDE.md 等其他格式。

## 目錄

- [安裝工具](#安裝工具)
- [框架 Frameworks](#框架-frameworks)
- [UI 元件庫 Component Libraries](#ui-元件庫-component-libraries)
- [設計 Design](#設計-design)
- [動畫 Animation](#動畫-animation)
- [測試 Testing](#測試-testing)
- [建置工具 Build Tools](#建置工具-build-tools)
- [影片製作 Video](#影片製作-video)
- [認證 Auth](#認證-auth)
- [ORM / 資料庫](#orm--資料庫)
- [Mobile / React Native](#mobile--react-native)
- [技能管理工具](#技能管理工具)

---

## 安裝工具

所有技能皆可透過 [Vercel Skills CLI](https://github.com/vercel-labs/skills) 安裝：

```
# 安裝特定技能
npx skills add <owner/repo> --skill <skill-name>

# 列出儲存庫中所有技能
npx skills add <owner/repo> --list

# 安裝至特定代理
npx skills add <owner/repo> --skill <name> -a claude-code -a cursor

# 安裝至所有代理
npx skills add <owner/repo> --all

```

---

## 框架 Frameworks

### React

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) 🔺 官方 | `vercel-react-best-practices` — 62 條規則、8 大類（消除 waterfall、bundle 最佳化、Server Side 效能、re-render 最佳化等） | `npx skills add vercel-labs/agent-skills --skill vercel-react-best-practices` |
| [millionco/react-doctor](https://github.com/millionco/react-doctor) | `react-doctor` — 掃描 React codebase 的安全性、效能、正確性與架構問題，輸出 0-100 分診斷報告（`npx react-doctor@latest . --verbose --diff`） | `npx skills add millionco/react-doctor --skill react-doctor` |
| [wshobson/agents](https://github.com/wshobson/agents) | `react-state-management` — React 狀態管理完整指南：Zustand、Redux Toolkit、Jotai、React Query、URL State 選型決策與模式 | `npx skills add wshobson/agents --skill react-state-management` |
| [softaworks/agent-toolkit](https://github.com/softaworks/agent-toolkit) | `react-dev` — React 19 TypeScript 型別安全指南（元件模式、事件處理、hooks 型別、泛型元件、Server Components、TanStack Router 整合） | `npx skills add softaworks/agent-toolkit --skill react-dev` |

## Angular

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [analogjs/angular-skills](https://github.com/analogjs/angular-skills) 🔺 官方 | `angular-component` — Standalone 元件、Signal inputs/outputs、OnPush、host bindings | `npx skills add analogjs/angular-skills --skill angular-component` |
|  | `angular-signals` — Signal 狀態管理、computed、effect、Signal Forms | `npx skills add analogjs/angular-skills --skill angular-signals` |
|  | `angular-forms` — Schema-based 驗證、欄位狀態管理、反應式模式 | `npx skills add analogjs/angular-skills --skill angular-forms` |
|  | `angular-routing` — 路由設定、guards、resolvers | `npx skills add analogjs/angular-skills --skill angular-routing` |
|  | `angular-http` — HttpClient、interceptors、錯誤處理 | `npx skills add analogjs/angular-skills --skill angular-http` |
|  | `angular-di` — inject()、injection tokens、provider 設定、階層式 DI | `npx skills add analogjs/angular-skills --skill angular-di` |

> 📌 官方 skill 主要針對 Angular v20+。

### Vue 🆕

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [hyf0/vue-skills](https://github.com/hyf0/vue-skills) | `vue-best-practices` — Vue 開發最佳實踐 | `npx skills add hyf0/vue-skills --skill vue-best-practices` |
| [antfu/skills](https://github.com/antfu/skills) | `vue` — Vue 開發技能（Anthony Fu 維護） | `npx skills add antfu/skills --skill vue` |
| [hyf0/vue-skills](https://github.com/hyf0/vue-skills) | `vue-debug-guides` — Vue 除錯指南 | `npx skills add hyf0/vue-skills --skill vue-debug-guides` |
| [antfu/skills](https://github.com/antfu/skills) | `vueuse-functions` — VueUse 組合式函數最佳實踐 | `npx skills add antfu/skills --skill vueuse-functions` |
| [vuejs-ai/skills](https://github.com/vuejs-ai/skills) | `vue-pinia-best-practices` — Pinia 狀態管理最佳實踐 | `npx skills add vuejs-ai/skills --skill vue-pinia-best-practices` |
| [vuejs-ai/skills](https://github.com/vuejs-ai/skills) | `create-adaptable-composable` — 可複用 composable 設計模式 | `npx skills add vuejs-ai/skills --skill create-adaptable-composable` |

> 📌 Vue.js 官方仍未提供 SKILL.md，但社群已有高品質技能可用。

### Next.js

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [vercel-labs/next-skills](https://github.com/vercel-labs/next-skills) 🔺 官方 | `next-best-practices` — Next.js 15+ 檔案慣例、RSC 邊界、async params、Runtime 選擇、水合錯誤、Suspense 等 | `npx skills add vercel-labs/next-skills` |
| [wshobson/agents](https://github.com/wshobson/agents) | `nextjs-app-router-patterns` — App Router 完整模式：Server Components、Server Actions、Parallel Routes、Streaming、Route Handlers | `npx skills add wshobson/agents --skill nextjs-app-router-patterns` |

### Nuxt 🆕

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [antfu/skills](https://github.com/antfu/skills) | `nuxt` — Nuxt 開發最佳實踐（Anthony Fu 維護） | `npx skills add antfu/skills --skill nuxt` |
| [nuxt/ui](https://github.com/nuxt/ui) 🔺 官方 | `nuxt-ui` — Nuxt UI 元件開發 | `npx skills add nuxt/ui --skill nuxt-ui` |
| [onmax/nuxt-skills](https://github.com/onmax/nuxt-skills) | `nuxt` — Nuxt 框架完整開發技能 | `npx skills add onmax/nuxt-skills --skill nuxt` |
| [onmax/nuxt-skills](https://github.com/onmax/nuxt-skills) | `reka-ui` — Reka UI 元件庫（Vue 無頭元件） | `npx skills add onmax/nuxt-skills --skill reka-ui` |
| [onmax/nuxt-skills](https://github.com/onmax/nuxt-skills) | `nuxt-ui` — Nuxt UI 整合 | `npx skills add onmax/nuxt-skills --skill nuxt-ui` |

### Svelte / SvelteKit

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [sveltejs/ai-tools](https://github.com/sveltejs/ai-tools) 🔺 官方 | `svelte-code-writer` — Svelte 程式碼生成（官方團隊維護） | `npx skills add sveltejs/ai-tools --skill svelte-code-writer` |

### TanStack

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [deckardger/tanstack-agent-skills](https://github.com/deckardger/tanstack-agent-skills) | `tanstack-start-best-practices` — TanStack Start 全端框架最佳實踐 | `npx skills add deckardger/tanstack-agent-skills --skill tanstack-start-best-practices` |
| [deckardger/tanstack-agent-skills](https://github.com/deckardger/tanstack-agent-skills) | `tanstack-query-best-practices` — TanStack Query 最佳實踐 | `npx skills add deckardger/tanstack-agent-skills --skill tanstack-query-best-practices` |

### Remix / React Router

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [remix-run/agent-skills](https://github.com/remix-run/agent-skills) 🔺 官方 | `react-router-framework-mode` — 全端框架模式（loaders、actions、middleware） | `npx skills add remix-run/agent-skills --skill react-router-framework-mode` |

---

## UI 元件庫 Component Libraries

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [shadcn/ui](https://ui.shadcn.com/docs/skills) 🔺 官方 | `shadcn` — 偵測專案設定（isRSC、Tailwind 版本、iconLibrary）、嚴格組合規則（FieldGroup、語義色彩、gap 排版、icon `data-icon`）、CLI 工作流程 | `npx shadcn@latest add skills` |
| [wshobson/agents](https://github.com/wshobson/agents) | `tailwind-design-system` — Tailwind v4 CSS-first 設計系統（`@theme` 配置、CVA 元件、Compound Components、暗黑模式、原生 CSS 動畫） | `npx skills add wshobson/agents --skill tailwind-design-system` |
| [giuseppe-trisciuoglio/developer-kit](https://github.com/giuseppe-trisciuoglio/developer-kit) | `shadcn-ui` — shadcn/ui 完整使用指南（Radix UI、Zod 表單驗證、圖表、受控元件） | `npx skills add giuseppe-trisciuoglio/developer-kit --skill shadcn-ui` |
| [jezweb/claude-skills](https://github.com/jezweb/claude-skills) | `tailwind-v4-shadcn` — Tailwind v4 + shadcn/ui 整合 | `npx skills add jezweb/claude-skills --skill tailwind-v4-shadcn` |
| [vercel/components.build](https://github.com/vercel/components.build) 🔺 官方 | `building-components` — Vercel 元件建構指南 | `npx skills add vercel/components.build --skill building-components` |

---

## 設計 Design

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | `ui-ux-pro-max` — 含 50+ 風格、161 色彩組合、57 字型配對、99 UX 準則、25 圖表類型，支援 `--design-system`/`--domain`/`--stack` 查詢 | `npx skills add nextlevelbuilder/ui-ux-pro-max-skill` |
| [supercent-io/skills-template](https://github.com/supercent-io/skills-template) | `frontend-design-system` — 前端設計系統建構指引 | `npx skills add supercent-io/skills-template --skill frontend-design-system` |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | `web-design-reviewer` — 網頁設計審查與回饋 | `npx skills add github/awesome-copilot --skill web-design-reviewer` |
| [kimny1143/claude-code-template](https://github.com/kimny1143/claude-code-template) | `ui-ux-pro-max` — UI/UX 設計最佳實踐 | `npx skills add kimny1143/claude-code-template --skill ui-ux-pro-max` |

---

## 動畫 Animation

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [cloudai-x/threejs-skills](https://github.com/cloudai-x/threejs-skills) | `threejs-animation` — Three.js 動畫系統（AnimationClip、AnimationMixer、骨骼動畫、Morph Target、動畫混合） | `npx skills add cloudai-x/threejs-skills --skill threejs-animation` |
| [mblode/agent-skills](https://github.com/mblode/agent-skills) | `ui-animation` — UI 動畫規範：僅使用 `transform`/`opacity`、200-300ms 時機、prefers-reduced-motion、CSS-first 原則 | `npx skills add mblode/agent-skills --skill ui-animation` |
| [patricio0312rev/skills](https://github.com/patricio0312rev/skills) | `framer-motion-animator` — Framer Motion 完整動畫開發（variants、stagger、page transitions、scroll、gesture、a11y） | `npx skills add patricio0312rev/skills --skill framer-motion-animator` |

---

## 測試 Testing

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) 🔺 官方 | `webapp-testing` — 以 Python Playwright 測試本地 Web App（含 `with_server.py` helper、reconnaissance-then-action 模式） | `npx skills add anthropics/skills --skill webapp-testing` |
| [currents-dev/playwright-best-practices-skill](https://github.com/currents-dev/playwright-best-practices-skill) 🔺 官方 | `playwright-best-practices` — Playwright E2E、component、API、visual regression、a11y 測試最佳實踐 | `npx skills add currents-dev/playwright-best-practices-skill` |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | `playwright-generate-test` — Playwright 測試程式碼生成 | `npx skills add github/awesome-copilot --skill playwright-generate-test` |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | `playwright-explore-website` — Playwright 網站探索自動化 | `npx skills add github/awesome-copilot --skill playwright-explore-website` |
| [microsoft/playwright-cli](https://github.com/microsoft/playwright-cli) 🔺 官方 | `playwright-cli` — Microsoft 官方 Playwright CLI 技能 | `npx skills add microsoft/playwright-cli --skill playwright-cli` |
| [wshobson/agents](https://github.com/wshobson/agents) | `e2e-testing-patterns` — E2E 測試模式與最佳實踐 | `npx skills add wshobson/agents --skill e2e-testing-patterns` |
| [LambdaTest/agent-skills](https://github.com/LambdaTest/agent-skills) 🔺 官方 | Selenium、Playwright、Cypress、WebdriverIO、Puppeteer 等多框架測試技能 | `cp -r agent-skills/playwright-skill .claude/skills/` |

---

## 建置工具 Build Tools

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [antfu/skills](https://github.com/antfu/skills) | `vite` — Vite 建置工具最佳實踐（Anthony Fu 維護） | `npx skills add antfu/skills --skill vite` |
| [antfu/skills](https://github.com/antfu/skills) | `vitepress` — VitePress 靜態網站產生器 | `npx skills add antfu/skills --skill vitepress` |
| [wshobson/agents](https://github.com/wshobson/agents) | `monorepo-management` — Monorepo 管理最佳實踐 | `npx skills add wshobson/agents --skill monorepo-management` |
| [nrwl/nx-ai-agents-config](https://github.com/nrwl/nx-ai-agents-config) 🔺 官方 | Nx workspace 探索、程式碼產生、任務執行、CI 監控 | `npx skills add nrwl/nx-ai-agents-config` |
| [vercel/turborepo](https://github.com/vercel/turborepo) 🔺 官方 | Task pipelines、快取、remote cache、CI 最佳化 | `npx skills add vercel/turborepo` |

---

## 影片製作 Video

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [remotion-dev/skills](https://github.com/remotion-dev/skills) 🔺 官方 | `remotion` — React 影片製作（28 條規則：動畫、字幕、3D、音訊、圖表） | `npx skills add remotion-dev/skills` |
| [inferen-sh/skills](https://github.com/inferen-sh/skills) | `remotion-render` — Remotion 影片渲染最佳實踐（36.8K 安裝） | `npx skills add inferen-sh/skills --skill remotion-render` |
| [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) | `remotion` — Stitch + Remotion 影片製作 | `npx skills add google-labs-code/stitch-skills --skill remotion` |
| [supercent-io/skills-template](https://github.com/supercent-io/skills-template) | `remotion-video-production` — Remotion 影片製作範本 | `npx skills add supercent-io/skills-template --skill remotion-video-production` |

---

## 認證 Auth

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [better-auth/skills](https://github.com/better-auth/skills) 🔺 官方 | `better-auth-best-practices` — Better Auth 認證最佳實踐（23K 安裝） | `npx skills add better-auth/skills --skill better-auth-best-practices` |
| [clerk/skills](https://github.com/clerk/skills) 🔺 官方 | `clerk-nextjs-patterns` — Clerk + Next.js 認證整合模式（3.7K 安裝） | `npx skills add clerk/skills --skill clerk-nextjs-patterns` |
|  | `clerk` — Clerk 核心認證功能 | `npx skills add clerk/skills --skill clerk` |
|  | `clerk-setup` — Clerk 初始設定 | `npx skills add clerk/skills --skill clerk-setup` |
| [auth0/agent-skills](https://github.com/auth0/agent-skills) 🔺 官方 | `auth0-react`、`auth0-nextjs`、`auth0-angular`、`auth0-vue`、`auth0-react-native`、`auth0-mfa` | `npx skills add auth0/agent-skills --skill auth0-react` |

---

## ORM / 資料庫

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [prisma/skills](https://github.com/prisma/skills) 🔺 官方 | `prisma-cli`、`prisma-client-api`、`prisma-upgrade-v7`、`prisma-database-setup`、`prisma-postgres` | `npx skills add prisma/skills` |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) 🔺 官方 | Postgres 最佳實踐、Edge Functions、RLS（34.7K 安裝） | `npx skills add supabase/agent-skills` |
| [convex-dev/agent-skills](https://github.com/convex-dev/agent-skills) 🔺 官方 | Convex 即時資料庫最佳實踐 | `npx skills add convex-dev/agent-skills` |

---

## Mobile / React Native

| 儲存庫 | 技能 | 安裝指令 |
|---|---|---|
| [callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills) 🔺 官方 | `react-native-best-practices` — 16 規則、7 章節（效能、架構、平台特定） | `npx skills add callstackincubator/agent-skills --skill react-native-best-practices` |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) 🔺 官方 | `react-native-best-practices` — Vercel 版 RN 最佳實踐 | `npx skills add vercel-labs/agent-skills --skill react-native-best-practices` |
| [expo/skills](https://github.com/expo/skills) 🔺 官方 | Expo 開發最佳實踐 | `npx skills add expo/skills` |

---

## 技能管理工具

| 工具 | 說明 | 連結 |
|---|---|---|
| **skills** (Vercel) | 官方 CLI，`npx skills add/remove/list`，支援 38+ 代理 | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| **[skills.sh](skills.sh)** | 技能目錄與排行榜 | [skills.sh](skills.sh) |
| **@tanstack/intent** | npm 內建技能發佈系統——技能隨套件版本同步更新 | [tanstack.com/intent](tanstack.com/intent) |
| **antfu/skills-npm** | 從 node_modules 自動發現 [SKILL.md](SKILL.md) 並建立符號連結 | [antfu/skills-npm](https://github.com/antfu/skills-npm) |
| **skillkit** | 跨 44+ 代理的通用技能管理器 | [rohitg00/skillkit](https://github.com/rohitg00/skillkit) |
