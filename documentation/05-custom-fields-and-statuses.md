# Custom Fields and Workflow Statuses

## Overview

This document describes the custom fields and workflow statuses configured for the CarePoint Medical Clinic ClickUp implementation.

Rather than relying solely on ClickUp's default configuration, custom fields and workflow statuses were created to mirror real operational processes within the clinic. This approach improves task visibility, standardizes workflows, and enables staff to track work consistently across departments.

---

# Design Objectives

The custom fields and statuses were designed to:

- Standardize operational workflows
- Capture key operational information
- Improve task visibility
- Support staff accountability
- Track work through defined process stages
- Reduce inconsistencies in task management

---

# Custom Fields

Several custom fields were created to support patient registration and operational tracking.

## Patient ID

**Field Type:** Text

Stores a unique identifier for each patient registration task.

Example:

```text
CPMC-2026-001
```

---

## Patient Type

**Field Type:** Dropdown

Used to classify patients during registration.

Values include:

- New Patient
- Returning Patient
- Walk-in
- Referral

---

## Phone Number

**Field Type:** Phone/Text

Stores the patient's primary contact number for communication and follow-up activities.

---

## Insurance Provider

**Field Type:** Dropdown

Captures the patient's payment or insurance arrangement.

Values include:

- Private Insurance
- National Health Insurance
- Employer Health Plan
- Self-Pay (Cash)
- Corporate Account
- HMO
- Government Health Scheme
- Other

---

## Assigned Staff

**Field Type:** People

Identifies the staff member responsible for completing the task.

Using ClickUp's People field allows work to be assigned directly to workspace members, improving accountability and workload management.

---

## Registration Priority

**Field Type:** Dropdown

Indicates the urgency of the registration process.

Values include:

- Routine
- Urgent
- Emergency

---

## Registration Date

**Field Type:** Date

Records the date the patient registration activity was initiated.

---

# Workflow Statuses

Each operational List uses custom workflow statuses that reflect the actual progression of work.

Instead of generic statuses, each workflow was configured to match real healthcare processes.

---

## Patient Registration

Workflow:

```text
New Registration
        ↓
Demographics Collected
        ↓
Insurance Verified
        ↓
Registration Complete
```

---

## Appointments

Workflow:

```text
Appointment Requested
        ↓
Appointment Confirmed
        ↓
Patient Checked In
        ↓
Consultation Completed
```

---

## Follow-up Care

Workflow:

```text
Follow-up Scheduled
        ↓
Patient Contacted
        ↓
Follow-up In Progress
        ↓
Follow-up Completed
```

---

## Sample Collection

Workflow:

```text
Test Requested
        ↓
Sample Collected
        ↓
Sent to Laboratory
        ↓
Collection Completed
```

---

## Test Processing

Workflow:

```text
Sample Received
        ↓
Analysis in Progress
        ↓
Quality Check
        ↓
Analysis Completed
```

---

## Results Review

Workflow:

```text
Results Pending Review
        ↓
Pathologist Review
        ↓
Results Approved
        ↓
Results Released
```

---

## Medication Dispensing

Workflow:

```text
Prescription Received
        ↓
Medication Prepared
        ↓
Ready for Pickup
        ↓
Dispensed
```

---

## Prescription Review

Workflow:

```text
Prescription Submitted
        ↓
Clinical Review
        ↓
Approved
        ↓
Completed
```

---

## Inventory Management

Workflow:

```text
Stock Received
        ↓
Stock Verified
        ↓
Available
        ↓
Low Stock Alert
```

---

## Patient Billing

Workflow:

```text
Charges Generated
        ↓
Invoice Created
        ↓
Payment Received
        ↓
Billing Complete
```

---

## Insurance Claims

Workflow:

```text
Claim Prepared
        ↓
Claim Submitted
        ↓
Under Review
        ↓
Claim Approved
```

---

## Outstanding Payments

Workflow:

```text
Payment Due
        ↓
Reminder Sent
        ↓
Payment Overdue
        ↓
Resolved
```

---

## Incident Reports

Workflow:

```text
Incident Reported
        ↓
Investigation Started
        ↓
Corrective Action
        ↓
Closed
```

---

## Internal Audits

Workflow:

```text
Audit Scheduled
        ↓
Audit In Progress
        ↓
Findings Documented
        ↓
Audit Completed
```

---

## Staff Compliance

Workflow:

```text
Training Assigned
        ↓
Training In Progress
        ↓
Assessment Completed
        ↓
Compliant
```

---

# Design Benefits

Implementing custom fields and workflow statuses provides several operational advantages:

- Standardized processes across departments
- Improved visibility into task progress
- Better accountability through task ownership
- Consistent operational reporting
- Easier onboarding for new staff
- Reduced reliance on manual tracking

---

# Conclusion

The combination of custom fields and workflow-specific statuses transforms ClickUp from a generic task management platform into a structured operational management system tailored to healthcare workflows.

These configurations improve consistency, enhance visibility, and ensure that each department follows a clearly defined process from initiation to completion.
