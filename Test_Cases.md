# Test Cases – E-Commerce Demo Website

## Registration Test Cases (R1)

| TC ID | Scenario ID | Description | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status | Priority |
|------|-------------|------------|---------------|------------|-----------|-----------------|---------------|--------|----------|
| TC_R1_01 | TS_R1_01 | Verify registration with valid data | User is on registration page | 1. Open registration page<br>2. Enter valid details<br>3. Click Register | Valid email, valid password | User is registered successfully | User was successfully registered and redirected to account page | Pass | High |
| TC_R1_02 | TS_R1_02 | Verify registration with invalid email | User is on registration page | 1. Enter invalid email<br>2. Click Register | invalid-email | Error message displayed | System displayed validation message "Invalid email address" and blocked registration | Pass | Medium |
| TC_R1_03 | TS_R1_03 | Verify mandatory fields validation | User is on registration page | 1. Leave mandatory fields empty<br>2. Click Register | Empty fields | Validation error displayed | System displayed validation message "Password is required" and blocked registration | Pass | High |

## Login Test Cases (R2)

| TC ID | Scenario ID | Description | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status | Priority |
|------|-------------|------------|---------------|------------|-----------|-----------------|---------------|--------|----------|
| TC_R2_01 | TS_R2_01 | Verify login with valid credentials | User is registered | 1. Open login page<br>2. Enter valid credentials<br>3. Click Login | Valid username/password | Login successful | User logged in successfully and was redirected to account page | Pass | High |
| TC_R2_02 | TS_R2_02 | Verify login with invalid password | User is registered | 1. Enter valid username<br>2. Enter invalid password<br>3. Click Login | Wrong password | Error message displayed | | | High |
| TC_R2_03 | TS_R2_03 | Verify login with empty fields | User is on login page | 1. Leave fields empty<br>2. Click Login | Empty fields | Validation message displayed | | | Medium |

## Add to Cart Test Cases (R5)

| TC ID | Scenario ID | Description | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status | Priority |
|------|-------------|------------|---------------|------------|-----------|-----------------|---------------|--------|----------|
| TC_R5_01 | TS_R5_01 | Verify product added to cart | User is logged in | 1. Select product<br>2. Click Add to Cart | Product | Product added to cart | | | High |
| TC_R5_02 | TS_R5_02 | Verify cart quantity update | Product in cart | 1. Increase quantit
