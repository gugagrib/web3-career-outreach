# Site Structure

## Product idea

W3 / Ledger is a compact field guide for an international Web3 growth profile. It translates product curiosity into evidence: what was observed, why it matters for growth, and where a hiring conversation can begin.

## Page anatomy

| Order | Section | Content and interaction |
|---:|---|---|
| 1 | Persistent rail | Custom W3 mark, `W3 / Ledger` wordmark, vertical `FIELD NOTE`, availability status, and the working-mode copy. |
| 2 | Top navigation | Anchors to Tracker, Signals, Outreach Lab, and GitHub Ops. On small screens it collapses into a menu. |
| 3 | Hero | Positioning statement, short value proposition, primary field-notes CTA, and generated dossier artwork. |
| 4 | Proof strip | Three concise signals: current focus, working mode, and best-fit teams. |
| 5 | Read-only Tracker | Filters by project, displays source status and public metrics, and refreshes the Variational metadata endpoint on demand. |
| 6 | Project Signals | Four project cards for RISEx, Variational Omni, Ink Points, and Lighter. Each card includes a product lens, tags, note, and official link. |
| 7 | Outreach Lab | Tabs for Founder and Recruiter messages. The Copy button places the selected template in the clipboard. |
| 8 | GitHub Operating Note | A three-step operating model: read-only audit, careful public building, and no secrets/no shortcuts. |
| 9 | Footer | W3 / Ledger lockup, short positioning line, and contact/social links. |

## Tracker behavior

The tracker intentionally separates public-source observation from personal-account activity. RISEx is source-linked for public market signals. Variational Omni can refresh public metadata when the endpoint is reachable. Ink Points is marked as a manual-check source because program rules and personal status should be verified through the official product surface.

The tracker never requests a wallet connection, private key, browser cookie, trading credential, or API secret. A failed request produces a visible notice and leaves the last known display state intact. The dashboard is an observation aid, not an automated participation or trading system.

## Visual system

The interface follows a Swiss editorial / field-note direction. Large Space Grotesk headlines create a strong hierarchy, IBM Plex Sans carries readable body copy, and IBM Plex Mono labels metadata, statuses, and controls. Bone paper, ink black, mineral grey, and signal lime create a restrained palette in which lime marks action, proof, active state, or a numbered signal.

The layout uses an asymmetric two-column hero, offset project cards, a dark outreach lab, and recurring vertical field-note cues. Generated visual assets are used for the hero and project dossier surfaces.

## Accessibility and resilience

Interactive controls use native buttons, visible states, and descriptive labels. External links open in a new tab with `rel="noreferrer"`. Reduced-motion preferences shorten transitions. The mobile layout removes the fixed rail, keeps the navigation reachable, stacks project cards, and turns the tracker into a single-column reading flow.
