# eFootball Game Testing Case Study

## Exploratory Testing: Matchmaking Becomes Unresponsive After Switching Apps

A mobile game-testing case study documenting an intermittent matchmaking responsiveness issue observed while playing eFootball on an iPhone.

## Project Overview

- **Game:** eFootball
- **Platform:** iOS
- **Device:** iPhone 15 Plus
- **Testing type:** Exploratory testing
- **Feature:** Online matchmaking
- **Case status:** Retrospective documentation based on personal observation

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

## Testing Limitations

The report is based on recollection. The exact game version, iOS version, incident date, and network measurements were not recorded. No screenshot or screen recording of the incident is available.

The network appeared stable to me at the time, but this does not rule out connectivity problems. The underlying cause has not been established.

## Further Testing Plan

1. Repeat the same steps with Instagram and record the outcome.
2. Compare the result with switching to a different app.
3. Run a control test without leaving eFootball.
4. Test different background durations.
5. Check whether the matchmaking cancel control responds.
6. Record the device OS version, game version, and evidence for each attempt.

## Support Contact

I received a KONAMI customer-support acknowledgement, but I cannot confirm whether it concerned this specific issue. No confirmed investigation result or fix is available for this case.

## Skills Demonstrated

- Exploratory testing
- Mobile application testing
- Writing expected and actual results
- Documenting reproducible test steps
- Identifying evidence gaps
- Separating observed behaviour from possible root causes

## Disclaimer

This is an independent testing case study based on personal gameplay observations. It is not an official KONAMI report, and no affiliation with or endorsement by KONAMI is implied.
