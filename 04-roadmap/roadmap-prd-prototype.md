# Roadmap, PRD & Prototype (Module 4)

## Your strategic anchors
- **Persona (M2), who are you solving for?:** Drivers
- **Primary success metric (M3), your leading indicator:** 3.4 times reduction in average daily time lost to manual workarounds, returning to the ~9 minutes of two years ago.
- **Moment of misery (M2), the specific friction blocking the goal:** To mark delivered, the driver navigates through three screens while physically carrying a package and navigating varied types of weather, including rain. Drivers end up sending a text/SMS to the dispatcher/coordinator instead of using the platform to report a delivered status.
- **Guardrail metric (M3), what must not drop or break:** Logging compliance checks must not increase for coordinators (14.6 minutes)

## Scan the backlog & set a human baseline
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** B1 - because marking delivery complete will be included in the Compliance Checklist

B2 - delivery complete should also be part of the daily reporting 

B6 - Driver Alert Notifications will alert driver when they have forgotten to mark a completed delivery.

## Audit, override & decide
- **Where did you override the AI? (feature + old vs. new score + why):** B1. Old score: value 3, effort 2. New score: value 4, effort 3. Does not solve delivery confirmation directly but protects the coordinator guardrail by reducing the 14.6-minute compliance burden while freeing capacity to support driver workflow changes. 

B5. Old score: value 2, effort 1. New score: value 3, effort 1. AI listed this as a nice to have if capacity remains and says it may reduce confusion in workflows. The effort is low (and cheap), so increasing the value here.

B6. Old score: value 3, effort 2. New score: value 4, effort 2. This feature is the only one that targets drivers and it will help them mark deliveries complete. Could reduce out-of-band communication
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** No
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** It underweighted B5 (step progress indicator)

## Generate your interactive roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** B5. Step Progress Indicator
B6. Driver Alert Notification
- **What I cut, and the “no” I’m protecting the scope from:** B3. Shift Handoff Wizard
B4. Mobile-first Coordinator Dashboard
B7. Contextual AI ETA Display
B8. Fleet Analytics Manager View
- **Prototype/roadmap screenshot link (paste into your deliverables):** https://github.com/jessiemccreary-dotcom/pm-final-project/blob/main/04-roadmap/HTML-preview.png
