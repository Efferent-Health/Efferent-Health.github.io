<img class="logo" width="300" alt="logo" src="../../efferent_logo.png" />

<br/>

# Release Notes

```
Product Name:   eVue and eFit
Version Number: 5.32
Release Date:   May, 2025
```

## Table of Contents

1. [Introduction](#introduction)
2. [New Features](#new-features)
3. [Improvements](#improvements)
4. [Bug Fixes](#bug-fixes)
5. [Deprecations](#deprecations)
6. [Known Issues](#known-issues)
7. [Upcoming Features](#upcoming-features)

## Introduction

Welcome to the May 2025 release of Efferent eVue and eFit. This update introduces new and anticipated features designed to significantly enhance efficiency and usability. It also includes key enhancements and critical bug fixes to ensure a smoother, more reliable user experience.

## New Features

### SmartUpload

We are introducing a redesigned Upload experience in eVue, built to improve data accuracy, visibility, and control when uploading studies to the platform. This release brings a more intuitive layout, enhanced evaluation feedback, and smarter workflows for handling studies.

_SmartUpload: AS IS option selected_

<img width=900 src="smartupload.png">

_SmartUpload: EDIT option_

<img width=900 src="eedit.png">

_SmartUpload: Bulk action selected_

<img width=900 src="bulk.png">

Key Improvement|Description<br>|
--|:--:|
Selectable Study Boxes | Studies to process are now displayed as selectable boxes on the left side of the interface. When a box is selected, its corresponding study information and patient demographics are shown in structured tables next to it. Only the data of the selected study is displayed at a time, helping to optimize screen space and maintain a clear, organized view—especially helpful when handling files with multiple studies.
Streamlined Data Management| The interface now organizes all key actions clearly per study, including:<br>**AS IS**: Upload the study with its original data.<br> **EDIT**: Modify patient demographics before upload.<br>**PICK**: Link the study to an existing patient in the system.<br>**DEIDENTIFY**: Anonymize the study before uploading.<br>**DISCARD**: Exclude a study from the upload.
Bulk Actions Buttons| Effortlessly manage multiple studies at once using the new bulk action buttons located above the study boxes. Options like **Deidentify All** and **Discard All** let you apply actions to all studies in a single click, streamlining your workflow.
Smart Evaluation Notifications|After scanning, the system automatically analyzes each study and highlights potential issues such as patient data discrepancies or conflicts with existing cloud data. These evaluations are displayed as inline alerts with attention icons, positioned directly above the tables showing the study information and patient demographics, ensuring users can immediately notice and address any issues.|
Smart Editing| When editing demographics, clicking Check and Apply triggers a system-wide search to detect existing patient matches by ID, prompting whether to apply changes across all studies from the same patient
Upload Summary|After the upload, users receive a clear on-screen status report indicating the number of images successfully processed and those that failed. The report also details non-image instances—such as KO, PR without pixel data, RT, and REP formats—that were included in the upload.|
Discrepancy Quarantine Handler|Automatically isolates studies with demographic discrepancies during upload, sending them to a quarantine list for manual review and resolution to ensure data integrity.|


## Improvements


## Bug Fixes



## Deprecations

None

## Known Issues

None

## Upcoming Features

None


---

Thank you for being a valued user of Efferent. We hope these updates enhance your experience. For any questions or feedback, please contact our support team at support@efferenthealth.com .