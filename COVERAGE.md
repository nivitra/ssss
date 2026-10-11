# Capture coverage

Reviewed 11 October 2026. This gallery documents authentic simulator screens, not generated mockups or a complete release certification. [The manifest](manifest.json) identifies each included image, its current or archival status, capture journey and checksum. The flow walkthroughs combine named captures in reading order; they are not uninterrupted recordings. Missing steps remain marked in the gallery.

The current captures use Kulture Edit 0.1.0 (1) on an iPhone 17 Pro simulator running iOS 26.5. Map services are real; location and navigation movement are simulated. The city-wide Explore map uses Mapbox. The new place preview and in-app navigation use Google Maps.

| Area | Included evidence | Boundary |
|---|---|---|
| Explore and places | City map, neighbourhood picker, place board, search, sourced place details, Google preview and Back | Approximate positions are not verified entrances. Conçu honestly shows an unknown-position fallback. |
| Google search and navigation | Actual chemist and café results; native route preview; explicitly simulated guidance; background/return and a system Dynamic Island | No physical-road, locked-iPhone audio, entrance-accuracy or performance claim. Full Google place details remain a capture gap below. |
| Ask and planning controls | Intent/category entry, request controls, manual café shortlist, service comparison, explicit IST start and visit-duration controls; an actual authenticated answer and follow-up | Applying controls does not send a request. The reply is scrollable, so a frame may show only part of it. A service listing is contact information, not a medical recommendation or leisure stop. |
| Saved and Plans | Saved places, explicit stop selection, draft summary, order editor and next-stop controls | The selection frame is before any choices. Progress is manual; opening directions does not record a visit. |
| Contact | Public website/phone, published hours, source dates and an enquiry checklist | Hours are not a live availability check. The enquiry is partly below the viewport; no business was called or messaged. |
| Shared ideas and account entry | Pasted-link confirmation and association with an outing; empty sign-in/registration forms; preference controls; voice consent | A confirmed pasted link is not automatic reel recognition. No microphone recording, transcription or account registration was performed for the gallery. |
| Larger text | Explore, Ask entry and the composer/keyboard at the system accessibility-medium text size | This is one accessibility size, not coverage of every text size or reduced-motion setting. |
| Archive | Earlier live planning, travel-budget, refinement, shared-outing and taste screens | Clearly labelled older layouts and historical state; not evidence that the exact current build was retested for those flows. |

## Google full-detail rendering gap

The current Google search results are visibly populated. A captured full-detail surface, however, had its wrapper and navigation controls without a visibly rendered venue title or facts. That frame was excluded. The final stricter check also failed while waiting for the selected venue title to render, despite the SDK data-ready state.

This remains unresolved capture/rendering evidence. A data-ready callback alone is insufficient. A replacement needs the actual selected venue content visibly settled, with provider attribution intact. No invented card or archival substitute is presented as the current Google detail screen.

## What the capture runs established

Screenshots and functional assertions are separate evidence. Valid earlier screenshots from a run can be included even if a later assertion failed.

| Capture run | Recorded outcome |
|---|---|
| Maps | Four tests passed, including native place preview, in-app navigation and return flows. The earlier detail check did not require a visibly rendered venue title. |
| Collection | The Saved/Plans screenshot journey passed. |
| Ask controls | Four tests passed: service separation, shortlist-to-draft, optional start time and explicit visit durations. A later capture test failed at the category-browser control. |
| Core retry | The journey captured initial screens but later failed an assertion; it is not an all-pass run. |
| Final flows | Two of five tests passed: pasted-link confirmation/planning and stay-timer persistence. Three failed: settled Google detail title, a missing Cancel control in the live-Ask journey, and a category selector. Thirteen captures were produced without capture-write errors. |
| Live Ask supplement | The authenticated answer/follow-up test passed in 58.476 seconds and produced four current-build captures. The test account was signed out afterward. |
| Larger-text supplement | The navigation/composer test passed in 17.874 seconds and produced three current-build captures at accessibility-medium. The prior large text-size setting was restored and verified. |

The earlier final-flows live-Ask attempt stopped before an answer because its screenshot-specific consent detour could not find Cancel. The later supplement removed that detour and completed the actual answer/follow-up assertions on the same unchanged app build. The Google full-detail and category-selector failures remain recorded; the later successes do not turn the earlier batch into an all-pass run. Only images listed in the manifest count as gallery coverage.

## Remaining conditional coverage

These states require their own authentic captures; their absence is not a claim that the feature is missing:

- Voice recording, transcription review and microphone/provider failure states beyond consent.
- Ask failure and recovery states, including a retained earlier answer and retry after a failed follow-up.
- Complete category-directory and no-results sequences where the gallery marks missing steps.
- Account-sync conflicts, account switching, stale taste data and recovery states.
- Published entrance/checkpoint guides, expired or offline references, and mode-specific access evidence.
- Google permission, notification and licensing variants; unknown-position branch selection after the shown fallback.
- Current shared-outing publishing, recipient import/revocation, and an external app’s share-extension flow.
- Partial travel failures, unresolved stops, unknown-duration or over-budget outcomes; additional Live Activity and accessibility variants.

Chosen start times and stays are user preferences. Route times are estimates, not opening-hours, future-traffic, reservation or live-availability verification. Static images cannot demonstrate animation smoothness. Provider attribution and visible uncertainty notices should remain intact when reusing the captures.
