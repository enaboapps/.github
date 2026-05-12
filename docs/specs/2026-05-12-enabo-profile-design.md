# EnabO GitHub Profile — Design Spec

## Context

The `enaboapps` GitHub user had no profile README before this work. With Switchify being open-sourced, the absence became visible to anyone landing on `github.com/enaboapps` from the Switchify repo. This document captures the strategic decisions that produced the profile README in `profile/README.md` of this repo.

## Strategic decisions taken during brainstorming

1. **Audience**: End users and caregivers, with secondary value for press / partnership inquiries. Not a developer audience.
2. **Identity**: EnabO is an accessibility studio. Single foreground theme.
3. **Timberlogs treatment**: Hidden. Will spin out as its own GitHub org (separate work).
4. **Featured products**: Switchify, SayIt!, Podium — all actively developed at time of writing.
5. **Archived products**: SayIt! iOS, SwitchAccessKit, augy-ios — single-line footer.
6. **Voice**: First-person under the EnabO brand. The 2016 origin acts as a credibility hook for the caregiver audience.
7. **Switchify open-source claim**: Deferred at time of writing because the Switchify repo was still private. One-line update when it flips public.
8. **Social / sponsor links**: Omitted because no live social presence currently exists for EnabO.

## Approved content

See `profile/README.md` in this repo for the live profile content. That file is the authoritative source; the design above describes the decisions that produced it.

## Out of scope (deliberately deferred)

- **Switchify open-source flip line**: One-line README update on the EnabO profile after the Switchify repo flips public.
- **Podium custom domain**: Replace the `podium-web-tan.vercel.app` autoname before real traffic arrives.
- **Timberlogs spin-out**: Separate GitHub org + repo migration + untangling Switchify's `timberlogs.apiKey` dependency.
- **Brand notice for Switchify**: SayIt! has a brand-reservation clause alongside its AGPL; consider the equivalent for Switchify.

## Success criteria

- `https://github.com/enaboapps` renders the README without markdown errors.
- A caregiver landing there can identify within ~30 seconds which of the three apps fits their need and click through.
- No mention of Timberlogs anywhere on the profile.
- No claims (open-source status, social presence, partnerships) that aren't currently true.
