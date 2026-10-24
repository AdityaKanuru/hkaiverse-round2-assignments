# Task 1 — Campus Loop: Every Student Request Gets an Owner

## 1. Objective

Campus Loop proposes a simple workflow to ensure student requests have a clear owner, status, and follow-up.

## 2. Problem

When requests pass between people without clear ownership or status updates, students may experience delays, repeated follow-ups, or unresolved queries. This is a problem hypothesis, not a verified claim about ICFAI's current process.

## 3. Proposed Workflow

1. Student submits a request.
2. Required information is checked.
3. Incomplete requests are returned for correction.
4. Complete requests are assigned to a responsible owner.
5. Approval is requested when necessary.
6. The request is completed or returned with an explanation.
7. The outcome is recorded and communicated to the student.

## 4. Evidence and Assumptions

This submission uses a hypothetical walkthrough. No official college process observation or staff interview has been confirmed. Timings and request volumes are illustrative estimates, not measured college data.

## 5. Synthetic Test Cases

Five scenarios are considered:

* Normal request
* Missing information
* Duplicate request
* Unauthorized request
* Failed workflow step

Expected outcomes and recovery actions are documented in `test-cases.csv`.

## 6. Time-Saving Estimate

The illustrative calculation estimates potential net time saved after accounting for review and support effort. See `time-saved.md`. Actual savings require validation using an approved sample of real process timings.

## 7. Supporting Files

* `workflow.mmd` — proposed workflow diagram
* `evidence-log.md` — evidence status, assumptions, and limitations
* `test-cases.csv` — five synthetic test cases
* `time-saved.md` — estimated effort and potential net time savings

## 8. Risks and Limitations

* The existing ICFAI process has not been verified.
* The estimated workload and timings may differ from reality.
* Requests involving approvals must remain with authorized decision-makers.
* Personal and confidential student information must not be collected for this exercise.
* The proposal should be revised if an approved walkthrough shows that the assumed handoffs or bottlenecks do not exist.

## 9. Conclusion

Campus Loop demonstrates how clear ownership, status tracking, approval boundaries, and failure recovery could improve a student-request workflow. It is a proposal for evaluation, not a production system or an official ICFAI process.

**Author:** Kanuru Sai Aditya
**Programme:** B.Tech Computer Science and Engineering
**College:** IFHE Hyderabad
