## Huawei Health App - Final Project


## 📌 Project Context


This project demonstrates a real-world inspired QA process for a mobile health tracking application (Huawei Health). It includes structured manual testing, exploratory testing,  and detailed defect reporting.

This project is based on the version of Huawei Health available at the time of testing and focuses on key functionalities such as activity tracking, heart rate monitoring, and device integration.


![Huawei-health-kv](https://user-images.githubusercontent.com/110250127/204929801-986c8fa1-bee6-4ae2-9a02-4ae61612ccb8.jpg)

## 🧰 Tools & Technologies

- Testing Tools: Jira, Zephyr for Jira (for test case management); 
- Environment: Android app (Samsung Galaxy A70, Android 11), Huawei smartwatch (Huawei Watch Fit); 
- Version Control: GitHub

## Types of Testing Included
•⁠  ⁠Manual Testing;

•⁠  ⁠Exploratory Testing;

•⁠  ⁠Positive & Negative Test Scenarios;

•  Security testing;

•  Installation/Uninstallation;

•  Internationalization testing;

## 🧠 Testing Approach

Testing was planned and executed based on risk assessment and user impact. Core user journeys were prioritized, then edge cases and negative scenarios were added.

## 🤔 Why These Tests Were Chosen

Test scenarios were selected by analyzing:
•⁠  ⁠User value of features
•⁠  ⁠Likelihood of failure

## 📋 Test Coverage Overview

## Key Features Tested
✔ User onboarding  
✔ Activity tracking (walking, steps, climbing)  
✔ Data synchronization with device sensors  
✔ Error and edge case handling


## Test plan

The description of how the testing process was conducted is outlined in the project documentation: [test plan.](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-plan.md)  

## Test cases

The test cases cover major functionalities of the Huawei Health app:

- 🔍 [TC-001](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-001.md) - Verify sleep details display when "Huawei TruSleep" is disabled
- 🔍 [TC-002](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-002.md) - Verify user receives a notification when toggling notifications off and on
- 🔍 [TC-003](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-003.md) - Check that a user cannot set more than 5 alarms
- 🔍 [TC-004](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-004.md) - Watch face installation
- 🔍[TC-005](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-005.md) - Verify multiple watch faces can be installed simultaneously
- 🔍[TC-006](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-006.md) - Watch face deletion
- 🔍[TC-007](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-007.md) - Adding another device to the app
- 🔍 [TC-008](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-008.md) - Verify new device sync in "Health" section
- 🔍 [TC-009](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-009.md) - Verify steps are displayed correctly for the first connected device
- 🔍 [TC-010](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-010.md) - Verify a user can delete an added device
- 🔍 [TC-011](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-011.md) - Verify steps are displayed correctly after deleting the second device
- 🔍 [TC-012](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-012.md) - Verify user cannot upload a picture in an incorrect format
- 🔍 [TC-013](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-013.md) - Check that the profile picture can be removed by the user
- 🔍 [TC-014](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-014.md) - Verify app shows an error when age under 18 is entered
- 🔍 [TC-015](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-015.md) - Verify a user can enter a valid phone number in "Personal info"
- 🔍 [TC-016](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-017.md) - Email field validation
- 🔍 [TC-017](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-018.md) - Nickname field validation
- 🔍 [TC-019](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-019.md) - Test if a user can set up a nickname with 1 character
- 🔍 [TC-018](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-020.md) - Verify a user can monitor weekly steps
- 🔍 [TC-019](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-021.md) - Verify the user can view the current week's step report
- 🔍 [TC-020](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-022.md) - Verify the share button in the steps section works correctly
- 🔍 [TC-021](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-023.md) - Verify app automatically detects running activity
- 🔍 [TC-022](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-024.md) - Verify the app automatically detects climbing activity
- 🔍[TC-023](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-025.md) - Verify a user can record a dance activity
- 🔍 [TC-024](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-026.md) - Verify a user can delete an activity from the "Exercise records" section
- 🔍 [TC-025](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-027.md) - Verify a user can view a step report from a previous date
- 🔍 [TC-026](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-028.md) - Verify heart rate is recorded continuously
- 🔍 [TC-027](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-029.md) - Verify the highest heart rate is displayed correctly
- 🔍 [TC-028](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-030.md) - Verify resting heart rate is displayed correctly
- 🔍 [TC-029](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-031.md) - Verify a user cannot reuse an old password in "Account security"
- 🔍 [TC-030](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-032.md) - Ensure proper app installation
- 🔍 [TC-031](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-033.md) - Ensure Huawei app uninstallation works
- 🔍 [TC-032](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-034.md) - Internationalization testing

## Test execution

| **Test   cases** | **Test results**          | **Test cases** | **Test results**          | **Test cases** | **Test results**          | **Test cases** | **Test results**          |
|------------------|---------------------------|----------------|---------------------------|----------------|---------------------------|----------------|---------------------------|
| tc-001           | :heavy_check_mark:   Pass | tc-011         | :x:   Fail                | tc-021         | :heavy_check_mark:   Pass | tc-031         | :heavy_check_mark:   Pass |
| tc-002           | :heavy_check_mark:   Pass | tc-012         | :x:   Fail                | tc-022         | :x: Fail  | tc-032         | :heavy_check_mark:   Pass |
| tc-003           | :x: Fail   | tc-013         | :x:   Fail                | tc-023         | :heavy_check_mark:   Pass | 
| tc-004           | :heavy_check_mark:   Pass | tc-014         | :heavy_check_mark:   Pass | tc-024         | :heavy_check_mark: Pass               | 
| tc-005           | :heavy_check_mark:   Pass | tc-015         | :heavy_check_mark:   Pass | tc-025         | :heavy_check_mark:   Pass |                |                           |
| tc-006           | :heavy_check_mark:   Pass | tc-016         | :heavy_check_mark:   Pass | tc-026         | :heavy_check_mark:   Pass |                |                           |
| tc-007           | :heavy_check_mark:   Pass | tc-017         | :heavy_check_mark:   Pass | tc-027         | :heavy_check_mark:   Pass |                |                           |
| tc-008           | :heavy_check_mark:   Pass | tc-018         | :heavy_check_mark:   Pass | tc-028         | :heavy_check_mark:   Pass |                |                           |
| tc-009           | :x: Fail                  | tc-019         | :heavy_check_mark:   Pass | tc-029         | :heavy_check_mark:   Pass |                |                           |
| tc-010           | :heavy_check_mark:   Pass | tc-020         | :heavy_check_mark:   Pass | tc-030         | :heavy_check_mark:   Pass |                |                           |

## Bug reports


During the exploratory testing phase, two bugs were identified, and an additional six bugs were uncovered through the systematic execution of test cases.

- 🐞 [Bug-001](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-001.md) - Multiple alarms set up at the same time; (same hour and date)
- 🐞 [Bug-002](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-002.md) - Security number cannot be set up using the pre-added number in the "Profile" area;
- 🐞 [Bug-003](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-003.md) - Heart button from watch faces doesn't work;
- 🐞 [Bug-004](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-004.md) - The app is displaying only the steps for the second device added. (Huawei GT2);
- 🐞 [Bug-005](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-005.md) - Steps from the deleted device are displayed after removing the device from the app; 
- 🐞 [Bug-006](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-006.md) - All format pictures are supported to be set up by the app; 
- 🐞 [Bug-007](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-007.md) - Profile picture cannot be deleted;
- 🐞 [Bug-008](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-008.md) - Climbing is not automatically detected by the app.

## Test metrics

The test metrics are shown in the table below:

|     | **Metrics**                           | **Notes** | **Conclusions**                                                             |
| --: | ------------------------------------- | --------- | --------------------------------------------------------------------------- |
|   1 | Defects found with TCS/ Total Defects | 6/8       | During the exploratory testing session and the execution of test cases, a total of two defects were identified. |
|   2 | TC created/ TC executed               | 32/32     | All TCs were executed according to the plan                                 |
|   3 | TC failed                             | 6/32         | Small part of the modules contain most of the defects                       |
|   4 | NonfunctionalTC /total TC             | 4/32      | The primary focus was on functional testing; however, the creation of non-functional test cases can be additionaly created|
|   5 | Negative TC /total TC                 | 8/32      | To identify defects, I integrated negative tests into the testing process   |



## 📈 Learnings

Key learnings from this project:

•⁠  ⁠Better understanding of mobile-specific testing risks; 

•⁠  ⁠Enhanced exploratory testing techniques; 

•⁠  ⁠Clearer structuring of test cases and bug reports; 

•⁠  ⁠Prioritization of features based on user impact


**Note:*
*- The tests were originally created at the beginning of my QA experience (2022), and some were not written in the most precise format. Therefore, I decided to review and rewrite the test cases.*

*- No regression tests have been performed since, and the application has undergone changes, so these tests may only apply to the version available at that time.*

_✨ Guided by curiosity, committed to quality._
