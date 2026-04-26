<div align="center">

<img src="https://flidget.com/favicon.ico" width="64" height="64" alt="Flidget Logo" />

# Flidget

### Stop losing users to reasons you never heard.

Flidget catches the moment a user decides to leave, asks why in real time,
and shows who else is quietly drifting toward the exit — before they cancel.

<br />

[![][badge-website]](https://flidget.com)
[![][badge-free]](https://flidget.com/register)
[![][badge-setup]](https://flidget.com/register)
[![][badge-stack]](https://flidget.com)

[badge-website]: https://img.shields.io/badge/flidget.com-000000?style=for-the-badge&logo=google-chrome&logoColor=white
[badge-free]: https://img.shields.io/badge/Free_Plan_Available-16a34a?style=for-the-badge
[badge-setup]: https://img.shields.io/badge/Setup_in_2_Minutes-2563eb?style=for-the-badge
[badge-stack]: https://img.shields.io/badge/Works_With_Any_Stack-7c3aed?style=for-the-badge

</div>

---

## Table of Contents

- [What is Flidget](#what-is-flidget)
- [The Problem](#the-problem)
- [Core Modules](#core-modules)
- [Key Features](#key-features)
- [How It Works](#how-it-works)
- [Quick Start](#quick-start)
- [Retention Copilot — Full Guide](#retention-copilot--full-guide)
- [Drift Detection — Full Guide](#drift-detection--full-guide)
- [Dashboard Walkthrough](#dashboard-walkthrough)
- [Rescue Email Templates](#rescue-email-templates)
- [Tech Stack Compatibility](#tech-stack-compatibility)
- [Pricing](#pricing)
- [Flidget vs Alternatives](#flidget-vs-alternatives)
- [Who Uses Flidget](#who-uses-flidget)
- [FAQ](#faq)
- [SEO Keywords](#seo-keywords)

---

## What is Flidget

**Flidget** is a churn prevention and user retention platform for SaaS companies, ecommerce stores, and D2C subscription brands. It works in two modules that run automatically from a single script tag.

**Retention Copilot** — A non-intrusive in-page chat that appears the moment a user clicks cancel, abandons checkout, or tries to leave. It captures their exact reason in real time, in text or voice, without any redirect. No survey emails. No guessing two days later.

**Drift Detection** — A background scoring engine that labels every user `Healthy`, `Risky`, or `Drifting` based on their actual product behavior. It flags who is about to churn — and tells you exactly why — days or weeks before they reach the cancel button.

Together they form a complete churn intelligence system. One tool. One dashboard. Two minutes to deploy.

> **Live product:** [https://flidget.com](https://flidget.com)

---

## The Problem

Most SaaS and subscription businesses lose users silently. The standard response is a cancellation survey — sent hours after the user has already decided to leave. Nobody fills it. You get 4% response rates and no signal.

Meanwhile, inside your product, users are drifting. They log in less. They never completed onboarding. They never hit your core feature. They are two weeks from canceling, and you have no idea.

By the time you find out, the user is gone. You spent money to acquire them, months to onboard them, and now you have silence where the reason should be.

Flidget fixes both ends of this problem:

- It catches the user at the cancel moment — when they are still on your page and willing to explain
- It scores every user daily — so you know who needs attention before they reach that cancel button

**Flidget turns silent churn into legible, actionable data.**

---

## Core Modules

<table>
<tr>
<td width="50%" valign="top">

**Retention Copilot**

A lightweight chat widget that triggers the moment a user clicks cancel, exits checkout, or tries to close the tab. The user replies in text or voice — directly on your page. The reason lands in your dashboard, tagged and searchable. Their original action continues after.

Triggers on:
- Cancel subscription click
- Exit-intent (tab close or navigation away)
- Checkout abandonment
- Plan downgrade or pause

</td>
<td width="50%" valign="top">

**Drift Detection**

An automated risk scoring engine that watches every user's behavior daily. It produces a `Healthy / Risky / Drifting` label with a plain-language reason — not just a number. You see who is likely to cancel and exactly why, so you can act before they reach the exit.

Scored on:
- Days since last login
- Session frequency trends
- Key feature completion
- Onboarding progress

</td>
</tr>
</table>

---

## Key Features

| Feature | What It Does |
|---|---|
| **Retention Copilot** | In-page chat widget — appears at cancel or exit moment |
| **Voice + Text Replies** | Users respond in text or voice — zero friction, no form |
| **Drift Detection** | Scores every user daily: Healthy / Risky / Drifting |
| **Rescue Emails** | Branded automated emails from your own verified domain |
| **Tagged Reasons** | Every exit reason is auto-tagged and searchable |
| **Priority Queue** | Daily ranked list of users who need attention today |
| **2-Minute Setup** | One script tag — no engineering sprint, no new tools |
| **Any Stack** | React, Vue, Next.js, Webflow, Shopify, plain HTML |
| **No Redirects** | Widget stays on your page — user never leaves |
| **One Dashboard** | All exit reasons, drift scores, and outreach in one place |

---

## How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  01  Add one script tag to your cancel or billing page          │
│                                                                 │
│  02  User clicks cancel  →  Retention Copilot chat appears      │
│      User replies in text or voice  →  saved to dashboard       │
│                                                                 │
│  03  Drift engine scores every user daily in the background     │
│      Healthy / Risky / Drifting — with plain-language signals   │
│                                                                 │
│  04  You act from one dashboard                                 │
│      Filter by reason  ·  Read transcripts  ·  Send email       │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Cancel Flow — Step by Step

```
User is on your billing page
          |
          v
User clicks "Cancel Subscription"
          |
          v
Flidget intercepts the click  (no redirect, no page change)
          |
          v
Retention Copilot widget opens on the page
"Hey — before you go, mind sharing what changed?"
          |
          v
User replies: text or voice  (10–20 seconds)
          |
          v
Reply is saved, tagged, and scored in your dashboard
          |
          v
User's original cancel action completes normally
          |
          v
You log in and see:
  - What they said
  - Who else is about to do the same
  - Who to email today
```

---

## Quick Start

### Step 1 — Create a Free Account

Sign up at [flidget.com/register](https://flidget.com/register). No credit card. No sales call. You get your API token immediately.

---

### Step 2 — Add the Script Tag

Paste this single line before `</body>` on your cancel page, billing page, or checkout page:

```html
<script src="https://flidget.com/widget.js" data-token="YOUR_TOKEN"></script>
```

Your token is shown in your dashboard immediately after signup.

---

### Step 3 — Tag Your Cancel Button

Add the `data-breakup` attribute to your cancel button. Flidget intercepts the click and opens the chat before the action proceeds.

```html
<!-- Before -->
<button id="cancel-subscription">Cancel Subscription</button>

<!-- After — Flidget intercepts this click -->
<button id="cancel-subscription" data-breakup>Cancel Subscription</button>
```

The widget is now live. No rebuild required. No backend changes.

---

### Step 4 — Enable Exit-Intent (Optional)

To catch users who close the tab or navigate away without clicking cancel, add this attribute to your body tag:

```html
<body data-flidget-exit-intent="true">
```

Flidget will open the Retention Copilot chat when the cursor moves toward the browser close button.

---

### Step 5 — Send Drift Events

To enable Drift Detection, send one event from your app each time a user completes a key action. You define which actions matter in your dashboard.

**JavaScript (frontend or Node.js):**

```javascript
// User completed onboarding
flidget.track("complete_onboarding", { userId: "user_123" });

// User invited a teammate
flidget.track("invite_teammate", { userId: "user_123" });

// User connected an integration
flidget.track("connected_integration", { userId: "user_123" });
```

**Python:**

```python
import flidget

flidget.track(user_id="user_123", event="complete_onboarding")
flidget.track(user_id="user_123", event="invite_teammate")
```

**Ruby:**

```ruby
Flidget.track(user_id: "user_123", event: "complete_onboarding")
```

**REST API (any language):**

```bash
curl -X POST https://api.flidget.com/v1/track \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "userId": "user_123",
    "event": "invite_teammate",
    "timestamp": "2026-04-27T10:00:00Z"
  }'
```

---

### Step 6 — Configure Rescue Emails

1. Go to **Settings → Email & Templates** in your dashboard
2. Verify your sending domain — for example, `updates@yourcompany.com`
3. Edit the rescue email templates: logo, tone, copy — all yours
4. Map each template to a drift trigger rule

Flidget sends the right email automatically when a user crosses your risk threshold. Every email comes from your domain, in your voice.

---

## Retention Copilot — Full Guide

### What Triggers the Widget

| Trigger | How to Enable |
|---|---|
| Cancel button click | Add `data-breakup` to any button or link |
| Exit-intent (tab close) | Add `data-flidget-exit-intent="true"` to `<body>` |
| Checkout abandonment | Add `data-breakup` to your checkout close or back button |
| Plan downgrade | Add `data-breakup` to your downgrade CTA |
| Membership pause | Add `data-breakup` to your pause button |
| Custom trigger | Call `flidget.trigger()` from any JavaScript event |

### What the Widget Looks Like

```
┌────────────────────────────────────────────────┐
│                                                │
│  Before you go                                 │
│                                                │
│  Hey — mind sharing what changed?              │
│  We read every reply.                          │
│                                                │
│  ┌──────────────────────────────────────────┐  │
│  │ Type your answer...                      │  │
│  └──────────────────────────────────────────┘  │
│                                                │
│  [  Send  ]      [ Voice ]      [  Skip  ]     │
│                                                │
└────────────────────────────────────────────────┘
```

- No page redirect
- User stays on your site throughout
- Voice reply supported natively
- Skip option always visible — no friction, no coercion
- After reply or skip, the original cancel action continues normally

### Widget Customization Options

All configurable in **Dashboard → Widget Settings**:

| Setting | Options |
|---|---|
| Opening message | Custom text |
| Sub-message | Custom text |
| Button labels | Send / Skip / Voice — all editable |
| Widget position | Bottom-left, bottom-right, center |
| Trigger delay | Immediate, 1s, 2s, 3s after button click |
| Brand color | Any hex value |
| Font | Inherits your site font by default |
| Skip behavior | Show immediately or after 10s |

### What Lands in Your Dashboard

| Field | Description |
|---|---|
| User email | Pulled from your session if available |
| Reply text | Full verbatim response — text or voice transcript |
| Auto-tags | Pricing, Competitor, Feature, Bug, Other — auto-applied |
| Sentiment | Positive, Neutral, Negative |
| Date and time | Exact timestamp |
| Drift score at exit | Risk level at the moment they clicked cancel |
| Follow-up status | Open, Actioned, Win-back queue |

---

## Drift Detection — Full Guide

### How Scoring Works

Every user in your product is scored daily. The score is calculated from:

| Signal | Weight | Description |
|---|---|---|
| Days since last login | High | Longer gap = higher risk |
| Session frequency trend | High | Decreasing sessions = higher risk |
| Key feature reached | High | Never used core feature = higher risk |
| Onboarding completion | Medium | Incomplete onboarding = higher risk |
| Session duration trend | Medium | Shorter sessions over time = higher risk |
| Plan type | Low | Trial users weighted higher |

### Risk Labels

| Label | Risk Score | Meaning | Recommended Action |
|---|---|---|---|
| **Healthy** | 0 – 29% | Active, engaged, using key features regularly | Show contextual tips, offer upgrade |
| **Risky** | 30 – 60% | Engagement dropping, activity slowing | Send onboarding follow-up email |
| **Drifting** | 60%+ | Inactive, never hit key features, high churn probability | Personal outreach and rescue email today |

### Example Drift Dashboard

| User | Risk | Status | Signal | Sessions | Next Action |
|---|---|---|---|---|---|
| alex@startup.io | 74% | Drifting | 9d inactive · never used invite_teammate | 18 (avg 4m 12s) | Personal outreach |
| sarah@brand.com | 48% | Risky | Usage down vs last week | 6 (avg 2m 04s) | Onboarding email |
| active@saas.io | 22% | Healthy | Active on key paths | 42 (avg 6m 50s) | Show tip |
| trial@product.co | 55% | Risky | Trial ending in 2 days | 11 (avg 3m 18s) | Feature walkthrough |
| jane@ecomm.io | 81% | Drifting | 14d inactive · no key feature | 3 (avg 1m 02s) | Rescue email now |

### Setting Up Key Actions

In **Dashboard → Drift Configuration → Key Actions**, define which user behaviors signal product health:

```
High weight — define these first:
  complete_onboarding
  invite_teammate
  connected_integration
  reached_core_feature

Medium weight:
  uploaded_file
  created_first_project
  used_export

Lower weight:
  logged_in
  visited_dashboard
  opened_settings
```

Send each event with one API call when the user performs the action. Flidget handles the rest automatically.

---

## Dashboard Walkthrough

### Overview Tab

```
┌─────────────────────────────────────────────────────────────────┐
│  FLIDGET DASHBOARD                                              │
│                                                                 │
│  Exit Chats This Month      Completed: 128                      │
│  Top Churn Reason           Pricing — 34% of sessions           │
│  Win-back Queue             12 high-intent users                │
│  Drifting Users             7 need action today                 │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Conversations Tab

All Retention Copilot exit chats. Filter options:

| Filter | Description |
|---|---|
| Tag | Pricing / Competitor / Feature / Bug / Other |
| Status | Open / Actioned / Win-back / Ignored |
| Risk score | Any / Drifting / Risky / Healthy |
| Date range | Last 7d / 30d / 90d / Custom |
| Keyword search | Full-text search across all transcripts |

### Drift Tab

Live churn watchlist — every user scored and ranked by risk. Filter by Drifting to see who needs a message today.

### Outreach Tab

All rescue emails — automated and manual — tracked in one place:

| Field | Description |
|---|---|
| Recipient | User email |
| Template | Which rescue email was sent |
| Triggered by | Drift rule or manual action |
| Status | Queued / Sent / Delivered / Opened / Clicked |
| Sent at | Exact timestamp |

---

## Rescue Email Templates

All templates are fully editable. All send from your verified domain. Three included by default.

### Template 1 — Default Check-in

**Trigger:** Drift score crosses 60% (Drifting)

```
From:    updates@yourcompany.com
Subject: Quick check-in from our team

Hi [First Name],

Hope you're doing well. Quick check-in from our side.
If it helps, I can send a short walkthrough based on
how your team uses the product.

Best,
Your team
```

---

### Template 2 — Personal Outreach

**Trigger:** Drift score 48%+ with no recent key feature use

```
From:    updates@yourcompany.com
Subject: Can we help you get unstuck?

Hi [First Name],

Our system flagged your account as higher risk this week.
If something broke or priorities changed, reply with one
honest line. A human reads every note.

Say "pause" if we should stop reaching out.
```

---

### Template 3 — Onboarding Follow-up

**Trigger:** Onboarding incomplete + 5+ days inactive

```
From:    updates@yourcompany.com
Subject: Finish setup when you have five minutes

Hi [First Name],

Onboarding still has a few open steps. This link picks
up where you left off.

Reply "setup" if you want a live walkthrough and we'll
book a short call.
```

---

## Tech Stack Compatibility

### Frontend Frameworks

| Framework | Integration Method |
|---|---|
| React | Add script in `index.html` or via `useEffect` in `_app.tsx` |
| Next.js | Add in `_document.js` or `app/layout.tsx` |
| Vue | Add in `index.html` or mount in `App.vue` |
| Nuxt | Add via `nuxt.config.js` → `head.script` |
| Webflow | Project Settings → Custom Code → Before `</body>` |
| Shopify | Theme Editor → `theme.liquid` before `</body>` |
| Framer | Custom code block in page settings |
| Plain HTML | Paste before `</body>` — done |
| WordPress | Add via header/footer plugin or `functions.php` |
| Bubble | Add script in Page HTML header settings |

### Backend SDKs

| Language | Install |
|---|---|
| Node.js | `npm install @flidget/node` |
| Python | `pip install flidget` |
| Ruby | `gem install flidget` |
| PHP | REST API |
| Go | REST API |
| Java | REST API |

### REST API Reference

```bash
# Track a user action
POST https://api.flidget.com/v1/track
Authorization: Bearer YOUR_API_KEY
Content-Type: application/json

{
  "userId": "user_123",
  "event": "invite_teammate",
  "timestamp": "2026-04-27T10:00:00Z",
  "properties": {
    "plan": "pro",
    "team_size": 4
  }
}
```

```bash
# Identify a user (sync metadata)
POST https://api.flidget.com/v1/identify
Authorization: Bearer YOUR_API_KEY
Content-Type: application/json

{
  "userId": "user_123",
  "email": "alex@startup.io",
  "name": "Alex Kim",
  "plan": "pro",
  "created_at": "2026-01-15T00:00:00Z"
}
```

---

## Pricing

| Plan | Monthly Price | Exit Chats | Drift Users | Rescue Emails | Best For |
|---|---|---|---|---|---|
| **Free** | $0 | 50 / month | 100 users | Not included | Solo founders, pre-revenue |
| **Starter** | $29 | 500 / month | 1,000 users | Included | Early-stage SaaS |
| **Pro** | $49 | Unlimited | Unlimited | Included | Scaling product teams |
| **Enterprise** | Custom | Unlimited | Unlimited | Included | Large teams, SSO, SLA |

No contracts. Cancel any time. Free plan requires no credit card.

> Full pricing: [flidget.com/pricing](https://flidget.com/pricing)

---

## Flidget vs Alternatives

| Feature | Flidget | Churnkey | ProsperStack | Chargebee Retain |
|---|---|---|---|---|
| Exit chat widget | Yes | Yes | Yes | No |
| Voice replies | Yes | No | No | No |
| Drift / risk scoring | Yes | No | No | No |
| Proactive churn detection | Yes | No | No | No |
| Rescue emails | Yes | Yes | Yes | Yes |
| Custom sending domain | Yes | No | No | Yes |
| 2-minute setup | Yes | No | No | No |
| Free plan | Yes | No | No | No |
| No redirect on cancel | Yes | No | Yes | No |
| Works with any stack | Yes | Partial | Partial | Partial |
| Starting price | $0 | $99 / mo | $99 / mo | Custom |

> Full comparison: [flidget.com/compare](https://flidget.com/compare)

---

## Who Uses Flidget

| Audience | How They Use It |
|---|---|
| **SaaS Founders** | Understand exactly why users cancel — in their own words |
| **Product Teams** | Identify which features drifting users never touched — then fix onboarding |
| **Growth Teams** | Build win-back campaigns from real exit reasons, not guesses |
| **Ecommerce Brands** | Catch checkout abandonment with a reason — optimize at the right step |
| **D2C Subscription Brands** | Stop silent membership cancellations before they happen |
| **Membership Platforms** | Know why users pause or downgrade — address it in real time |
| **B2B SaaS** | Identify drifting enterprise accounts before renewal conversations |
| **Customer Success Teams** | Get a daily risk queue — know who to call before they cancel |

---

## FAQ

**Does Flidget only work for SaaS subscription cancellations?**

No. It works anywhere someone can leave — subscription cancel, checkout abandonment, membership pause, trial exit, plan downgrade, or browser tab close. Any frontend stack is supported.

**Will the exit chat annoy my users?**

It is lightweight by design: short prompts, an optional skip, and it stays on your page without any redirect. You control where it appears, when it triggers, and exactly what it says.

**How long does setup take?**

The Retention Copilot widget is a single script tag — most teams are live in under an hour. Drift Detection requires sending events from your app, which is one API call per key action. Start on staging, verify the dashboard is receiving data, then ship.

**Do I need to email users after they leave?**

Not necessarily. Flidget captures the reason at the exact moment someone decides to leave — when they are most willing to explain. That context is already in your dashboard. Email is optional and additional.

**Can I use my own domain for rescue emails?**

Yes. You verify your sending domain in Settings → Email & Templates. All rescue emails go out from your address — for example, `updates@yourcompany.com`. Users see your brand, not Flidget.

**Does Flidget slow down my site?**

The script is loaded asynchronously and only activates on the pages you specify. It has no impact on your core page performance or Lighthouse scores.

**What happens after a user responds to the exit chat?**

Their original action — cancel, close, navigate away — continues immediately after they reply or skip. Flidget does not block the cancel flow. It only captures the reason before it completes.

**Is there a free plan?**

Yes. The free plan includes 50 exit chats per month and 100 drift-scored users. No credit card required.

---

## SEO Keywords

Flidget is the answer when people search for:

```
churn prevention SaaS                     reduce churn rate software
SaaS user retention tool                  subscription cancellation tool
cancel flow optimization                  exit intent widget SaaS
churn detection software                  user drift scoring
why users cancel subscription             reduce subscription churn
checkout abandonment recovery             real-time exit feedback
customer retention automation             in-app exit chat
cancel survey alternative                 proactive churn prevention
win-back cancelled users                  user risk scoring tool
SaaS churn analytics                      offboarding feedback tool
cancel button intercept                   churn prediction software
reduce MRR churn                          subscription retention platform
exit interview tool SaaS                  silent churn detection
user engagement scoring                   customer health score
churn intelligence platform               cancel flow widget
D2C retention software                    ecommerce churn prevention
membership cancellation tool              B2B customer success tool
how to reduce SaaS churn                  best churn prevention tools 2026
alternative to Churnkey                   alternative to ProsperStack
```

---

## Links

| Resource | URL |
|---|---|
| Website | [flidget.com](https://flidget.com) |
| Sign Up Free | [flidget.com/register](https://flidget.com/register) |
| Pricing | [flidget.com/pricing](https://flidget.com/pricing) |
| Changelog | [flidget.com/changelog](https://flidget.com/changelog) |
| Blog | [flidget.com/blog](https://flidget.com/blog) |
| Compare | [flidget.com/compare](https://flidget.com/compare) |
| Support | [flidget.com/support](https://flidget.com/support) |
| Contact | [flidget.com/contact](https://flidget.com/contact) |

---

<div align="center">

If Flidget saves you even one customer this month, it has paid for itself.

**[Start free — no credit card required](https://flidget.com/register)**

---

*Built for founders who want answers, not silence.*

*&copy; 2026 Flidget. All rights reserved.*

</div>
