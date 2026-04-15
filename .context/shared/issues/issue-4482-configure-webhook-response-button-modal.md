# #4482: Add "Configure Response" button and modal to the trigger form

[Github](https://github.com/OpenFn/lightning/issues/4482)

**Status:** open
**Created:** 2026-03-04T08:52:25Z
**Updated:** 2026-03-04T14:25:28Z
**Assignee:** None
**Labels:** configurable webhook responses

### User story
When Sync mode is selected in the trigger form, a "Configure Response" button should appear. Clicking it opens the "Configure Webhook Response" modal.

For the modal: The title should be "Configure Webhook Response" and the subtitle "Set the status code and body returned by this webhook." The four fields are styled text inputs (monospace/code font, dark background) — not full code editor instances.

### User acceptance criteria

1. "Configure Response" button is visible only when Sync mode is selected.
2. Clicking the button opens the modal.
3. Modal title and subtitle match the spec exactly.
4. All four fields render with grey placeholder text showing their defaults.
5. Entering a value makes the text white and shows the clear button.
6. Clear button resets the field to empty (restoring the placeholder).
7. Save writes all four values to the trigger doc.
8. Cancel discards changes.
9. Button and modal do not appear when Async mode is selected.
