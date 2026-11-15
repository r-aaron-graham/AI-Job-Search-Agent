# AI Job Search Agent

Design specification for an assistant that finds job listings, drafts tailored application materials, and tracks application activity. This repository contains requirements and expected behavior for five modules.

## Review the design

Start with the [system overview](Documentation.md). The proposed workflow is to retrieve and filter job listings, use a selected listing to tailor application materials, and record application outcomes.

| Module | Design scope |
| --- | --- |
| [Job search](JobSearchModule.md) | Job-board retrieval, filtering, and listing storage |
| [Résumé and cover letter tailoring](ResumeTailoringModule.md) | Draft generation, editing, and finalization |
| [Application submission](ApplicationSubmissionModule.md) | Form navigation, uploads, and submission logging |
| [Tracking and logging](TrackingModule.md) | Local action records, filtering, and reporting |
| [Google integration](GoogleAPIIntegration.md) | Optional OAuth, calendar, and document integration |

**Status:** Design-stage project. The repository contains Markdown specifications and has no executable agent, dependency manifest, or deployment setup.
