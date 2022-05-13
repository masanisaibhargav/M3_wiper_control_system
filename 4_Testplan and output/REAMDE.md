# Test plan and Output
### Test plan is created and verified
## HIGH LEVEL TEST PLAN / Integrated test plan
| Test id | Description | Input | Expected output | Actual output |
|---------|-------------|-------|-----------------|---------------|
| 01 | Engine on | user button press once | car engine should on | car engine will on |
| 02 | Engine off | user button press twice | car engine should off | car engine will off |
| 03 | wiper on | user button press three times | car wipers should on | car wipers will on |
| 04 | wiper off | user button press four times | car wipers should off | car wipers will off |

## LOW LEVEL TEST PLAN
| Test id | Description | Input | Expected Output | Actual Output | Passed/Not |
|---------|-------------|-------|-----------------|---------------|------------|
| 01 | check for engine on | user button press once | red led should on | red led will on | passed |
| 02 | check for engine off | user button press twice | red led should off | red led will off | passed |
| 03 | check for wiper on | user button press three times | blue-green-orange led's should on in clock wise manner | blue-green-orange led's will on in clock wise manner | passed |
| 04 | check for wiper off | user button press four times | orange-green-blue led's should on in anti-clock wise manner | orange-green-blue led's will on in anti-clock wise manner | passed |
