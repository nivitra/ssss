# Kulture Edit — flow guide

Open the [interactive gallery](index.html#flows) to click through these steps. A flow can combine captured screens from separate runs; it is not a video or blanket acceptance certificate.

## Explore → choose → inspect

Browse or search, open a place, inspect the source information and return with context intact.

1. [Explore · city map](images/atlas-01-explore-map-home.png) — The live Mapbox discovery map with sourced place clusters and the place shelf.
2. [Choose a neighbourhood](images/atlas-02-choose-neighbourhood.png) — Switch between Hyderabad, Jubilee Hills and Kokapet.
3. [Explore · place board](images/atlas-03-explore-place-board.png) — Browse the maintained catalogue in a visual board.
4. [Search · Kbr National Park](images/atlas-22-search-kbr-national-park.png) — Actual search results before opening the named catalogue place.
5. [Kbr National Park](images/atlas-23-place-kbr-national-park.png) — The actual place page, including sourced media or the honest artwork/map fallback.
6. [Back keeps your search](images/flow-04-search-preserved-after-swipe-back.png) — An edge-swipe return retains the search and bottom navigation.

## A place → Google map → route review

Google place preview, route review and Back, illustrated with separate captured venue journeys. The city-wide Explore canvas remains Mapbox.

1. [Club Rogue · Google map preview](images/place-01-google-preview-club-rogue.png) — The new styled Google place preview with a clearly approximate source position.
2. [Place → in-app directions](images/flow-03-direct-google-navigation.png) — Direct transition to the native Google route surface.
3. [Navigation · route ready](images/google-ask-05-actual-navigation-sdk-response.png) — A real provider route from stationary simulated Hyderabad GPS. This is not a real-road test.
4. [Return to the same place](images/place-02-google-preview-after-back.png) — The rendered preview after route review and native Back.

## A category → broader Google results

Category handoff, deliberate manual search, provider details and Back. An uncaptured detail stays marked as a gap.

1. [Ask · category entry](images/google-ask-01-category-grid.png) — The initial intent and category choices.
2. [Find a category](images/google-ask-02-searchable-sector-directory.png) — Search the category browser for Chemists.
3. [Google · chemists](images/google-ask-02b-chemists-direct-search.png) — An explicit category handoff returned actual Google Places results.
4. [Google · cafés](images/google-ask-03-actual-places-sdk-response.png) — Actual Google Places results for a submitted Jubilee Hills café search.
5. **Not captured:** google-ask-07-actual-place-details.
6. [Back to your Google results](images/google-ask-08-search-preserved-after-back.png) — The search query is retained after returning from details and navigation.

## Preview → start simulation → background → return

Captured with the actual Navigation SDK and simulated location. No real road or arrival accuracy is implied.

1. [Navigation · route ready](images/google-ask-05-actual-navigation-sdk-response.png) — A real provider route from stationary simulated Hyderabad GPS. This is not a real-road test.
2. [Navigation · simulated guidance](images/google-ask-06-simulated-guidance.png) — Explicit Google SDK simulation, with the simulation label preserved.
3. [Navigation · Dynamic Island](images/google-navigation-background-island.png) — The actual system Island while simulated guidance continues. The simulator Home Screen includes the test-runner icon.
4. [Guidance after returning](images/google-ask-09-guidance-after-background.png) — The same started simulated navigation session after backgrounding the app.

## Ask → categories → useful choices

Starting choices, request context, all categories, focused results and an honest empty state.

1. [Ask · starting choices](images/atlas-12-ask-starting-choices.png) — Start with an intent, a suggestion, a category, typing or voice.
2. [Shape your request](images/atlas-13-ask-request-controls.png) — Area, intent and other request controls.
3. [Discovery categories](images/atlas-18-all-discovery-sectors.png) — The searchable category browser.
4. [More categories](images/atlas-19-more-discovery-sectors.png) — Another part of the same category browser, reached by scrolling.
5. **Not captured:** atlas-20-cafe-directory.
6. **Not captured:** atlas-21-no-results-and-search-further.

## Type → live answer → refine

The typed-request and live-answer journey. Uncaptured response steps remain marked; credentials and identifying account content are excluded.

1. [Type your intent](images/atlas-15-type-a-request.png) — An editable request with the keyboard visible.
2. [Sending a live request](images/ask-live-01-request-in-progress.png) — The app state immediately after sending to the deployed AI service.
3. [A live Ask answer](images/ask-live-02-completed-answer.png) — An actual completed provider answer tied to sourced catalogue places.
4. [Refine the shortlist](images/ask-05-live-source-bound-answer.png) — A live answer with an explicitly selected place for comparison.
5. [Continue the conversation](images/ask-06-live-follow-up.png) — An actual follow-up response retaining the request context.

## Voice input → account gate → consent

The screenshots stop at consent. No microphone recording or fabricated transcription was used.

1. [Voice · sign-in gate](images/atlas-14-voice-requires-sign-in.png) — Voice input requires an authenticated Kulture account.
2. [Sign in](images/atlas-07-sign-in.png) — The empty sign-in form. No account credentials are included.
3. [Voice transcription consent](images/voice-01-transcription-consent.png) — Actual consent prompt after sign-in. No microphone recording or speech transcription was performed for this gallery.

## Activities → preferences → time budget

Prepare an editable outing request before sending it.

1. [Choose activities](images/atlas-16-plan-activities.png) — Plan an outing with ordered activities and optional timing.
2. [Company, budget and pace](images/atlas-17-plan-company-budget-and-pace.png) — Refine the outing brief before sending it.
3. [Explicit IST selection](images/visit-time-01-explicit-ist-selection.png) — A planning control state reached through the actual editor. Applying controls prepares the request; it does not send it.
4. [Explicit visit choices](images/time-budget-01-explicit-visit-choices.png) — A planning control state reached through the actual editor. Applying controls prepares the request; it does not send it.
5. [Applied without sending](images/time-budget-02-applied-without-sending.png) — A planning control state reached through the actual editor. Applying controls prepares the request; it does not send it.

## Compare → one draft → reopen

Real café shortlist and an automatically expanded saved draft. Service comparison is a separate contact-oriented path.

1. [Start discovering](images/ask-01-intent-led-start.png) — Intent-led starting screen before a manual shortlist.
2. [Compare your choices](images/ask-02-compare-sourced-shortlist.png) — A manually chosen café shortlist using real catalogue records.
3. [Shortlist → saved draft](images/ask-03-shortlist-to-draft.png) — One explicit action turns the selected places into an expanded draft plan.
4. [Compare a service](images/ask-04-service-comparison.png) — A hospital choice remains a service to contact, rather than a leisure outing stop.

## Place → save → choose stops → edit plan

Local saves and plans created through the UI on a separate simulator; account sync remains off.

1. [Concu Jubilee Hills](images/atlas-23-place-concu-jubilee-hills.png) — The actual place page, including sourced media or the honest artwork/map fallback.
2. [Your saved places](images/atlas-26-saved-places.png) — Places saved through the actual detail screen on this device.
3. [Choose your stops](images/atlas-27-choose-and-order-plan-stops.png) — The selection screen before any stops are chosen (0/8 selected). Choose and order stops here.
4. [A saved outing](images/atlas-28-saved-plan.png) — The summary of a local plan made from selected places. Its stop list continues below this frame.
5. [Edit an outing](images/atlas-29-edit-plan-stops.png) — Adjust the stored plan through its normal editor.

## Begin an outing → next stop → stay timer

Progress and timers are explicit. A timer never records a visit automatically.

1. [Ready to go](images/atlas-30-start-an-outing.png) — The outing progress screen before beginning.
2. [The next stop](images/atlas-31-outing-next-stop.png) — The next-stop state before starting a visit or stay timer. Opening directions does not mark a visit.
3. [A 15-minute stay](images/stay-01-explicit-fifteen-minute-timer.png) — A stay timer started explicitly by the user.
4. [Stay timer · Dynamic Island](images/stay-03-actual-system-dynamic-island.png) — A real system Live Activity on the simulator, not an illustration.
5. [A timer that continues](images/stay-02-same-timer-after-back.png) — Reopening the outing reconnects to the existing timer.
6. [End a stay timer](images/stay-04-timer-ended-with-progress-unchanged.png) — Ending the timer does not silently mark a place visited.

## Place → contact facts → enquiry

Check source-listed contact details and prepare an enquiry. This journey does not call or message the business.

1. [Concu Jubilee Hills](images/atlas-23-place-concu-jubilee-hills.png) — The actual place page, including sourced media or the honest artwork/map fallback.
2. [Contacts and published hours](images/atlas-24-sourced-contact-and-hours.png) — Sourced public contact facts for Conçu. Published hours are not a live availability check.
3. [Prepare an enquiry](images/atlas-25-prepare-an-enquiry.png) — The checklist and beginning of an editable enquiry. The full message extends below this frame; nothing was sent.

## A shared idea → confirm its place → plan

Current captures use a pasted website link. The external Instagram share host and reel parsing are not verified here.

1. [Shared links · starting state](images/atlas-10-shared-links-inbox-start.png) — The device-local inbox for external ideas.
2. [Confirm the place in a link](images/editorial-17-shared-link-confirmation.png) — A pasted website link and note await explicit place confirmation; no reel video was analyzed.
3. [A discovery becomes a plan](images/editorial-18-shared-link-plan.png) — A confirmed shared idea is associated with a local outing.

## Connection → sign in / register → taste

Independent account and preference screens. No account was created for this capture.

1. [Your Kulture](images/atlas-06-account-and-connection.png) — Connection information and account entry.
2. [Sign in](images/atlas-07-sign-in.png) — The empty sign-in form. No account credentials are included.
3. [Create an account](images/atlas-08-create-account.png) — Registration form only; no account was created for this capture.
4. [Your kind of city](images/atlas-04-taste-interests.png) — Choose explicit interests for discovery.
5. [Pace and preferences](images/atlas-05-taste-pace-and-preferences.png) — Preferences and Live Activity controls in the actual app.

## Larger text → Explore → Ask → compose

The same app at a system accessibility text size.

1. [Explore · larger text](images/editorial-07-large-type-explore.png) — The actual simulator accessibility text size, not enlarged pixels.
2. [Ask · larger text](images/ask-start-05-large-type-entry.png) — The Ask entry at accessibility-medium text size.
3. [Compose · larger text](images/editorial-08-large-type-ask-keyboard.png) — Keyboard and primary Ask actions at accessibility-medium text size.

## Earlier planning and refinement

Visually reviewed screenshots from an earlier October 10 build. Layouts differ; see each image’s provenance.

1. [An outing with chosen visit times](images/archive-01-an-outing-with-chosen-visit-times.png) — A real two-stage Ask result with 75 minutes of chosen stays and an explicit IST start. The screen distinguishes a straight-line comparison from checked travel. Only the first stage heading is in view; use alongside the complete time-and-travel capture.
2. [Check whether the outing fits](images/archive-02-check-whether-the-outing-fits.png) — The completed live test shows 75 minutes of stays plus a current Mapbox route estimate: about 92 minutes total, with a projected IST timeline for Chill Out Cafe and KBR National Park. Historical sheet presentation; the underlying Plans title overlaps the status bar. This known layout issue was fixed later. Travel is a current estimate, not opening-hours or future-traffic verification.
3. [Keep the park, change the café](images/archive-03-keep-the-park-change-the-caf.png) — The outing editor keeps KBR National Park pinned while allowing another café choice. Older editor copy and modal presentation. Lower optional controls continue below the frame.
4. [A new café in the same plan](images/archive-04-a-new-caf-in-the-same-plan.png) — The successful refinement returns Zoca Cafe for the café stage. The preceding editor capture and passed test establish that the other stop was kept. Only the café stage is visible; the park being kept is evidenced by the paired editor image and acceptance test, not both names in this frame.

## Earlier shared discovery to Ask

Visually reviewed screenshots from an earlier October 10 build. Layouts differ; see each image’s provenance.

1. [Bring a saved idea into Ask](images/archive-05-bring-a-saved-idea-into-ask.png) — A manually confirmed KBR National Park is carried into an editable Ask draft. The saved note is excluded unless explicitly added. Older Ask header and layout. This is a confirmed link handoff, not automatic reel recognition.
2. [Build around the place you chose](images/archive-06-build-around-the-place-you-chose.png) — The live response keeps KBR National Park as the pinned first stop in a parks-to-cafés outing, while honestly showing incomplete position coverage. Café details extend below the frame. This image shows the generated draft; local saving and association are proved by the linked passed test, not visually shown here.

## Earlier sharing and taste

Visually reviewed screenshots from an earlier October 10 build. Layouts differ; see each image’s provenance.

1. [Review exactly what you share](images/archive-07-review-exactly-what-you-share.png) — A review lists KBR National Park and Salar Jung Museum in order, with an explicit Create share link action and a clear boundary excluding private notes and preferences. Older modal presentation and pre-fix Plans header behind the sheet. No share URL, owner identity, or account details are visible.
2. [Make a shared outing your own](images/archive-08-make-a-shared-outing-your-own.png) — The recipient preview shows the ordered stops and Save a copy to Plans. The link expiry is historical; the test later revoked this share. An archival recipient preview, not a promise that the old link remains available. No capability URL or account identity is visible.
3. [Keep track of what you like](images/archive-09-keep-track-of-what-you-like.png) — The Liked list contains the deliberately liked Conçu branch, with Undo and an explanation that taste choices do not alter saved places or plans. Older sheet presentation. This is a private QA-account choice without identifying account information.
4. [Manage hidden suggestions](images/archive-10-manage-hidden-suggestions.png) — After relaunch, the Hidden list retains the Conçu choice and offers Undo. This pairs with the liked state to show the distinct preference states. Visually similar to the liked list but a different persisted state; use as an alternate or before-and-after pair, rather than adjacent duplicate decoration.
