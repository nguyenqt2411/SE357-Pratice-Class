# Requirements Traceability Matrix (RTM)

| Requirement ID | Functional Requirement                  | Non-Functional Requirement                            | Source                         | Stakeholder  | Test Case ID | Proposed Change                            | Release Version |
| -------------- | --------------------------------------- | ----------------------------------------------------- | ------------------------------ | ------------ | ------------ | ------------------------------------------ | --------------- |
| REQ-001        | User registration and account creation  | Security: User authentication                         | User Stories                   | User         | TC-001       | Implement multi-factor authentication    | 1.0             |
| REQ-002        | Browse and enroll in courses             | Accessibility: User-friendly navigation               | Business Requirements Document | User         | TC-002       | Add search functionality      | 1.0             |
| REQ-003        | Access materials and resources  | Scalability: Support for a large number of users       | User Stories                   | User         | TC-003       | Integrate a document preview feature      | 2.0             |
| REQ-004        | Take detail of goods and assessments             | Performance: Low-latency goods loading                  | User Stories                   | User         | TC-004       | Enhance quiz submission process          | 1.0             |
| REQ-005        | Track and manage progress                | Data Privacy: Secure storage of user progress data     | User Stories                   | User         | TC-005       | Implement a progress exchanging visualization dashboard | 2.0             |
| REQ-006        | Forum for student interaction                      | Social: Platform for customer communication             | User Stories                   | Student      | TC-006       | Add comment and reply functionality      | 2.0             |
| REQ-007        | Instructor dashboard for user management         | Performance: Real-time data updates                     | User Stories                   | Instructor   | TC-007       | Enhance dashboard features                | 1.0             |
| REQ-008        | Mobile responsiveness for learning on the go        | Accessibility: Usable on various devices               | User Stories                   | User         | TC-008       | Improve mobile interface                  | 2.0             |
| REQ-009        | Ads campain for brands| Engagement: Combine buying and conducting adversting campain     | User Stories                   | Student      | TC-009       | Integrate badges and rewards system      | 1.0             |
| REQ-010        | Automated course evaluation and feedback            | Efficiency: Streamline the feedback process            | User Stories                   | Student      | TC-010       | Implement automated feedback system      | 2.0             |
| REQ-011        | Integration with external learning resources        | Compatibility: Support integration with third-party   | Business Requirements Document | User         | TC-011       | Connect with seller | 1.0             |
| REQ-012        | Advanced search and filtering options     | Usability: Improve user experience with enhanced search| User Stories                   | User         | TC-012       | Add advanced search features              | 2.0             |
| REQ-013        | Real-time progress tracking for instructors         | Performance: Instant updates on purchasing progress       | User Stories                   | Instructor   | TC-013       | Enable real-time progress monitoring     | 1.0             |
| REQ-014        | Integration with video conferencing tools           | Compatibility: Seamless integration with video tools  | Business Requirements Document | User         | TC-014       | Connect with video review of goods | 2.0             |
| REQ-015        | Peer review system for assignments                  | Quality Assurance: Enhance assignment evaluation        | User Stories                   | Student      | TC-015       | Implement peer review functionality       | 1.0             |

| **Use Case**                   | **Requirement** | **REQ-001** | **REQ-002** | **REQ-003** | **REQ-004** | **REQ-005** |
| ------------------------------ | --------------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| User Registration              | User            | R           |             |             |             | U           |
| Browse Courses                 | User            | R           |             |             |             |             |
| Access Materials      | User            | R           |             | R           |             |             |
| Take Detail                 | User            | R           |             |             | R           |             |
| Track and Manage Progress      | User            | R           |             |             |             | R           |
| Forum Interaction              | Customer      | U           |             |             |             | R           |
| Instructor Dashboard           | Instructor      |             |             |             |             | R           |
| Mobile Responsiveness          | User            | R           |             |             |             | R           |
| Adversting                   | User         |             |             |             |             | R           |
| Automated Evaluation           | Customer         | U           |             | R           |             |             |
| External Integration           | User            |             |             | R           |             | R           |
| Advanced Search                | User            |             | R           |             |             |             |
| Real-time Tracking             | Instructor      |             | U           |             |             | R           |
| Video Reviewing           | User            |             |             | R           |             |             |
| Peer Review                    | User         | U           |             |             |             | U           |

