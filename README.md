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


## UX polish and microinteractions
- Smooth fade/slide transitions between screens
- Hover and press microinteractions on cards/buttons
- Animated KPI counters and onboarding progress indicators
- Skeleton loading state before analytics chart render
- Animated chart placeholders (bars/line), empty-state cards, and success check animation
- Sticky nav, mobile-first spacing refinements, and toast confirmations


## Investor Demo section
- Startup-style hero messaging with Book a Demo CTA and waitlist email capture
- ROI calculator, impact counters, recovery metrics, and affordability statistics
- Problem vs Solution, market opportunity, pricing, testimonials, FAQ accordion, and footer links
- Animated storytelling components for accelerator/investor presentation flows


## Parent Mobile App simulation
- iPhone-style in-browser phone mockup
- Parent dashboard, payment reminders, confirmation, tuition breakdown
- Split and weekly payment setup screens
- Subsidy support status and payment calendar
- Family profile, child enrollment, in-app messaging
- Mobile login/signup and onboarding flow
- Bottom navigation, swipeable cards, push notification previews, notification badges, FAB, and loading animations


## AI Insights section
- New AI Insights page for providers and parents
- Enrollment/retention risk scoring badges and predictive cards
- AI-generated recommendations, summaries, next actions, and automation center
- Parent-focused smart plan and financial wellness guidance
- Simulated AI assistant widget/chat bubble with recommendation responses


## Series A product polish refinements
- Upgraded visual hierarchy, spacing, typography rhythm, and premium shadows
- Enhanced chart placeholders, loading states, and empty states
- Improved onboarding experience with launch checklist guidance
- Added accessibility-friendly input labels for key interactive fields
- Strengthened responsive behavior and enterprise SaaS consistency


## Interactive analytics charts
- Replaced placeholder analytics visuals with animated line, bar, and donut charts rendered in-browser using pure JS/CSS
- Added hover tooltips and realistic childcare-fintech trend data for payment, retention, subsidy gap, and forecasting narratives
- Maintains single-file, backend-free compatibility


## Expanded AI Assistant
- Expandable AI support modal with suggested prompts and typing animation
- Simulated provider workflow recommendations and parent financial guidance
- Smart automation suggestions with realistic AI-generated outputs
- Quick actions: Generate outreach message, Predict enrollment risk, Recommend payment plan


## Fully interactive onboarding wizard
- 10-step guided setup flow with progress bar and step transitions
- Includes welcome, center info, tuition, classroom, parent invites, banking, branding, notifications, and AI setup
- Interactive validation for required fields and recommended defaults
- Completion celebration screen before entering dashboard


## Live production-like interactions
- Added auto-refresh dashboard simulation for balances and live activity feed updates
- Expanded micro-interactions, hover elevation, and smoother transitions
- Added additional empty states, toasts, and success/error interaction polish
- Enhanced loading skeleton and dynamic in-use behaviors for provider/parent realism


## Enterprise Admin Dashboard
- Multi-location management view for childcare networks/agencies
- Organization-wide analytics, provider health scoring, and at-risk center monitoring
- Regional enrollment insights, revenue recovery tracking, subsidy usage trends
- Staff performance summaries and network benchmarking visuals
