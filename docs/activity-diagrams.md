# Activity Diagrams – ServiceHub AI

This document presents the activity diagrams representing key workflows of the ServiceHub AI system.

# Activity Diagram – User Registration

```mermaid
flowchart TD

Start([Start])

A[Enter user details]
B[Validate input]

C{Is data valid?}

D[Create account]
E[Send verification email]

F[Show error message]

End([End])

Start --> A --> B --> C
C -->|Yes| D --> E --> End
C -->|No| F --> End
```

## Explanation

This diagram represents the user registration process. The system validates user input before creating an account. If validation fails, an error is shown.

### Traceability

Functional Requirements:

* FR1 – User Registration

User Stories:

* US-001: User Registration
========================================================================================

# Activity Diagram – User Login

```mermaid
flowchart TD

Start([Start])

A[Enter username and password]
B[Validate credentials]

C{Are credentials valid?}

D[Grant access]
E[Display dashboard]

F[Show login error]

End([End])

Start --> A --> B --> C
C -->|Yes| D --> E --> End
C -->|No| F --> End
```

## Explanation

The login workflow verifies user credentials before granting access to the system dashboard.

### Traceability

Functional Requirements:

* FR2 – User Authentication

User Stories:

* US-002: User Login
========================================================================================

# Activity Diagram – Search Services

```mermaid
flowchart TD

Start([Start])

A[Enter search query]
B[Fetch services]

C{Results found?}

D[Display results]
E[Apply filters/sort]

F[Show no results]

End([End])

Start --> A --> B --> C
C -->|Yes| D --> E --> End
C -->|No| F --> End
```

## Explanation

Users search for services and receive filtered results. If no services are found, the system displays an appropriate message.

### Traceability

Functional Requirements:

* FR3 – Service Search

User Stories:

* US-003: Search Services
========================================================================================

# Activity Diagram – View Service Details

```mermaid
flowchart TD

Start([Start])

A[Select service]
B[Fetch service details]
C[Display service information]

End([End])

Start --> A --> B --> C --> End
```

## Explanation

This workflow shows how users view detailed information about a selected service.

### Traceability

Functional Requirements:

* FR4 – Service Listing

User Stories:

* US-004: View Service Details
========================================================================================

# Activity Diagram – Book Service

```mermaid
flowchart TD

Start([Start])

A[Select service]
B[Choose date & time]
C[Submit booking request]

D{Is service available?}

E[Create booking]
F[Redirect to payment]

G[Confirm booking]
H[Send notification]

X[Show error message]

End([End])

Start --> A --> B --> C --> D
D -->|Yes| E --> F --> G --> H --> End
D -->|No| X --> End
```

## Explanation

This diagram illustrates the booking workflow, including availability checks and confirmation.

### Traceability

Functional Requirements:

* FR5 – Booking Management
* FR6 – Payment Processing

User Stories:

* US-005: Book Service
========================================================================================

# Activity Diagram – Make Payment

```mermaid
flowchart TD

Start([Start])

A[Enter payment details]
B[Process payment]

C{Payment successful?}

D[Confirm payment]
E[Update booking]

F[Show failure message]

End([End])

Start --> A --> B --> C
C -->|Yes| D --> E --> End
C -->|No| F --> End
```

## Explanation

This workflow handles payment processing and updates the booking status accordingly.

### Traceability

Functional Requirements:

* FR6 – Payment Processing

User Stories:

* US-006: Make Payment
========================================================================================

# Activity Diagram – Leave Review

```mermaid
flowchart TD

Start([Start])

A[Open completed booking]
B[Enter rating & comment]
C[Submit review]

D{Valid input?}

E[Save review]
F[Display confirmation]

G[Show error]

End([End])

Start --> A --> B --> C --> D
D -->|Yes| E --> F --> End
D -->|No| G --> End
```

## Explanation

Users provide feedback after service completion. Validation ensures meaningful reviews.

### Traceability

Functional Requirements:

* FR8 – Review System

User Stories:

* US-007: Leave Review
========================================================================================

# Activity Diagram – Approve Provider

```mermaid
flowchart TD

Start([Start])

A[View provider application]
B[Review documents]

C{Approve provider?}

D[Approve provider]
E[Activate account]

F[Reject application]

End([End])

Start --> A --> B --> C
C -->|Yes| D --> E --> End
C -->|No| F --> End
```

## Explanation

Admins evaluate provider applications and decide whether to approve or reject them.

### Traceability

Functional Requirements:

* FR7 – Provider Approval

User Stories:

* US-010: Approve Providers
========================================================================================

