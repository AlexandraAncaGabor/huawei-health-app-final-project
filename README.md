# **QA-Project-Huawei-Health App**


The culmination of my coursework involved a thorough examination of the Huawei Health app—an Android companion application that seamlessly connects with Huawei smartwatches to monitor a range of activities.

I selected this application for testing because it's a tool I rely on daily. My motivation stemmed from a personal curiosity to thoroughly explore its functionalities and, in the process, discover any errors or bugs that may have eluded notice.

![Huawei-health-kv](https://user-images.githubusercontent.com/110250127/204929801-986c8fa1-bee6-4ae2-9a02-4ae61612ccb8.jpg)

## **Test plan**


The description of how the testing process was conducted is outlined in the project documentation: [test plan.](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-plan.md). 

## **Test cases**


I formulated a comprehensive set of 34 test cases, encompassing various segments of the mobile application: Health, Device, and Me. These test cases were executed using an Android mobile device running version 11 (Samsung Galaxy A70) in conjunction with a Huawei Watch Fit.

- 🔍 [TC-001](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-001.md) - Check if the app shows sleep details when the "Huawei TruSleep" function is disabled
- 🔍 [TC-002](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-002.md) - Test if a user receives a notification when disabling and then activating a notification
- 🔍 [TC-003](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-003.md) - Check that the application does not allow more than 5 alarms to be set
- 🔍 [TC-004](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-004.md) - Check that a watch face can be installed
- 🔍[TC-005](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-005.md) - Check that the user can install multiple watch faces in the same time
- 🔍[TC-006](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-006.md) - Check that a watch face can be deleted
- 🔍[TC-007](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-007.md) - Verify if a user is able to add another device to the app
- 🔍 [TC-008](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-008.md) - Test if the app is synchronized with the new device and the new information is displayed correctly in the "Health" area
- 🔍 [TC-009](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-009.md) - Verify if the app displays correctly the steps for the first device connected
- 🔍 [TC-010](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-010.md) - Verify if a user can delete a device aleardy added
- 🔍 [TC-011](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-011.md) - Check that the app displays the steps correctly after deleting the second device
- 🔍 [TC-012](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-012.md) - Check that a user cannot upload an incorrect format picture
- 🔍 [TC-013](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-013.md) - Test if a user is able to delete his profile picture
- 🔍 [TC-014](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-014.md) - Check that the app displays an error message when setting up an age under 18
- 🔍 [TC-015](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-015.md) - Test if a user can set up a valid phone number in the "Personal info" area
- 🔍 [TC-016](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-016.md) - Test if a user can set up an invalid phone number in the "Personal info" area
- 🔍 [TC-017](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-017.md) - Test if a user can set up an invalid email address
- 🔍 [TC-018](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-018.md) - Check that the app doesn't allow the user to set up a nickname using symbols
- 🔍 [TC-019](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-019.md) - Test if a user can set up a nickname with 1 character
- 🔍 [TC-20](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-020.md) - Check if a user is able to monitor his weekly steps
- 🔍 [TC-21](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-021.md) - Check if a user can see step report for the current week
- 🔍 [TC-22](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-022.md) - Check if share button from steps section is working properly
- 🔍 [TC-23](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-023.md) - Check if the application automatically detects when a user is running
- 🔍 [TC-24](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-024.md) - Verify if the app autodetects when a user is climbing
- 🔍[TC-25](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-025.md) - Verify if a user can record a dance activity
- 🔍 [TC-26](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-026.md) - Check if a user is able to delete an activity from "Exercise records" area
- 🔍 [TC-27](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-027.md) - Check if user is able to select a step report from a previous date
- 🔍 [TC-28](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-028.md) - Check if heart rate is recorded constantly
- 🔍 [TC-29](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-029.md) - Verify if the highest heart rate is displayed properly
- 🔍 [TC-30](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-030.md) - Verify if the resting heart rate is displayed properly
- 🔍 [TC-31](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-031.md) - Check that a user can't set up a new password using an old password in the "Account security" area
- 🔍 [TC-32](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-032.md) - Check if the app is installed properly
- 🔍 [TC-33](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-033.md) - Unistall Huawei app from a mobile device
- 🔍 [TC-34](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/test-cases/tc-034.md) - Internationalization testing

## **Test execution**

| **Test   cases** | **Test results**          | **Test cases** | **Test results**          | **Test cases** | **Test results**          | **Test cases** | **Test results**          |
|------------------|---------------------------|----------------|---------------------------|----------------|---------------------------|----------------|---------------------------|
| tc-001           | :heavy_check_mark:   Pass | tc-011         | :x:   Fail                | tc-021         | :heavy_check_mark:   Pass | tc-031         | :heavy_check_mark:   Pass |
| tc-002           | :heavy_check_mark:   Pass | tc-012         | :x:   Fail                | tc-022         | :heavy_check_mark:   Pass | tc-032         | :heavy_check_mark:   Pass |
| tc-003           | :heavy_check_mark:   Pass | tc-013         | :x:   Fail                | tc-023         | :heavy_check_mark:   Pass | tc-033         | :heavy_check_mark:   Pass |
| tc-004           | :heavy_check_mark:   Pass | tc-014         | :heavy_check_mark:   Pass | tc-024         | :x:   Fail                | tc-034         | :heavy_check_mark:   Pass |
| tc-005           | :heavy_check_mark:   Pass | tc-015         | :heavy_check_mark:   Pass | tc-025         | :heavy_check_mark:   Pass |                |                           |
| tc-006           | :heavy_check_mark:   Pass | tc-016         | :heavy_check_mark:   Pass | tc-026         | :heavy_check_mark:   Pass |                |                           |
| tc-007           | :heavy_check_mark:   Pass | tc-017         | :heavy_check_mark:   Pass | tc-027         | :heavy_check_mark:   Pass |                |                           |
| tc-008           | :heavy_check_mark:   Pass | tc-018         | :heavy_check_mark:   Pass | tc-028         | :heavy_check_mark:   Pass |                |                           |
| tc-009           | :x: Fail                  | tc-019         | :heavy_check_mark:   Pass | tc-029         | :heavy_check_mark:   Pass |                |                           |
| tc-010           | :heavy_check_mark:   Pass | tc-020         | :heavy_check_mark:   Pass | tc-030         | :heavy_check_mark:   Pass |                |                           |

## **Bug reports**


During the exploratory testing phase, three bugs were identified, and an additional five bugs were uncovered through the systematic execution of test cases.

- 🐞 [Bug-001](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-001.md) - Multiple alarms set up at the same time; (same hour and date)
- 🐞 [Bug-002](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-002.md) - Security number cannot be set up using the pre-added number in the "Profile" area;
- 🐞 [Bug-003](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-003.md) - Heart button from watch faces doesn't work;
- 🐞 [Bug-004](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-004.md) - The app is displaying only the steps for the second device added. (Huawei GT2);
- 🐞 [Bug-005](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-005.md) - The app still displays the steps from the first device after the second device is deleted;
- 🐞 [Bug-006](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-006.md) - All format pictures are supported to be set up by the app;
- 🐞 [Bug-007](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-007.md) - Profile picture cannot be deleted;
- 🐞 [Bug-008](https://github.com/AlexandraAncaGabor/QA-Project-Huawei-Health/blob/feature/refactoring/bugs/bug-008.md) - Climbing is not automatically detected by the app.

## **Tools used**

|     | \*\*               | **Tools used**                                                                                                                     |
| --: | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Project Management | [Jira](https://jira.atlassian.com/)                                                                                                |
|   2 | Test case creation | [Zephyr for Jira](https://marketplace.atlassian.com/apps/1213259/zephyr-scale-test-management-for-jira?tab=overview&hosting=cloud) |
|   3 | Bug tracking       | [Jira](https://jira.atlassian.com/)                                                                                                |

## **Test metrics**

The test metrics are shown in the table below:

|     | **Metrics**                           | **Notes** | **Conclusions**                                                             |
| --: | ------------------------------------- | --------- | --------------------------------------------------------------------------- |
|   1 | Defects found with TCS/ Total Defects | 5/8       | During the exploratory testing session and the execution of test cases, a total of three defects were identified. |
|   2 | TC created/ TC executed               | 34/34     | All TCs were executed according to the plan                                 |
|   3 | TC failed                             | 5         | Small part of the modules contain most of the defects                       |
|   4 | NonfunctionalTC /total TC             | 4/34      | The primary focus was on functional testing; however, the creation of non-functional test cases can be additionaly created|
|   5 | Negative TC /total TC                 | 8/34      | To identify defects, I integrated negative tests into the testing process   |

### **Nonfunctional testing used:**

- Security testing;
- Installation/Uninstallation;
- Internationalization testing

## **Conclusions:**
- The scope of the testing was intentionally limited to a small section of the application, as per the specified request;
  
- In my experience, the more extensive the testing, the greater the likelihood of uncovering defects or generating improvement ideas;
  
- It appears that the application may have more undiscovered bugs based on the issues encountered during the testing process;
  
- Using Jira and Zephyr presented an initial challenge, given my lack of prior experience with these tools. However, as I became more familiar with them, the process proved to be relatively straightforward. Moving forward, I am inclined to explore these tools further in my upcoming projects, as they not only facilitated this project but also resonated positively with my workflow.

