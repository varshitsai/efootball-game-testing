# Bug Report: eFootball Matchmaking Becomes Unresponsive After App Switching

## Bug ID
EF-MOB-001

## Title
Matchmaking screen becomes unresponsive after returning from Instagram

## Product
- **Game:** eFootball
- **Platform:** iOS
- **Device:** iPhone 15 Plus
- **Feature:** Online matchmaking

## Severity
**Proposed severity: Medium — provisional**

Rationale: The issue interrupts the current matchmaking session and, according to the tester's recollection, requires restarting the game to recover. The severity has not been validated against an official severity scale or by the developer.

## Preconditions
1. eFootball is running on an iPhone 15 Plus.
2. Online matchmaking is in progress.
3. An Instagram notification is available.

## Steps to Reproduce
These steps are based on retrospective recollection and have not been independently retested.

1. Start eFootball.
2. Begin online matchmaking.
3. Open Instagram from an incoming notification.
4. Stay in Instagram for approximately 2–3 seconds.
5. Return to eFootball.
6. Attempt to interact with the matchmaking screen.

## Expected Result
The game remains responsive after returning from Instagram. Matchmaking continues normally or the player can cancel it and return to a usable state.

## Actual Result
- The matchmaking screen becomes unresponsive.
- The loading animation remains visible and continues moving.
- Waiting approximately 5–10 minutes does not resolve the issue.
- Restarting the game restores normal operation.

## Frequency
Sometimes, according to the tester's recollection. The number of attempts and failures was not recorded.

## Environment
- Device: iPhone 15 Plus
- iOS version: Not recorded
- Game version: Not recorded
- Network conditions: Connection appeared stable to the tester; no measurements or logs are available.
- Incident date: Not recorded

## Evidence
No screenshot or screen recording of the original incident is available. This report is based on the tester's recollection.

## Investigation Notes
The root cause is unknown. Potential investigation areas include app lifecycle handling, matchmaking state recovery, connectivity changes, and client/server synchronization. None has been established as the cause.

The continued movement of the loading animation does not establish that the rest of the game is functioning correctly.

## Retest Status
Not retested. Further attempts are needed to establish reproducibility and capture current environment details.

## Support Status
A KONAMI support acknowledgement exists, but the tester cannot confirm whether it concerned this issue. No confirmed investigation result or fix is available for this case.

## Tester Conclusion
This report documents an intermittent matchmaking responsiveness issue observed after briefly switching to Instagram. The game did not recover through waiting, and restarting it restored normal operation. Further testing is required to verify the behaviour and investigate its cause.
