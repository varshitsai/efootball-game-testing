# eFootball Game Testing Case Study

## Exploratory Testing: Matchmaking Becomes Unresponsive After Switching Apps

A mobile game-testing case study documenting an intermittent matchmaking responsiveness issue observed while playing eFootball on an iPhone.

## Project Overview

- **Game:** eFootball
- **Platform:** iOS
- **Device:** iPhone 15 Plus
- **Testing type:** Exploratory testing
- **Feature:** Online matchmaking
- **Case status:** Original issue documented retrospectively; recent retest results recorded

## Issue Summary

During online matchmaking, I opened Instagram from an incoming notification and returned to eFootball approximately 2–3 seconds later.

After returning, the matchmaking screen became unresponsive. The loading animation continued moving, but I could not interact with the game normally. Waiting approximately 5–10 minutes did not resolve the issue. Restarting the game restored normal operation.

The issue occurred sometimes, according to my recollection.

## Expected Behaviour

The game should remain responsive when returning from another app. Matchmaking should continue normally or provide a working way to cancel and recover.

## Actual Behaviour

- The matchmaking screen became unresponsive after returning from Instagram.
- The loading animation remained visible and continued moving.
- Waiting approximately 5–10 minutes did not resolve the issue.
- Restarting the game restored normal operation.

## Original Testing Limitations

The original report is based on recollection. The exact game version, iOS version, incident date, and network measurements were not recorded. No screenshot or screen recording of the original incident is available.

The network appeared stable to me at the time, but this does not rule out connectivity problems. The underlying cause has not been established.

## Recent Retest Results

After the original incidents, I tested switching to Instagram and returning to eFootball during matchmaking approximately 5–10 times. The original freeze was not reproduced in these recent attempts.

- **Result:** Issue not reproduced in recent attempts
- **Game update:** eFootball was updated after the original incidents
- **Exact attempt count and test dates:** Not recorded
- **iOS and game versions:** Not recorded
- **Root cause or confirmed fix:** Unknown

These results do not prove that the issue is permanently fixed. The game update may be relevant, but a causal relationship has not been established.

## Further Testing Plan

1. If the original issue recurs, record the exact steps, date, iOS version, and game version.
2. Capture a screen recording or screenshots if possible.
3. Test switching to another app separately from switching to Instagram.
4. Compare results with matchmaking while keeping eFootball in the foreground.
5. Record each attempt and its outcome.
6. If the freeze recurs, document whether waiting or cancelling matchmaking recovers the game, and whether restarting is required.

## Support Contact

I received a KONAMI customer-support acknowledgement, but I cannot confirm whether it concerned this specific issue. No confirmed investigation result or fix is available for this case.

## Skills Demonstrated

- Exploratory testing
- Mobile application testing
- Writing expected and actual results
- Documenting test scenarios and outcomes
- Recording retest results
- Identifying evidence gaps
- Separating observed behaviour from possible root causes

## Disclaimer

This is an independent testing case study based on personal gameplay observations. It is not an official KONAMI report, and no affiliation with or endorsement by KONAMI is implied.

## Project Files

- [**Detailed Bug Report — EF-MOB-001**](bug-report.md): Structured report with reproduction steps, expected and actual results, severity rationale, environment details, retest status, and testing limitations.
- [**Test Execution Log**](test-execution-log.md): Records the recent retest scenario, results, and testing limitations.

## Project Status

- [x] Documented the originally observed issue and expected behaviour
- [x] Created a structured bug report
- [x] Recorded recent retest results
- [ ] Capture evidence if the issue occurs again
- [ ] Record exact software versions and test dates in a future test session

**Note:** The original incident is documented retrospectively from personal recollection. Recent attempts did not reproduce it; the root cause and any permanent fix remain unconfirmed.
