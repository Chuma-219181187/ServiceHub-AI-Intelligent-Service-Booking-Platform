# Product Backlog – ServiceHub AI

| Story ID | User Story           | Priority (MoSCoW) | Effort (Points) | Dependencies   |
| -------- | -------------------- | ----------------- | --------------- | -------------- |
| US-001   | Register account     | Must-have         | 2               | None           |
| US-002   | Login                | Must-have         | 2               | US-001         |
| US-003   | Search services      | Must-have         | 3               | None           |
| US-004   | View service details | Must-have         | 2               | US-003         |
| US-005   | Book service         | Must-have         | 5               | US-002, US-003 |
| US-006   | Make payment         | Must-have         | 5               | US-005         |
| US-008   | Manage services      | Should-have       | 3               | US-002         |
| US-009   | Manage bookings      | Should-have       | 3               | US-005         |
| US-010   | Approve providers    | Should-have       | 2               | None           |
| US-007   | Leave review         | Could-have        | 2               | US-005         |
| US-011   | Send notifications   | Could-have        | 3               | US-005         |
| US-012   | AI recommendations   | Won’t-have (MVP)  | 5               | US-003         |

---

## Prioritization Justification

Must-have features focus on core platform functionality such as registration, login, service discovery, booking, and payment. These directly support stakeholder needs for usability and system functionality.

Should-have features enhance system management for providers and administrators.

Could-have features improve user experience but are not critical for the initial release.

The AI recommendation system is classified as a Won’t-have for the MVP due to its complexity and dependency on user data.
