# Workday Tracking System (workday-tracking-system)

APIs for managing employee time tracking, absence management, and workforce scheduling in the Workday platform. Covers time blocks, time clock events, timesheets, time off, leaves of absence, accruals, schedule shifts, scheduling organizations, labor demand, and worker scheduling preferences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/apis.yml)

## Tags

- Absence Management
- Attendance
- Enterprise
- HCM
- Human Capital Management
- Payroll
- Scheduling
- Time Tracking
- Timesheets
- Workforce Management

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Workday Time Tracking API

Manage employee time entries, time blocks, time clock events, work schedule assignments, and time requests within the Workday platform. Supports both individual and batch operations for enterprise workforce management.

- **Human URL:** [https://www.workday.com/en-us/products/human-capital-management/time-tracking.html](https://www.workday.com/en-us/products/human-capital-management/time-tracking.html)
- **Base URL:** `https://{tenant}.workday.com/api/time-tracking/v1`

#### Tags

- Time Tracking
- Timesheets
- Time Blocks
- Time Clock
- Work Schedules
- Time Requests
- Hours
- Attendance

#### Properties

- [Documentation](https://docs.workday.com/api/time-tracking)
- [API Reference](https://developer.workday.com/api-reference/time-tracking)
- [Authentication](https://docs.workday.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-time-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-shift-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-block-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-blocks-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-clock-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-clock-event-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-clock-events-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-request-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-time-requests-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-timesheet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-timesheets-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-work-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/time-tracking-work-schedule-assignment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-shift-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-block-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-block-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-blocks-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-clock-event-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-clock-event-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-clock-events-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-request-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-request-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-time-requests-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-timesheet-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-timesheets-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-work-schedule-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/time-tracking-work-schedule-assignment-structure.json)
- [Postman Collection](collections/workday-tracking-system-absence-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-absence-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-tracking-system-scheduling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-scheduling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-tracking-system-time-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-time-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Absence Management API

Track employee attendance, absences, leave requests, and time off balances in the Workday platform. Supports entering time off, requesting leave of absence, managing accrual balances, and processing return-from-leave events.

- **Human URL:** [https://www.workday.com/en-us/products/human-capital-management/absence-management.html](https://www.workday.com/en-us/products/human-capital-management/absence-management.html)
- **Base URL:** `https://{tenant}.workday.com/api/absence-management/v1`

#### Tags

- Absence Management
- Time Off
- Leave of Absence
- Accruals
- Balances
- Attendance

#### Properties

- [Documentation](https://docs.workday.com/api/absence-management)
- [API Reference](https://developer.workday.com/api-reference/absence-management)
- [Authentication](https://docs.workday.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-absence-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-accrual-override-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-accrual-override-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-accrual-overrides-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-leave-of-absence-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-leave-of-absence-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-leaves-of-absence-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-return-from-leave-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-balance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-balances-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/absence-management-time-off-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-accrual-override-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-accrual-override-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-accrual-overrides-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-leave-of-absence-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-leave-of-absence-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-leaves-of-absence-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-return-from-leave-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-balance-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-balances-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-entry-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/absence-management-time-off-response-structure.json)
- [Postman Collection](collections/workday-tracking-system-absence-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-absence-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-tracking-system-scheduling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-scheduling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-tracking-system-time-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-time-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Scheduling API

Create and manage employee work schedules, shifts, scheduling organizations, and labor demand within the Workday platform. Supports importing schedule data, managing shift assignments, and configuring scheduling settings and worker scheduling preferences.

- **Human URL:** [https://www.workday.com/en-us/products/human-capital-management/scheduling.html](https://www.workday.com/en-us/products/human-capital-management/scheduling.html)
- **Base URL:** `https://{tenant}.workday.com/api/scheduling/v1`

#### Tags

- Scheduling
- Schedules
- Shifts
- Scheduling Organizations
- Labor Demand
- Worker Preferences
- Workforce Management

#### Properties

- [Documentation](https://docs.workday.com/api/scheduling)
- [API Reference](https://developer.workday.com/api-reference/scheduling)
- [Authentication](https://docs.workday.com/authentication)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/openapi/workday-tracking-system-scheduling-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-labor-demand-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-labor-demand-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-labor-demand-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-schedule-shift-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-schedule-shift-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-schedule-shifts-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-scheduling-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-scheduling-organization-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-scheduling-organizations-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-worker-scheduling-preferences-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/scheduling-worker-scheduling-preferences-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-labor-demand-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-labor-demand-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-labor-demand-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-schedule-shift-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-schedule-shift-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-schedule-shifts-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-scheduling-organization-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-scheduling-organization-input-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-scheduling-organizations-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-worker-scheduling-preferences-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/scheduling-worker-scheduling-preferences-input-structure.json)
- [Postman Collection](collections/workday-tracking-system-absence-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-absence-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-tracking-system-scheduling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-scheduling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-tracking-system-time-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-tracking-system-time-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.workday.com)
- [Getting Started](https://developer.workday.com/getting-started)
- [Documentation](https://docs.workday.com)
- [Authentication](https://docs.workday.com/authentication/oauth2)
- [Sign Up](https://www.workday.com/en-us/forms/contact-sales.html)
- [Pricing](https://www.workday.com/en-us/pricing.html)
- [Rate Limits](https://docs.workday.com/rate-limits)
- [Status Page](https://status.workday.com)
- [Support](https://www.workday.com/en-us/company/latest/customer-support.html)
- [Community](https://community.workday.com)
- [Blog](https://blog.workday.com)
- [Release Notes](https://docs.workday.com/release-notes)
- [Terms of Service](https://www.workday.com/en-us/terms-of-service.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [GitHub Organization](https://github.com/Workday)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-ld/workday-tracking-system-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-leave-of-absence-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-time-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-schema/workday-tracking-system-timesheet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-leave-of-absence-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-time-block-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/json-structure/workday-tracking-system-timesheet-structure.json)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/workday-tracking-system/refs/heads/main/rules/workday-tracking-system-spectral-rules.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
