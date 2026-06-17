# Schema Plan

## Users

- id
- name
- email
- password
- role

## Leads

- id
- assigned user
- name
- email
- phone
- source
- status
- notes

## Customers

- id
- related lead
- assigned user
- name
- email
- phone
- company name
- address

## Follow Ups

- id
- related lead
- related customer
- assigned user
- follow up date
- note
- status

## Deals

- id
- related customer
- title
- value
- stage
- expected close date
- status

## Notes

- id
- related user
- related lead
- related customer
- note

## Activity Logs

- id
- related user
- action
- description
