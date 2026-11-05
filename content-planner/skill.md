---
name: content-planner
description: Validates calendar dates, publishing deadlines, dependencies, scheduling conflicts and approval requirements before content scheduling.
---

# Calendar Constraints

## 1. Main Purpose

Prevent the agent from scheduling content on inappropriate dates, overlooking important events, or scheduling content before required dependencies and approvals are ready.

## 2. Input

### 2.1 Calendar Information

- Calendar name
- Publishing channel
- Planning frequency
- Planning owner
- Calendar coordinator
- Content owner
- Reviewer
- Final approver
- Publisher
- Timezone
- Calendar source
- Blackout dates
- Publishing statuses

### 2.2 Recurring and Fixed Content Information

- Recurring occasions
- Fixed dates
- Company events
- Campaigns
- Awareness days
- Employee milestones, where authorised

Use the calendar records supplied through the current context package. Do not assume or invent events or dates.

Employee date-of-joining information is restricted. Use it only when the current stage is authorised to access the record and the milestone has been verified for approved employee-recognition content.

### 2.3 Calendar Record Fields

- Event ID
- Event name
- Event type
- Date
- Time
- Timezone
- Content required
- Target audience
- Content format
- Draft deadline
- Review deadline
- Approval deadline
- Publishing date
- Dependency
- Blackout
- Owner
- Confirmation source
- Status

### 2.4 Context and Knowledge Sources

- Relevant calendar records from the current context package.
- Approved period brief.
- Relevant calendar and approval information from the client knowledge files.
- Earlier approved stage outputs, where relevant.
- Authorised restricted records, only when required for the stage.

## 3. Instructions

1. Read the relevant calendar information and period brief from the current context package.

2. Identify recurring occasions, fixed dates, company events, campaigns and employee milestones from the supplied records.

3. Validate event dates and timezones before scheduling content.

4. Check whether an awareness day is relevant to the target audience.

5. Verify employee milestones before using them for employee-recognition content. Access restricted employee information only when authorised.

6. Confirm events, client announcements and campaigns with the responsible owner when confirmation is required.

7. Check draft, review and approval deadlines before assigning publishing dates.

8. Verify that required inputs, creative assets, speakers and approvals are available before scheduling.

9. Check blackout dates and identify scheduling conflicts.

10. Flag missing dependencies, unconfirmed dates, conflicting events and incomplete calendar information.

11. Do not treat a calendar entry as an automatically approved post.

12. Do not allow publishing dates to override required review and approval processes.

13. Reconcile the supplied calendar with the relevant period brief before finalising the publishing schedule.

14. Clearly identify provisional and unconfirmed calendar information instead of making assumptions.

15. Do not invent missing calendar details or treat unconfirmed information as approved.

## 4. Output

Produce a structured calendar constraints report.

### 4.1 Calendar Information

- Calendar name
- Publishing channel
- Planning frequency
- Planning owner
- Calendar coordinator
- Content owner
- Reviewer
- Final approver
- Publisher
- Timezone
- Calendar source
- Blackout dates
- Publishing statuses

### 4.2 Calendar Records

Provide the available calendar records using the supplied fields:

- Event ID
- Event name
- Event type
- Date
- Time
- Timezone
- Content required
- Target audience
- Content format
- Draft deadline
- Review deadline
- Approval deadline
- Publishing date
- Dependency
- Blackout
- Owner
- Confirmation source
- Status

### 4.3 Calendar Validation Findings

Identify:

- Missing or unconfirmed event dates.
- Events requiring owner confirmation.
- Awareness days requiring audience relevance checks.
- Employee milestones requiring verification.
- Scheduling conflicts.
- Blackout dates.
- Missing dependencies.
- Draft, review and approval deadline issues.
- Publishing dates that conflict with approval requirements.
- Provisional or unconfirmed calendar information.

### 4.4 Final Calendar Readiness

Provide the calendar validation status and identify the items that must be resolved before the publishing schedule is finalised.

Clearly distinguish confirmed information, provisional information and unresolved issues.