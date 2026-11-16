# Module 05 — Quality Assurance Report (Case-Based Revision)

**Presentation:** `Module05_My_Brand_Interactive.html`  
**Slides:** 58  
**Status:** **PASS — responsive and interaction checks completed**

## Content and teaching-sequence checks
- [x] The fictional Maryam case appears on slide 02, immediately after the cover.
- [x] The same case facts are carried through the presentation.
- [x] The original source Summary prompt is retained verbatim.
- [x] A filled demonstration prompt is shown using Maryam's case facts.
- [x] Each of the seven CV sections has an immediate, separate output slide.
- [x] A complete text CV is shown after the seven section outputs.
- [x] A Canva-formatted CV preview is shown after the Canva design explanation.
- [x] Unknown details remain placeholders or are omitted.
- [x] No invented university, dates, contact details, employer, metrics or certification.
- [x] The minute-by-minute session map and visible session-time labels are removed.
- [x] The source ten-item peer-review checklist remains intact.

## Typography and layout
- [x] Projector body text increased from the previous 16px base to a responsive 18–23px range on desktop.
- [x] Main slide titles increased to a responsive 34–62px range on desktop.
- [x] Mobile body text uses a 17px minimum for the tested widths.
- [x] CV output panels use readable English LTR layout with Arabic explanation alongside.
- [x] The case file uses three columns on wide screens and a single column on narrow screens.

## Technical validation
- [x] HTML parsed successfully; 58 slides found.
- [x] JavaScript syntax check with Node.js — PASS.
- [x] No JavaScript page errors in tested Chromium workflows.
- [x] No duplicate slide numbering; numbering runs 01–58.
- [x] Every slide includes Study and Trainer notes.

## Responsive browser tests
| Viewport | Horizontal overflow | Slides with vertical scrolling | Navigation / modes / overview |
|---|---|---:|---|
| 1920 × 1080 | None | 3 | PASS |
| 1366 × 768 | None | 8 | PASS |
| 1280 × 720 | None | 20 | PASS |
| 1024 × 768 | None | 6 | PASS |
| 768 × 1024 | None | 3 | PASS |
| 390 × 844 | None | 42 | PASS |
| 360 × 800 | None | 49 | PASS |

Vertical scrolling is intentional on content-heavy slides, especially on phones. No horizontal overflow was detected. Students can scroll within a slide to read the full content; the design does not shrink the text to force all content into one screen.

## Interactive smoke tests
- [x] Next / previous navigation and counter.
- [x] Presentation mode.
- [x] Study mode.
- [x] Trainer mode.
- [x] Overview open / close.
- [x] Prompt Builder output.
- [x] Peer-review checklist interaction.
- [x] Quiz feedback.

## Remaining classroom checks
- Test the deck on the actual projector and browser used in class.
- Live ChatGPT, Grammarly and Canva account workflows depend on the learner's access and were not tested by this browser validation.
- Fullscreen and clipboard permissions can vary by browser context.

**Acceptance:** The revised Module 05 passes the automated responsive, navigation, mode and interaction checks. The content now follows a continuous case-based demonstration with a visible CV output after each section application.
