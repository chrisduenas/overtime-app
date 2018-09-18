# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI
- AuditLog

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input -> integrate     with Heroku scheduler
- x Administrate admin dashboard
- x Block non admin and guest users
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI: 
- x Bootstrap -> formatting
- x Icons from Glyphicons
- x Update the styles for forms

## Approval Workflow TODOs
- status to post (database migration)
- status needs to be required
- status to have a default value
- implement approval stages
- locking 
