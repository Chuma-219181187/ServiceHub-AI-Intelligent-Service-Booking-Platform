# Use Case Specifications – ServiceHub AI

## UC1: User Login

**Actor:** Customer / Provider / Admin
**Description:** Allows users to access the system securely

**Preconditions:**

* User must be registered

**Postconditions:**

* User is authenticated and granted access

**Basic Flow:**

1. User enters login credentials
2. System validates credentials
3. System grants access

**Alternative Flow:**

* Invalid credentials → error message displayed

---

## UC2: Search Services

**Actor:** Customer

**Preconditions:**

* User is logged in

**Postconditions:**

* List of services displayed

**Basic Flow:**

1. User enters search query
2. System retrieves services
3. Results displayed

**Alternative Flow:**

* No results found → system displays message

---

## UC3: Book Service

**Actor:** Customer

**Preconditions:**

* User is logged in
* Service is available

**Postconditions:**

* Booking is created

**Basic Flow:**

1. User selects service
2. User chooses date/time
3. System creates booking

**Alternative Flow:**

* Service unavailable → error message

---

## UC4: Make Payment

**Actor:** Customer

**Preconditions:**

* Booking exists

**Postconditions:**

* Payment is confirmed

**Basic Flow:**

1. User selects payment method
2. Payment processed
3. Confirmation returned

**Alternative Flow:**

* Payment failure → retry option

---

## UC5: Leave Review

**Actor:** Customer

**Preconditions:**

* Booking completed

**Postconditions:**

* Review stored

**Basic Flow:**

1. User selects booking
2. Enters rating and comment
3. System saves review

---

## UC6: Manage Services

**Actor:** Provider

**Preconditions:**

* Provider is approved

**Postconditions:**

* Service updated

**Basic Flow:**

1. Provider creates/updates service
2. System saves changes

---

## UC7: Manage Bookings

**Actor:** Provider

**Preconditions:**

* Booking exists

**Postconditions:**

* Booking status updated

**Basic Flow:**

1. Provider views booking
2. Accepts/rejects request

---

## UC8: Approve Providers

**Actor:** Admin

**Preconditions:**

* Provider registration submitted

**Postconditions:**

* Provider approved/rejected

**Basic Flow:**

1. Admin reviews provider
2. Approves or rejects
3. System updates status
