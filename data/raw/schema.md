# Raw Data Schema

## companies
- company_id (string)
- created_at (timestamp)
- country (string)
- plan (string)

## users
- user_id (string)
- company_id (string)
- role (admin | employee)
- created_at (timestamp)

## onboarding_events
- event_id (string)
- company_id (string)
- user_id (string)
- event_name (string)
- event_timestamp (timestamp)

## Event Definitions
- company_created
- admin_created
- team_invited
- payroll_submitted
- documents_uploaded
- first_payment
- onboarding_completed
