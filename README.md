# Vilinq Prototype Demo (Single-File, Browser Ready)

This repo includes a polished, startup-quality Vilinq prototype built with **HTML/CSS/vanilla JavaScript only**.

## Open the demo
No server required:
1. Open `vilinq-demo.html` directly in your browser (double-click).
2. Or open `index.html` (same experience).

## Included demo flows
- Welcome screen with Vilinq branding
- Provider Login flow (mock, no real auth)
- Multi-step Provider Onboarding wizard
- Provider Dashboard with:
  - KPI cards
  - chart placeholders
  - notification center
  - recent activity
  - payment trend placeholders
- Parent Payment View with:
  - plan selection
  - payment history
  - saved payment methods
  - autopay reminder
  - downloadable receipt button
- Why Now + How Vilinq Works sections

## Notes
- Prototype only — no backend, no authentication, no payment processing.
- Intended for demos/investor previews/provider walkthroughs.


## New Checkout Demo Features
- Secure checkout modal/page simulation
- Saved card selection + add new card form
- Billing address capture section
- Pay Now processing animation + loading state
- Success and failed payment simulation
- Payment confirmation receipt UI
- Download receipt + return to dashboard
- Dashboard updates after successful payment (reduced balance + activity update)


## Provider-to-Family Invitation Workflow
- Invite Family button on Provider Dashboard
- Invite modal with parent/child/tuition/plan fields
- Invitation sent state + parent onboarding preview
- Parent actions: accept invite, choose plan, add payment method, enable autopay
- Invite status tracking: Sent, Pending, Accepted, Payment Active


## Subsidy assistance and gap workflow
- Subsidy alerts and expiring warnings in Provider Dashboard
- Subsidy gap tracking KPI cards and uncovered gap indicators
- Assist Family modal for delay/change reporting and gap estimation
- Flexible options: split payments, weekly payments, subsidy bridge support
- Visual statuses: At risk, Pending subsidy, Gap resolved, Payment protected
- Educational cards on continuity and enrollment disruption prevention


## Advanced Provider Analytics
- Dedicated Analytics page in top navigation
- KPI cards for collections, subsidy gaps, plans, outstanding trends, and retention
- Interactive chart placeholders for:
  - Monthly payment trends
  - Enrollment stability
  - Outstanding balance trends
  - Subsidy gap metrics
  - Retention indicators
- Time filters: Weekly, Monthly, Quarterly


## Settings & Profile Management
- Provider settings: center profile, tuition preferences, flexibility settings, branding/logo placeholder, notifications, team access
- Family settings: saved payment methods, autopay preferences, notification settings, billing contacts, child profiles
- Editable forms, toggle switches, profile avatar placeholders, and save confirmation animation


## Notifications and Messages Center
- Notification dropdown panel with provider and parent alerts
- Read/unread states with mark-all-read support
- Message inbox with conversation preview cards
- Timestamp indicators for alerts and messages
- Includes late payments, subsidy reminders, parent responses, confirmations, autopay reminders, and enrollment risk alerts
