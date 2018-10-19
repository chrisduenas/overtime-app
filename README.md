# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI
- x AuditLog
q
## Features:
- x Approval Workflow
- x SMS Sending -> link to approval or overtime input -> integrate     with Heroku scheduler
- x Administrate admin dashboard
- x Block non admin and guest users
- x Email summary to managers for approval
- x Needs to be documented if employee did not log overtime
- x Create audit log for each text message
- x Need to update end_date when confirmed
- x Need to update audit log status when an overtime item has been rejected
- x Update buttons on employee homepage so they show on mobile
- x Update buttons to include timespan
- x Update button sort order on employee page
- x Remove unnecessary buttons for managers (Audit log & Request Overtime)
- x Fix admin dashboard bug *administrate
- Implement rollbar for error reporting
- Implement new relic for keeping site alive




