
# WITHIN — MVP

## Project purpose

WITHIN is an AI-powered voice companion designed to support people navigating alcohol and drug recovery.

This repository supports the controlled development of the WITHIN MVP for internal testing and technical validation.

## Current stage

MVP build — October/November 2026.

The product is under development. Features must not be described as complete until they have been implemented and tested.

## Working principles

- Build only from approved WITHIN specifications.
- Keep code, technical documentation and versioned prompts under version control.
- Make small, reviewable changes rather than large, uncontrolled changes.
- Test features against agreed acceptance criteria.
- Record important product and technical decisions in the shared Notion workspace.
- Document known issues, limitations and unresolved risks.
- Do not use restricted code, prompts, architecture or confidential materials from former collaborators.

## Proposed technology stack

- Lovable / React — application development
- Supabase — database and backend
- Hume EVI — voice interaction
- Claude — AI conversation and reasoning

These are proposed components until the integrations and data flows have been validated.

## Security and privacy

- Never commit API keys, passwords, tokens or other secrets.
- Never commit real user conversations or sensitive health information.
- Keep credentials in appropriate secure environment settings.
- Use test data during development.
- Verify access controls, consent, data retention and deletion before any authorised real-user testing.

## Project documentation

The shared Notion workspace is the source of truth for:

- Master build plan and task tracker
- Product decisions and specifications
- Meeting notes and build log
- Risks, blockers and test results

## Definition of done

A task is complete only when:

1. The agreed acceptance criteria are met.
2. The relevant functionality has been tested.
3. Known issues are documented.
4. Evidence of the result is recorded in Notion.
5. The change is saved in GitHub.

## Status

This repository is part of the WITHIN MVP development process. Its existence does not mean the product is ready for release or real-user testing.
