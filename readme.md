# GraphQL in AppSync using AWS SAM

### Introduction

Implementing GraphQL in AppSync using AWS SAM.

### Working

- It uses Dynamo DB table to query the DB
- Creating a role which allows access to DDB table.
- Uses API key for authentication purposes.
- Used inline mapping template, which takes uses DDB aws sdk like functions.
- The client can take just the required fields they want instead of fetching all the unwanted data returned in REST APIs.
- A single resolver is used here i.e., DynamoDB.
