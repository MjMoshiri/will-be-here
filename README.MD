# Will Be Here
## Introduction

`Will Be Here` is a web service that allows users to create, manage, and share digital wills. Users can set activation modes, enabling designated beneficiaries to access their wills under predefined conditions, such as after a specified period without cancellation by the user.

## High Level Overview (Subject to change)

## Api Endpoints

| Method | Endpoint                            | Description                                          |
|--------|-------------------------------------|------------------------------------------------------|
| POST   | /api/register                       | Register a new user.                                 |
| POST   | /api/will                           | Create a new will (encrypted)       |
| POST   | /api/will/access                    | Request access to a will (for a beneficiary).              |
| POST   | /api/will/cancel                    | Cancel a will access request (by the owner or trusted person).       |


## Stack Overview 
1. Django 
2. PostgreSQL


