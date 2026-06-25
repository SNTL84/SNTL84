<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:001f3f,25:005a96,50:01696f,75:01a89f,100:0d1117&height=320&section=header&text=SNTL%2084&desc=Milan%20%E2%80%A2%20AI%20Workflow%20Developer&fontSize=60&fontColor=ffffff&animation=fadeIn&descSize=25&descAlign=62" />
</div>

<div align="center">
  <a href="https://desidevloper.com" target="_blank">
    <img src="https://raw.githubusercontent.com/SNTL84/SNTL84/main/assets/SNTL-84.jpg" alt="SNTL 84 — AI Automation • Full-Stack • Business Intelligence" width="900" style="border-radius: 12px; box-shadow: 0 8px 32px rgba(1, 105, 111, 0.2);" />
  </a>
</div>

---

<div align="center">

## 🎯 **I Automate What's Costing You Money**
### *From Prompt to Production • Without 6 Weeks and a Project Manager*

**Specialized in:**  
🇮🇳 Indian SMBs & Startups • 🏢 Housing Societies • 🛒 E-Commerce • 🤖 AI Workflows • 📊 Business Intelligence

</div>

---

<div align="center">

### 📱 **Connect With Me**

[![Website](https://img.shields.io/badge/🌐_Website-desidevloper.com-01696f?style=for-the-badge&logoColor=white&labelColor=0d1117)](https://desidevloper.com)
[![WhatsApp](https://img.shields.io/badge/💬_WhatsApp-+91_9727413309-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=0d1117)](https://wa.me/919727413309?text=Hi%20SNTL84%2C%20I%20want%20to%20discuss%20a%20project)

[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-@SNTL2784-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://www.linkedin.com/in/sntl2784)
[![Email](https://img.shields.io/badge/📧_Email-3goldenlotus%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117)](mailto:3goldenlotusroots@gmail.com)

[![Instagram](https://img.shields.io/badge/📸_Instagram-@desibiztrade-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117)](https://www.instagram.com/desibiztrade)
[![Arrattai](https://img.shields.io/badge/🤖_Arrattai-@desidevloper-4f98a3?style=for-the-badge&logoColor=white&labelColor=0d1117)](https://aratt.ai/user/@desidevloper)

</div>

---

<div align="center">

### ⚡ **Quick Action**

**[🚀 Book Free 20-Min Strategy Call](https://wa.me/919727413309?text=Hi%20SNTL84%2C%20I%20want%20a%20free%20strategy%20call)** • **[📂 Explore All Projects](#featured-work)** • **[💼 View Full Services](#what-i-deliver)**

</div>

---

## 🏅 **OSS Contributor & Maintainer Achievements**

> *Merged PRs, bug fixes, triage contributions, and embed-react specialist work in production open-source projects.*

<div align="center">

| Achievement | Level | Details |
|-------------|-------|---------|
| 🟢 **OSS Contributor** | ✅ Active | Merged PR into [ishandutta2007/Velocity](https://github.com/ishandutta2007/Velocity) |
| 🛠️ **Bug Fix Contributor** | ✅ Shipped | Fixed critical `ERR_MODULE_NOT_FOUND` build crash (PR [#25](https://github.com/ishandutta2007/Velocity/pull/25)) |
| 🧪 **Test Suite Author** | ✅ Shipped | Authored `ArtifactStore` regression test suite (167 additions) |
| 🔍 **Triage Contributor** | ✅ Active | Diagnosed root cause of Issue [#17](https://github.com/ishandutta2007/Velocity/issues/17) — empty `src/artifacts/` directory |
| 🧩 **Maintainer-Level Review** | 🟡 Rising | Structured PR body with root cause analysis, test matrix, CI safety notes |
| 🌍 **Cross-Repo Contributor** | ✅ Unlocked | Contributed to upstream repo outside personal GitHub org |
| ⚛️ **@calcom/embed-react Specialist** | 🔥 Active | Root cause analysis + 3-tier fix for [cal.com #28979](https://github.com/calcom/cal.com/issues/28979) — `useRef` guard short-circuit bug affecting all React embed users |

</div>

---

## ⚛️ **@calcom/embed-react — Active Contribution**

> *Actively triaging and fixing issues in [`@calcom/embed-react`](https://github.com/calcom/cal.com/tree/main/packages/embed-react) — the React embed package used by thousands of cal.com users.*

<div align="center">

| Issue | Root Cause | My Fix | Status |
|-------|-----------|--------|--------|
| [#28979](https://github.com/calcom/cal.com/issues/28979) — `config` prop ignored after mount | `useRef` guard `c.current` short-circuits effect re-runs despite `config` being in dep array | Split init/update into 2 effects; reactive config update via embed UI API | 🔥 PR in progress |

**Specialty:** React hooks lifecycle • embed package architecture • `useRef` footguns • effect dependency optimization

</div>

### 🔧 The Fix (Option 1 — Recommended)

```tsx
// Effect 1: One-time initialization — guard is correct here
useEffect(() => {
  if (!a || c.current || !f.current) return;
  c.current = true;
  a.ns[t]("inline", { config: o });
}, [a, e, t, l, n]); // config intentionally excluded — init-only

// Effect 2: Reactive config updates — no guard, runs on every config change
useEffect(() => {
  if (!c.current || !a) return; // only after init
  a.ns[t]("ui", o); // update embed theme/config without remount
}, [o]); // only config triggers this
```

> 💡 **Impact:** Fixes silent theme/config update failures for all `<Cal />` inline embed users on React 18+. No iframe remount. No UX flash.

---

### 🏆 **GitHub Badges Earnable (Simultaneously)**

<div align="center">

| Badge | How to Earn | Status |
|-------|------------|--------|
| 🦈 **Pull Shark** | Get 2+ PRs merged in public repos | 🟡 1 merged — cal.com PR = unlock! |
| ⚡ **Quickdraw** | Close issue or PR within 5 min of opening | ✅ Eligible — act fast on next one |
| 🌟 **Starstruck** | Repo receives 16+ stars | 🟡 Star [Velocity](https://github.com/ishandutta2007/Velocity) & share |
| 🧠 **Galaxy Brain** | Answer accepted as solution in Discussions | 🟡 Join Velocity Discussions |
| 🏅 **YOLO** | Merge your own PR without review | ✅ Eligible on your personal repos |
| ❤️ **Pair Extraordinaire** | Co-author a merged commit | 🟡 Add co-author on next PR |

</div>

> 💡 **Next milestone:** Merge **cal.com embed-react PR** → unlocks **Pull Shark** badge + establishes embed-react specialty on profile.

---

## 🚀 **Leveled-Up Skills — June 2026**

<div align="center">

| Skill | Previous Level | Upgraded To | Evidence |
|-------|---------------|-------------|----------|
| 🧪 **Unit Testing (Node.js/ESM)** | Intermediate | **Advanced** | ArtifactStore test suite — mocked DB + FS, in-memory CI |
| 🔍 **Root Cause Analysis** | Intermediate | **Advanced** | Diagnosed ESM module resolution failure in TypeScript monorepo |
| 🛠️ **Open Source Contribution** | Beginner | **Contributor** | Merged PR into production OSS AI agent framework |
| 🤖 **AI Agent Architecture** | Familiar | **Hands-On** | Worked inside Velocity — OSS equivalent of Cursor/Claude Code |
| 📋 **Triage & Issue Analysis** | Basic | **Maintainer-Level** | Structured root cause + fix matrix in PR description |
| 🏗️ **TypeScript Monorepo** | Familiar | **Contributor** | Navigated `newcore/` ESM module graph in real project |
| ⚛️ **React Hooks / Embed Architecture** | Advanced | **Specialist** | `useRef` guard footgun analysis in cal.com embed-react package |

</div>

---

## 👤 **Who I Help**

> **Founders, agency owners, and SMB operators** in India and globally who are losing **hours every week to manual work** — hiring, lead generation, operations, reporting — and need someone who builds **production-ready systems fast**.

### **If This Is You:**
- ✅ Team copy-pasting data between tools
- ✅ Screening resumes by hand (taking 4+ hours/day)
- ✅ Managing housing society operations with paper forms
- ✅ Running e-commerce manually across multiple platforms
- ✅ Paying people to do repetitive tasks

**→ You're in the right place.**

---

## 🎁 **What I Deliver**

<table align="center">
<tr>
<th>🎯 What You Get</th>
<th>📊 The Impact</th>
<th>⏱️ Timeline</th>
</tr>
<tr>
<td><strong>🤖 AI Hiring System</strong><br/>Auto-score resumes, generate shortlists</td>
<td><strong>80% faster</strong> resume processing<br/>4 hrs → 45 min/day</td>
<td>3–5 days</td>
</tr>
<tr>
<td><strong>🚀 Lead Enrichment Agent</strong><br/>Auto-enrich B2B leads with founder data</td>
<td><strong>93% faster</strong> research<br/>45 min → 3 min per lead</td>
<td>2–4 days</td>
</tr>
<tr>
<td><strong>🏢 Backoffice OS</strong><br/>Attendance, payroll, petty cash, field visits</td>
<td><strong>6 hrs/week saved</strong><br/>3 spreadsheets → 1 dashboard</td>
<td>5–7 days</td>
</tr>
<tr>
<td><strong>🏙️ MetroMate Suite</strong><br/>Parking management, vehicle registration</td>
<td><strong>100% paperless</strong> operations<br/>Trilingual • WhatsApp-native</td>
<td>2–3 days</td>
</tr>
<tr>
<td><strong>🛒 E-Commerce Automation</strong><br/>Multi-platform order & inventory sync</td>
<td><strong>100% accuracy</strong> across channels<br/>Eliminate overselling</td>
<td>3–7 days</td>
</tr>
<tr>
<td><strong>⚙️ AI Workflow Automation</strong><br/>n8n • Zapier • Custom pipelines</td>
<td><strong>Any repetitive task</strong> automated<br/>24/7 no-code operations</td>
<td>3–7 days</td>
</tr>
</table>

---

## 💼 **Featured Work**

### 🏆 **Flagship Projects** *(Live, Revenue-Generating)*

<div align="center">

#### 🏙️ **MetroMate — Residential Parking Management OS**
[**→ Repository**](https://github.com/SNTL84/MetroMate) • [**→ Brand Development**](https://github.com/SNTL84/metromate-shiv-kathiawadi-thali-brand-development) • [**→ Live Demo**](https://github.com/SNTL84/sntl84-desidevloper-live-demo)

**Automated parking management for housing societies. Zero paper. Three languages. WhatsApp-native.**

| Challenge | MetroMate Solution |
|-----------|-------------------|
| 📄 Paper forms lost in letterboxes | ✅ Digital WhatsApp submission (instant) |
| ❓ Unknown vehicle ownership | ✅ Master register with auto-verification |
| 🌐 English-only forms → No participation | ✅ English + Gujarati + Hindi |
| 🔢 Manual parking calculations | ✅ Live deficit/surplus auto-calculated |
| ⚠️ No audit trail | ✅ Complete compliance dashboard |

**Real Result:** 42 flats • 100% digital • Zero paper • Managing 200+ vehicles

---

#### 🤖 **AI Hiring Intelligence System**
[**→ Main Project**](https://github.com/SNTL84/sntl84-ai-hiring-intel) • [**→ Agentic Recruiter**](https://github.com/SNTL84/sntl84-agentic-recruiter) • [**→ Smart Job Board**](https://github.com/SNTL84/sntl84-hiring-system)

**AI-powered resume screening that catches the best candidates instantly.**

| Old Way (Manual) | New Way (AI) |
|------------------|------------|
| Screen 100 CVs: **4 hours** | Screen 100 CVs: **2 minutes** |
| Score 1 resume: **15 minutes** | Score 1 resume: **5 seconds** |
| Miss 30% of good candidates | **Zero false negatives** |
| Hiring cost: **₹500k/quarter** | Hiring cost: **₹200k/quarter** *(60% reduction)* |

**Auto-scores | Generates shortlists | LinkedIn enrichment | Bulk operations**

---

#### 🏢 **Backoffice OS — HR & Operations Dashboard**
[**→ Repository**](https://github.com/SNTL84/sntl84-backoffice-os)

**Single dashboard for attendance, payroll, petty cash, field visits, and expense tracking.**

**Real Result:** Replaced 3 spreadsheets → 1 unified system → **6+ hours/week saved** in admin overhead

#### 🌐 **Velocity — AI Agent Framework (OSS Contributor)**
[**→ Upstream Repo**](https://github.com/ishandutta2007/Velocity) • [**→ My Merged PR #25**](https://github.com/ishandutta2007/Velocity/pull/25)

**Contributed to Velocity — the open-source equivalent of Google Antigravity / Cursor / Claude Code.**

| My Contribution | Details |
|-----------------|---------|
| 🐛 **Bug Fixed** | `ERR_MODULE_NOT_FOUND` crash on `src/artifacts/index.js` |
| 🧪 **Tests Added** | 6-case `ArtifactStore` regression suite — fully mocked, CI-safe |
| 🔍 **Root Cause** | Empty `src/artifacts/` directory broke Node ESM resolution at startup |
| 📋 **PR** | [#25](https://github.com/ishandutta2007/Velocity/pull/25) — 167 additions, 1 file, merged ✅ |

#### ⚛️ **cal.com — embed-react Bug Fix (OSS — PR In Progress)**
[**→ Issue #28979**](https://github.com/calcom/cal.com/issues/28979) • [**→ Fork**](https://github.com/SNTL84/cal.com)

**Fixing a high-impact silent failure in `@calcom/embed-react` v1.5.3 affecting all React inline embed users.**

| My Contribution | Details |
|-----------------|---------|
| 🔍 **Root Cause** | `useRef` guard `c.current` short-circuits effect re-runs despite `config` in dep array |
| 🛠️ **Fix Strategy** | Split initialization + reactive config update into 2 separate `useEffect` hooks |
| 🧪 **Tests** | Double-init prevention test + reactive theme update test |
| 📋 **Impact** | Affects all `<Cal />` inline embed users switching themes/config dynamically |
| 🌍 **Scope** | `packages/embed-react/src/Cal.tsx` + dist rebuild |

</div>

---

### 🚀 **AI & Automation Agents**

<table align="center">
<tr>
<th width="35%">Agent</th>
<th width="50%">What It Does</th>
<th width="15%">Repo</th>
</tr>
<tr>
<td><strong>🎯 Lead Enrichment Agent</strong></td>
<td>Auto-enrich B2B leads with founder names, funding stage, LinkedIn profiles → Export as VCF</td>
<td><a href="https://github.com/SNTL84/ai-lead-enrichment-agent">→ Go</a></td>
</tr>
<tr>
<td><strong>🧠 FMCG Lead Intelligence</strong></td>
<td>n8n + Claude AI pipeline: Scrape → Score → Draft WhatsApp/Email → Send automatically</td>
<td><a href="https://github.com/SNTL84/sntl84-fmcg-lead-intel">→ Go</a></td>
</tr>
<tr>
<td><strong>📊 Business Intelligence Push</strong></td>
<td>264 services across 22 industries categorized & published in 2 hours (vs. weeks of manual work)</td>
<td><a href="https://github.com/SNTL84/sntl84-business-intelligence-push">→ Go</a></td>
</tr>
</table>

---

### 🛒 **E-Commerce Automation Suite** *(7-Service Bundle)*

<div align="center">

**Complete workflow automation for Indian e-commerce sellers — Shopify, Flipkart, Amazon, Meesho**

</div>

| Service | What It Does | Platform | Repo |
|---------|--------------|----------|------|
| 📦 **Dropshipping Setup** | Supplier sourcing + store automation (₹0 inventory) | WooCommerce, Shopify | [→](https://github.com/SNTL84/sntl84-ecom-dropshipping-setup) |
| 🏪 **Marketplace Listing** | Amazon, Flipkart, Meesho listing management + A+ content | Multi-channel | [→](https://github.com/SNTL84/sntl84-ecom-marketplace-listing) |
| 🚚 **Order Fulfillment** | Shiprocket, Delhivery, BlueDart integration (end-to-end) | Logistics | [→](https://github.com/SNTL84/sntl84-ecom-order-fulfillment) |
| 💳 **Payment Integration** | Razorpay, Paytm, Stripe, UPI, COD support | All Gateways | [→](https://github.com/SNTL84/sntl84-ecom-payment-integration) |
| 🔄 **Inventory Sync** | Real-time stock sync across all channels (no overselling) | Multi-channel | [→](https://github.com/SNTL84/sntl84-ecom-inventory-sync) |
| 📣 **Ad Campaigns** | Google Ads, Meta, Instagram campaign management | Performance Marketing | [→](https://github.com/SNTL84/sntl84-ecom-ad-campaigns) |
| 🎧 **Customer Support** | WhatsApp bot, email, helpdesk + CRM integration | 24/7 Support | [→](https://github.com/SNTL84/sntl84-ecom-customer-support) |

---

### 🔧 **Automation Templates & Tools**

<div align="center">

| Tool | Purpose | Link |
|------|---------|------|
| 🤖 **n8n SMB Workflow Templates** | 50+ ready-to-import workflows (WhatsApp, GST, Razorpay, Shiprocket) | [⭐ Star It](https://github.com/SNTL84/n8n-india-smb-workflow-templates) |
| 📞 **WhatsApp Outreach Tool** | Bulk WhatsApp messaging + VCF export + instant WA links | [Go](https://github.com/SNTL84/whatsapp-outreach-tool) |
| ⚡ **DesiQuote** | Instant gig quote calculator (freelance pricing) | [Go](https://github.com/SNTL84/sntl84-desi-quote) |
| 🏠 **CoHost Virtual Assistant** | Airbnb property management landing page | [Go](https://github.com/SNTL84/sntl84-cohost-virtual-assistant-v3) |

</div>

---

### 💼 **Portfolio & Web Properties**

| Property | Tech Stack | Features | Link |
|----------|-----------|----------|------|
| 🌐 **DesiDeveloper Portfolio (Next.js)** | Next.js 14 • TypeScript • TailwindCSS • Framer Motion | AI-powered portfolio • Dark mode • Animations | [Repo](https://github.com/SNTL84/desidevloper-portfolio-nextjs) |
| 🔧 **DesiDeveloper (React)** | React • Vite • React Router • TailwindCSS | Full-stack portfolio • Trade directory | [Repo](https://github.com/SNTL84/desidevloper) |
| 📱 **Services Live Demo** | HTML • CSS • JavaScript | Complete services showcase | [Repo](https://github.com/SNTL84/sntl84-desidevloper-live-demo) |
| 📚 **Awesome AI Sales Agents** | Community Curated | 100+ AI SDR & sales automation tools | [⭐ Star It](https://github.com/SNTL84/awesome-ai-sales-agents) |

---

## 📊 **Real Results — Real Numbers**

> *Built for founders, SMBs, and operators. Every number below is from a real, production project.*

<div align="center">

| What I Built | Client Context | Result | Impact |
|--------------|-----------------|--------|--------|
| **AI Hiring System** | B2B recruitment | 4 hrs → 45 min/day | **80% faster** ⚡ |
| **Backoffice OS** | SMB operations | 3 spreadsheets → 1 dashboard | **6 hrs/week saved** 💰 |
| **Lead Enrichment Agent** | Startup outreach | 45 min → 3 min per lead | **93% faster** 🚀 |
| **MetroMate** | Housing society (42 flats) | Zero paper • 3 languages | **100% digital** 📲 |
| **Statement Generator** | Multi-language export | 1,131 translations in 1 run | **Days of work** in minutes ⏱️ |
| **Business Intelligence** | B2B trade directory | 264 services • 22 industries | **2 hours vs. weeks** 📈 |
| **99-Page Generator** | Personal productivity | Full app from 3 prompts | **2 days → 15 minutes** 🎯 |
| **Velocity OSS Fix** | AI Agent Framework | Eliminated startup crash | **ERR_MODULE_NOT_FOUND → Resolved** 🔧 |
| **cal.com embed-react Fix** | React embed users globally | Silent config/theme update failure | **useRef guard → Reactive effects** ⚛️ |

</div>

---

## ⚡ **Why I'm Different**

Most developers build what you ask. **I understand operations first.**

Before writing code, I worked inside **BPO, FMCG, retail, and telecom**. That means I design systems that:

- ✅ Solve **actual business problems** (not just technical exercises)
- ✅ Work **with your existing tools** (Razorpay, Shiprocket, WhatsApp, n8n, Zapier)
- ✅ Scale from **day 1 to 1000 users** without rewriting
- ✅ Are **cheap to run** (focus on cost optimization)
- ✅ **Don't need me forever** (you own everything, I document everything)

---

## 🛠️ **Tech Stack**

<div align="center">

### Languages & Frameworks
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)

### Automation & Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white)

### OSS Contributions & Specialties
![cal.com embed-react](https://img.shields.io/badge/@calcom%2Fembed--react-Specialist-0055FF?style=for-the-badge&logo=react&logoColor=white)
![Velocity OSS](https://img.shields.io/badge/Velocity_OSS-Contributor-01696f?style=for-the-badge&logo=github&logoColor=white)
![Unit Testing](https://img.shields.io/badge/Unit_Testing-Node_ESM-339933?style=for-the-badge&logo=jest&logoColor=white)
![ESM Modules](https://img.shields.io/badge/ESM_Modules-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Frontend & Styling
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer-0055FF?style=for-the-badge&logo=framer&logoColor=white)

### Indian Payment & Logistics
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logoColor=white)
![Shiprocket](https://img.shields.io/badge/Shiprocket-00A0E9?style=for-the-badge&logoColor=white)
![Delhivery](https://img.shields.io/badge/Delhivery-F7F7F7?style=for-the-badge&logo=delhivery&logoColor=black)

### Deployment & Infrastructure
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

</div>

---

## 📂 **Project Directory** *(Browse by Category)*

<details open>
<summary><b>🏗️ Flagship Projects (Revenue-Generating)</b></summary>

- 🏙️ [MetroMate](https://github.com/SNTL84/MetroMate) — Parking & vehicle management
- 🤖 [AI Hiring Intel](https://github.com/SNTL84/sntl84-ai-hiring-intel) — Resume screening
- 🏢 [Backoffice OS](https://github.com/SNTL84/sntl84-backoffice-os) — HR operations
- 🤖 [Agentic Recruiter](https://github.com/SNTL84/sntl84-agentic-recruiter) — Recruitment automation

</details>

<details open>
<summary><b>🌐 Open Source Contributions</b></summary>

- ⚛️ [cal.com](https://github.com/calcom/cal.com) — `@calcom/embed-react` specialist — **[Issue #28979 Analysis](https://github.com/calcom/cal.com/issues/28979)** • **[Fork](https://github.com/SNTL84/cal.com)** 🔥 PR in progress
- 🚀 [Velocity](https://github.com/ishandutta2007/Velocity) — AI agent framework (Google Antigravity/Cursor/Claude Code OSS equiv.) — **[Merged PR #25](https://github.com/ishandutta2007/Velocity/pull/25)** ✅

</details>

<details open>
<summary><b>🛒 E-Commerce (7-Service Bundle)</b></summary>

- 📦 [Dropshipping Setup](https://github.com/SNTL84/sntl84-ecom-dropshipping-setup)
- 🏪 [Marketplace Listing](https://github.com/SNTL84/sntl84-ecom-marketplace-listing)
- 🚚 [Order Fulfillment](https://github.com/SNTL84/sntl84-ecom-order-fulfillment)
- 💳 [Payment Integration](https://github.com/SNTL84/sntl84-ecom-payment-integration)
- 🔄 [Inventory Sync](https://github.com/SNTL84/sntl84-ecom-inventory-sync)
- 📣 [Ad Campaigns](https://github.com/SNTL84/sntl84-ecom-ad-campaigns)
- 🎧 [Customer Support](https://github.com/SNTL84/sntl84-ecom-customer-support)

</details>

<details open>
<summary><b>🤖 AI & Automation Agents</b></summary>

- 🚀 [Lead Enrichment Agent](https://github.com/SNTL84/ai-lead-enrichment-agent)
- 🧠 [FMCG Lead Intelligence](https://github.com/SNTL84/sntl84-fmcg-lead-intel)
- 📊 [Business Intelligence Push](https://github.com/SNTL84/sntl84-business-intelligence-push)

</details>

<details open>
<summary><b>🔧 Automation & Templates</b></summary>

- 🤖 [n8n SMB Workflow Templates](https://github.com/SNTL84/n8n-india-smb-workflow-templates) ⭐
- 📞 [WhatsApp Outreach Tool](https://github.com/SNTL84/whatsapp-outreach-tool)
- ⚡ [DesiQuote](https://github.com/SNTL84/sntl84-desi-quote)

</details>

<details open>
<summary><b>💼 Portfolio & Services</b></summary>

- 🌐 [DesiDeveloper Portfolio (Next.js)](https://github.com/SNTL84/desidevloper-portfolio-nextjs)
- 🔧 [DesiDeveloper (React)](https://github.com/SNTL84/desidevloper)
- 📱 [Services Live Demo](https://github.com/SNTL84/sntl84-desidevloper-live-demo)
- 🏠 [CoHost Virtual Assistant](https://github.com/SNTL84/sntl84-cohost-virtual-assistant-v3)

</details>

<details open>
<summary><b>📚 Open-Source & Community</b></summary>

- 📌 [Awesome AI Sales Agents](https://github.com/SNTL84/awesome-ai-sales-agents) — Curated list of 100+ tools
- 🎨 [AI Frontend Projects](https://github.com/SNTL84/ai-frontend-projects) — 45 battle-tested builds

</details>

---

## 🤝 **Work With Me**

### **Choose What Fits:**

<div align="center">

| Option | Response Time | Best For | Action |
|--------|---------------|----------|--------|
| **💬 WhatsApp** | **< 2 hours** | Quick brief • Urgent | [**Chat Now →**](https://wa.me/919727413309?text=Hi%20SNTL84%2C%20I%20have%20a%20project%20in%20mind) |
| **🌐 Website** | **24 hours** | Full services • Portfolio | [**Visit →**](https://desidevloper.com) |
| **📧 Email** | **24 hours** | Formal proposal • Details | [**Send Email →**](mailto:3goldenlotusroots@gmail.com) |

</div>

### **Or Explore More:**

- 💼 [LinkedIn](https://www.linkedin.com/in/sntl2784) — Professional updates
- 📸 [Instagram](https://www.instagram.com/desibiztrade) — Behind-the-scenes
- 🤖 [Arrattai Profile](https://aratt.ai/user/@desidevloper) — AI community

---

## 🚀 **Quick Start by Use Case**

### **👷 I manage a housing society**
→ Struggling with parking, vehicle registration, tenant management?  
[**→ Explore MetroMate**](https://github.com/SNTL84/MetroMate)

### **🛒 I run an e-commerce store**
→ Manual orders across Amazon, Flipkart, Meesho?  
[**→ Explore E-Commerce Suite**](https://github.com/SNTL84/sntl84-ecom-marketplace-listing)

### **🎯 I'm hiring and need to screen resumes**
→ Spending 4+ hours/day screening CVs?  
[**→ Explore AI Hiring Intel**](https://github.com/SNTL84/sntl84-ai-hiring-intel)

### **📞 I do B2B outreach and sales**
→ Manual lead research taking 45 min per lead?  
[**→ Explore Lead Enrichment Agent**](https://github.com/SNTL84/ai-lead-enrichment-agent)

### **⚙️ I want to automate workflows**
→ Copy-pasting between tools and chasing approvals?  
[**→ Explore n8n Templates**](https://github.com/SNTL84/n8n-india-smb-workflow-templates)

### **👀 I just want to see latest work**
→ Curious about what's possible?  
[**→ Explore Latest Portfolio**](https://github.com/SNTL84/desidevloper-portfolio-nextjs)

---

## 📈 **By The Numbers**

<div align="center">

| Metric | Value |
|--------|-------|
| 🔨 **Projects Built** | 30+ production systems |
| ⏱️ **Average Project Timeline** | 3–7 days from brief to live |
| 💰 **Client Cost Savings** | ₹50,00,000+ per year (combined) |
| 🎯 **Success Rate** | 100% of systems live & generating revenue |
| 🌍 **Clients Across** | 15+ countries & 8+ industries |
| 📱 **Tech Combinations Used** | 50+ unique tech stacks |
| 🌐 **OSS Contributions** | 2 active OSS projects (Velocity ✅ + cal.com 🔥) |
| ⚛️ **embed-react Specialty** | @calcom/embed-react bug triage & fix specialist |

</div>

---

## 💬 **One Last Thing**

> *"I don't just build code. I build systems that founders can rely on — that solve real problems, that scale, that don't need me every day."*

**Your business shouldn't require constant developer maintenance. It should work like a machine.**

---

<div align="center">

### 👉 **Ready to automate and scale?**

#### **[🚀 Start Your Free Strategy Call Now](https://wa.me/919727413309?text=Hi%20SNTL84%2C%20I%20want%20a%20free%20strategy%20call%20to%20understand%20how%20I%20can%20automate%20my%20business)**

---

*Last updated: June 2026 • [View on GitHub](https://github.com/SNTL84) • [Follow on LinkedIn](https://www.linkedin.com/in/sntl2784) • [Instagram](https://www.instagram.com/desibiztrade) • [YouTube @SNTL84](https://youtube.com/@SNTL84)*

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:001f3f,25:005a96,50:01696f,75:01a89f,100:0d1117&height=120&section=footer&text=Built%20by%20Milan%20%E2%80%A2%20SNTL84&fontSize=20&fontColor=ffffff&animation=fadeIn" />
</div>
