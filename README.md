# api-testing-postman
API testing portfolio using Postman with JavaScript test assertions.
# API Testing with Postman

This repository has beginner API tests created using Postman.

## Test Case
Verify that a public API endpoint returns a successful response.

## Tools
- Postman
- JavaScript test assertions

## Test Script

pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});

## Expected Result
The API should return HTTP status code **200 OK**.

## Evidence
Screenshots of the request setup, test script, and execution results are included.
