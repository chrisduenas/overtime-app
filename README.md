# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI

## Features:
- Approval Workflow
    - User enters a post
    - Admin User reviews post
    - Approve/ Reject Post
    - Lock records after approval
    - Sent back to user if rejected
- SMS Sending -> link to approval or overtime input
- x Administrate admin dashboard
- x Block non admin and guest users
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI: 
- x Bootstrap -> formatting
- Icons from Font Awesome
- x Update the styles for forms

## Refactor TODOs
- Refactor posts/_form for admin user with status


## Approval Workflow TODOs
- status to post (database migration)
- status needs to be required
- status to have a default value
- implement approval stages
- locking 
