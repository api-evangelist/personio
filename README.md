# Personio (personio)

Personio is a European HR management and recruiting platform serving small and mid-sized businesses with a unified HRIS covering employee records, absence management, time tracking, payroll preparation, performance, and applicant tracking. The platform is headquartered in Munich and is widely adopted across Germany, Austria, Switzerland, the UK, the Netherlands, and Spain. Personio exposes a Public API at api.personio.de that supports Bearer token authentication via Client ID/Secret (v1 token endpoint and v2 OAuth 2.0 client credentials flow), with webhooks now available for Person entity events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/personio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/personio/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Human Resources
- HRIS
- Recruiting
- Applicant Tracking
- Absence Management
- Time Tracking
- Europe HR

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Personio Public API v1

REST API for managing employees, attendances, absences, projects, and recruiting data in Personio. Authentication uses a Client ID/Secret exchanged for a short-lived Bearer token via POST /v1/auth.

- **Human URL:** [https://developer.personio.de/reference/authentication](https://developer.personio.de/reference/authentication)
- **Base URL:** `https://api.personio.de/v1`

#### Tags

- HRIS
- Employees
- Absences
- Attendances
- Recruiting

#### Properties

- [Documentation](https://developer.personio.de/)
- [Authentication](https://developer.personio.de/reference/authentication)
- [Getting Started](https://developer.personio.de/docs/getting-started-with-the-personio-api)
- [OpenAPI](https://raw.githubusercontent.com/personio/api-docs/master/personio-auth-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/personio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/personio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Personio Public API v2

Next-generation REST API with OAuth 2.0 Client Credentials Grant authentication. Token endpoint POST /v2/auth/token returns access tokens used as Bearer credentials on subsequent calls.

- **Human URL:** [https://developer.personio.de/reference/post_v2-auth-token](https://developer.personio.de/reference/post_v2-auth-token)
- **Base URL:** `https://api.personio.de/v2`

#### Tags

- HRIS
- OAuth 2.0
- Employees

#### Properties

- [Documentation](https://developer.personio.de/reference/post_v2-auth-token)
- [Git Hub](https://github.com/personio/api-docs)
- [Postman Collection](collections/personio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/personio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/personio)
- [Website](https://www.personio.com)
- [Documentation](https://developer.personio.de/)
- [Pricing](https://www.personio.com/pricing/)
- [Sign Up](https://www.personio.com/contact/)
- [GitHub Organization](https://github.com/personio)
- [L L Ms Txt](https://developer.personio.de/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
