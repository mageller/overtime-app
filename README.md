# Overtime App

## Key requirement: company needs documentationthat salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- Administrate admin dashboard
- Email summary to manager for approval
- Needs to be documented if employee did not log overtime

## UI:
- Bootstrap -> formatting

## Refactor TODOS:
- Refactor user association integration test in post_spec


## Starting PostgreSQL
```
sudo service postgresql start
```

## Starting Rails Server
```
rails s -b $IP -p $PORT
```
