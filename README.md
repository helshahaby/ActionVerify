# DoneVerify

**From request → action → verified outcome.**

DoneVerify is a multimodal AI coworker that turns emails, meeting transcripts, spoken requests, typed notes, and uploaded text into actionable work. It guides the user through one action at a time, checks real evidence, independently evaluates whether the result satisfies the original request, and keeps a timestamped evidence trail.

## The problem

Most task tools stop at a checkbox. DoneVerify does not treat a claim, screenshot, or URL as completion by itself. An action is complete only when available evidence reasonably supports the original requirement. If a check cannot be performed or the evidence is insufficient, the result stays partial, unsupported, or unknown.

## Core workflow

1. **Capture** — paste an email or transcript, type, speak, or upload a text file.
2. **Understand** — preserve the original text and extract every distinct ask.
3. **Plan** — review and edit proposed actions; the coworker maintains action-specific completion checks.
4. **Work** — use voice or screen interaction with one shared current action.
5. **Verify** — submit a link, screenshot, or written confirmation for real inspection.
6. **Challenge** — Evidence Scout asks whether the observed outcome truly satisfies the request.
7. **Explain** — show status, confidence factors, sources, contradictions, graph, and timestamped history.

## Main features

- Email, meeting transcript, voice, typed, and text-file request intake
- Editable ordered action list with immediate agent awareness of updates
- Agent-owned, action-specific acceptance criteria
- Realistic portrait coworker with ElevenLabs voice and screen-only fallback
- Newest-first transcript and action switching during a session
- GitHub, generic web URL, video metadata, screenshot, and written-evidence checks
- Independent Evidence Scout with provenance labels
- Evidence-based confidence calculation
- Evidence graph connecting request → requirement → action → evidence → verification → Scout
- Timestamped history that preserves every verification attempt
- Private account data and private screenshot storage

## Verification principles

- A checkbox is not proof.
- A user statement is not proof.
- A screenshot or URL is evidence to inspect, not automatic completion.
- The agent cannot contradict the verification result.
- Infrastructure failures are reported as unknown, never blamed on the user.
- Completion requires a verified check and a supported Evidence Scout conclusion.

## Example walkthrough

A user pastes an email containing several separate asks: apply for project membership, apply for an account, and confirm storage access. DoneVerify proposes three distinct actions. The user edits the wording; the coworker immediately uses the updated list. During the live session the user submits a screenshot. DoneVerify reads what is visible, identifies what the screenshot cannot establish, compares those observations with the action, and either verifies completion or explains exactly what remains missing.

## Technology

- React 19 and TanStack Start
- TypeScript and Tailwind CSS
- Lovable Cloud for authentication, data, and private storage
- Lovable AI for structured request analysis, screenshot understanding, relevance judgement, and Evidence Scout
- ElevenLabs for coworker speech

## Project materials

- DoneVerify_Hossam_Elshahaby.pptx — six-slide presentation with click-driven transitions
- DoneVerify_Presentation_Video.mp4 — narrated presentation, under 90 seconds
- DoneVerify_Project_Description.pdf — detailed project brief

## Presenter

Hossam Elshahaby
