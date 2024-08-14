<! -- omit in toc -->
## 0901-SS-SY-BIS-SYSPRO Technical Knowledge Base

<! -- omit in toc -->
### Example Topic

<! -- omit in toc -->
#### In this article

- [0901-SS-SY-BIS-SYSPRO Technical Knowledge Base](#0901-ss-sy-bis-syspro-technical-knowledge-base)
  - [Example Topic](#example-topic)
    - [In this article](#in-this-article)
  - [Overview](#overview)
    - [Pre-requisites](#pre-requisites)
    - [What is Project Recovery Journals?](#what-is-project-recovery-journals)
    - [Contents of the Project Recovery Journals application](#contents-of-the-project-recovery-journals-application)
    - [The workflow process for Project Recovery Journals](#the-workflow-process-for-project-recovery-journals)
  - [Tutorial](#tutorial)
    - [How does it work?](#how-does-it-work)
    - [Submitting Project Recovery Journals for approval](#submitting-project-recovery-journals-for-approval)
    - [Approving/Posting Project Recovery Journals](#approvingposting-project-recovery-journals)
  - [Troubleshooting](#troubleshooting)
    - [Frequently Asked Questions](#frequently-asked-questions)

### Overview

#### Pre-requisites

For any of these Project Recovery Journals to be processed there is a requirement for a sub-contract captured for the specified budget code as well as the forecast values and dates to be up to date according to the current execution plan or expectation.

---

__NOTE__

The generation and considerations are not covered in this topic. It is assumed that the knowledge exists.

---

#### What is Project Recovery Journals?

Project Recovery Journals is a custom development module implemented to streamline the recovery of Corporate Contribution, Warranty, Management Reserve and Profit Margin from projects. The aim of this implementation is to replace the manual requirement to capture AP invoices for each project transaction required for the recovery of internal funds and allow for better tracking and reporting of what internal recovery values are paid and still outstanding.

#### Contents of the Project Recovery Journals application

Within the Transaction Engine application for Project Recovery Journals (located in SYSPRO), there are 4 different types of recovery namely Corporate Contribution, Warranty, Management Reserve and Profit Margin. Each one of these have two dashboards, one for submitting journals for approval and a second for approval of the journals submitted at which point the system will post the journals into the general ledger. It is important to note that there is/will be other journal processes implemented into this application but are not covered in this topic as they have different processes and requirements.

---

__NOTE__

//Blank

---

#### The workflow process for Project Recovery Journals

At this point, we make the assumption that a sub-contract for the Project Recovery Journals. The first step is to ensure that the milestone of the sub-contract that must be recovered now has been updated for the milestone's forecast date to be in the period that it has to be recovered and the value has been updated to the correct value to be recovered for the period specified. The next step is to submit the journals for the specified period and then finally approve or reject these journals. The journal that is posted will provide enough data to relevant reports, like the Project P&L, that will provide insight into cashflow requirements, if it has been paid further down the process, etc.

### Tutorial

🔹 Corporate Contribution Journals\
🔹 Warranty Journals\
🔹 Management Reserve Journals\
🔹 Profit Margin Journals

The following guide explains the process to submit and approve the journals mentioned above and what affects it has in the system allowing the users to understand what to do and what the process entails for future troubleshooting.

#### How does it work?

As discussed previously, the aim of these dashboard and processes is to make transaction for the internal project recovery invoices more efficient, remove possible capturing and allocation errors, and also allow for better cash flow tracking using existing reports by posting journals instead of invoices and also managing the process further down the line in the accounts function to identify allocation errors and funding requirements.

---

__NOTE__

//Blank

---

#### Submitting Project Recovery Journals for approval

Once the pre-requisites have all been met and you have reached a point in time where you need to recover costs from the project, you can navigate to the 'Project Recovery Journals' application on your SYSPRO home screen.

![TestImage1](/TrainingDocs/images/TestImage1.png "")

Within this application you have the option to submit journals for the four different project recovery types. You can now select the correct 'Submit Journals' dashboard that is applicable to the transaction you need to process.

![TestImage1](/TrainingDocs/images/TestImage2.png "")

When you are using any of the 'Submit Journals' dashboards, you will first be required to input a date to search for a range of sub-contract milestones and click on search. This will search for all of the sub-contract milestones relating to the type of transaction, i.e. Profit Margin, within the month and year for the date you have selected. The search functionality is based on the forecast date of the milestones of the sub-contract.

[Need to add an image here]:#

Once you have clicked on search, the window will populate with all of the milestones that match the search criteria.

There is a status column that can be changed. This can either be empty (nothing will be submitted) or you can select the 'Submit' option. You can use the submit option for multiple rows at the same time to submit them at once. However, you can only submit for one period at a time. In other words, you will not be able to submit milestones for April and May, but only for May or April separately.

Once you have changed the status for the milestone you want to submit, you can click on the save button in the bottom right of the window/dashboard. This will highlight all of the rows that you made changes to either GREEN or RED.

GREEN: If there aren't any issues and it has submitted the row/transaction successfully for approval, it will highlight GREEN. It is important to note that it will still be visible on the screen until you refresh/search again. DO NOT SUBMIT THE ROWS AGAIN!

RED: If there are issues, the rows/transactions that do have issues will be highlighted in RED and there will be a temporary pop-up notification to explain the reason there is an issue/error. The rows that are highlighted RED will NOT be submitted and the errors must be fixed before they will be submitted for approval and removed from the list.

[Need to add an image here]:#

Some criteria to consider when submitting Project Recovery Journals for approval:\
➤ You will only be able to see the data when you click search while you are in the 'Project Accounts' role in SYSPRO. The other roles DO NOT have access to this functionality.\
➤ You can only submit journals for approval for one month at a time. It is suggested and preferred that you DO NOT post journals for previous or future months. Journals should only be posted for the month currently in question.

#### Approving/Posting Project Recovery Journals

### Troubleshooting

#### Frequently Asked Questions
