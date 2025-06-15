# Test Cases for SauceDemo Functional Testing

This document contains the key functional test cases executed for the SauceDemo website.

| Test ID | Test Name                    | Test Steps                                                                                     | Expected Result                                         | Actual Result | Status   | Remarks           |
|---------|------------------------------|------------------------------------------------------------------------------------------------|---------------------------------------------------------|---------------|----------|-------------------|
| TC01    | Login with valid credentials  | 1. Go to login page<br>2. Enter valid username and password<br>3. Click Login                 | User is successfully logged into the homepage           |               | Pass/Fail|                   |
| TC02    | Login with invalid credentials| 1. Go to login page<br>2. Enter invalid username and/or password<br>3. Click Login            | Error message "Username or password is incorrect" shown |               | Pass/Fail|                   |
| TC03    | Add product to cart           | 1. Login<br>2. Select a product<br>3. Click "Add to cart"                                    | Product appears in the shopping cart                     |               | Pass/Fail|                   |
| TC04    | Complete checkout successfully| 1. Add product to cart<br>2. Go to checkout<br>3. Enter required information<br>4. Complete purchase | Purchase completes successfully                        |               | Pass/Fail|                   