| **Use Case**                   | **Requirement** | **REQ-006** | **REQ-007** | **REQ-008** | **REQ-009** | **REQ-010** | **REQ-011** | **REQ-012** | **REQ-013** | **REQ-014** | **REQ-015** |
| ------------------------------ | --------------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| User Registration              | User            | U           |             | R           |             |             |             |             |             |             |             |
| Browse Courses                 | User            |             |             | R           |             |             |             |             |             |             |             |
| Access  Materials      | User            |             |             |             |             |             |             |             |             |             |             |
| Take Detail of goods                   | User            |             |             |             |             |             |             |             |             |             |             |
| Track and Manage Progress      | User            |             |             |             |             |             |             |             |             |             |             |
| Forum Interaction              | Customer         |             |             |             |             |             |             |             |             |             |             |
| Instructor Dashboard           | Instructor      |             |             |             |             |             |             |             |             |             |             |
| Mobile Responsiveness          | User            |             |             | R           |             |             |             |             |             |             |             |
| Adversting Campain                   | User         |             | U           |             |             |             |             |             |             |             |             |
| Automated Evaluation           | Customer         |             |             |             |             |             |             |             |             |             |             |
| External Integration           | User            |             | R           |             |             |             |             |             |             |             |             |
| Advanced Search                | User            |             |             |             |             |             |             |             |             |             |             |
| Real-time Tracking             | Instructor      |             | U           |             |             |             |             |             |             |             |             |
| Video Conferencing             | User            |             |             | R           |             |             |             |             |             |             |             |
| Peer Review                    | User         |             | U           |             |             |             |             |             |             |             |             |



## Requirements Source Traceability Matrix

| **Requirement ID** | **Source**                         |
| ------------------- | ---------------------------------- |
| REQ-001             | User Stories                       |
| REQ-002             | Business Requirements Document     |
| REQ-003             | User Stories                       |
| REQ-004             | User Stories                       |
| REQ-005             | Business Requirements Document     |
| REQ-006             | User Stories                       |
| REQ-007             | User Stories                       |
| REQ-008             | User Stories                       |
| REQ-009             | User Stories                       |
| REQ-010             | User Stories                       |
| REQ-011             | Business Requirements Document     |
| REQ-012             | User Stories                       |
| REQ-013             | User Stories                       |
| REQ-014             | Business Requirements Document     |
| REQ-015             | User Stories                       |


## Requirements Stakeholder Traceability Matrix

| **Requirement ID** | **Stakeholder**  |
| ------------------- | ---------------- |
| REQ-001             | User             |
| REQ-002             | User             |
| REQ-003             | User             |
| REQ-004             | User             |
| REQ-005             | Organization     |
| REQ-006             | Customer          |
| REQ-007             | Instructor       |
| REQ-008             | User             |
| REQ-009             | User          |
| REQ-010             | Customer          |
| REQ-011             | User             |
| REQ-012             | User             |
| REQ-013             | Instructor       |
| REQ-014             | User             |
| REQ-015             | User          |


## Requirements Test Traceability Matrix

| **Requirement ID** | **Test Case ID** |
| ------------------- | ---------------- |
| REQ-001             | TC-001           |
| REQ-002             | TC-002           |
| REQ-003             | TC-003           |
| REQ-004             | TC-004           |
| REQ-005             | TC-005           |
| REQ-006             | TC-006           |
| REQ-007             | TC-007           |
| REQ-008             | TC-008           |
| REQ-009             | TC-009           |
| REQ-010             | TC-010           |
| REQ-011             | TC-011           |
| REQ-012             | TC-012           |
| REQ-013             | TC-013           |
| REQ-014             | TC-014           |
| REQ-015             | TC-015           |


## Requirements Change Traceability Matrix

| **Requirement ID** | **Proposed Change**                            |
| ------------------- | --------------------------------------------- |
| REQ-001             | Implement multi-factor authentication         |
| REQ-002             | Add search functionality           |
| REQ-003             | Integrate a document preview feature           |
| REQ-004             | Enhance items changing  process               |
| REQ-005             | Implement a progress visualization dashboard |
| REQ-006             | Add comment and reply functionality           |
| REQ-007             | Enhance dashboard features                    |
| REQ-008             | Improve mobile interface                      |
| REQ-009             | Integrate badges and rewards system           |
| REQ-010             | Implement automated feedback system           |
| REQ-011             | Connect with external learning platforms      |
| REQ-012             | Add advanced search features                   |
| REQ-013             | Enable real-time progress monitoring          |
| REQ-014             | Connect with video conferencing platforms      |
| REQ-015             | Implement peer review functionality            |


## Requirements Release Traceability Matrix

| **Requirement ID** | **Release Version** |
| ------------------- | ------------------- |
| REQ-001             | 1.0                 |
| REQ-002             | 2.0                 |
| REQ-003             | 1.0                 |
| REQ-004             | 2.0                 |
| REQ-005             | 1.0                 |
| REQ-006             | 2.0                 |
| REQ-007             | 1.0                 |
| REQ-008             | 2.0                 |
| REQ-009             | 1.0                 |
| REQ-010             | 2.0                 |
| REQ-011             | 1.0                 |
| REQ-012             | 2.0                 |
| REQ-013             | 1.0                 |
| REQ-014             | 2.0                 |
| REQ-015             | 1.0                 |

