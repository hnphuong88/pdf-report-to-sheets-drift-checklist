# Sample Drift Report

Report family: monthly vendor performance
Run date: 2026-07-06
Fixture data: synthetic

## Status

Review needed.

## Findings

- Missing required field value: `net_revenue` for `2026-07`.
- Duplicate report period detected: `2026-06`.
- Gross revenue increased 18.2 percent while order count decreased 7.7 percent.
- Refunds increased more than 150 percent month over month.

## Suggested Actions

1. Confirm the July PDF still contains the `net_revenue` label.
2. Remove or quarantine the duplicate June row before dashboard refresh.
3. Reconcile July gross revenue and refunds against the source PDF.
4. Mark this report family as `layout_review_required` until the next clean run.
