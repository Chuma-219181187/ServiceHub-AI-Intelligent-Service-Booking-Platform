# Test Cases – ServiceHub AI

| Test ID | Requirement | Description        | Steps                  | Expected Result    | Status  |
| ------- | ----------- | ------------------ | ---------------------- | ------------------ | ------- |
| TC-001  | FR1         | User registration  | Enter details → Submit | Account created    | Pending |
| TC-002  | FR2         | User login         | Enter credentials      | Login successful   | Pending |
| TC-003  | FR3         | Search services    | Enter keyword → Search | Results displayed  | Pending |
| TC-004  | FR5         | Book service       | Select service → Book  | Booking created    | Pending |
| TC-005  | FR6         | Payment processing | Enter payment details  | Payment successful | Pending |
| TC-006  | FR8         | Leave review       | Submit review          | Review saved       | Pending |
| TC-007  | FR7         | Approve provider   | Admin approves         | Provider activated | Pending |
| TC-008  | FR9         | Notifications      | Trigger booking        | Notification sent  | Pending |

---

## Non-Functional Test Cases

### Performance Test

* Simulate 1,000 users searching services
* Expected: Response time ≤ 2 seconds

### Security Test

* Attempt unauthorized login
* Expected: Access denied and logged
