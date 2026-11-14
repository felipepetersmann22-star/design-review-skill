# Applied examples

These are fictional scenarios, not evidence of a real product or a universal visual template.

## A crowded task workspace

**Request:** Review a task list on desktop and mobile. The actual list is preceded by three repeated summary boxes, and long task names run under action buttons at a narrow width.

**Finding:** On the narrow task list, long names overlap the action area. A person cannot reliably read the task or identify its action. Let the text wrap and reserve the action's own space, then inspect long and short names at the affected widths. Separately, the repeated summaries dominate the first view while adding no new decision: remove or consolidate them if their information is already available in the list.

**Validation:** Re-render populated and empty states with representative names; verify keyboard focus and primary actions if the UI is interactive. Mark saving and reload continuity unverified unless exercised.

## An expressive product page

**Request:** Review a page whose large headline and gradient convey a deliberate visual identity. Equal cards present comparable plans.

**Judgment:** Do not prescribe a neutral palette or eliminate equal cards merely because those features are familiar. If the headline obscures the actual offer, clarify the copy or hierarchy while retaining the chosen treatment. If plan descriptions differ in length, check alignment and wrapping. Verify the plan links actually work before calling the flow complete.

## An unfinished form

**Request:** Improve a registration dialog that shows an error after submission.

**Finding:** If an observed keyboard pass shows focus disappearing when the dialog opens or closes, identify the exact sequence and affected control. Provide appropriate modal focus behavior and return focus on dismissal. If the submitted values are lost on error, retain them and associate the error with the relevant field.

**Validation:** Exercise keyboard open, field navigation, invalid submit, correction, dismiss and reopen. Check narrow and short viewports. A screenshot of the dialog alone cannot prove these behaviors, submission persistence or backend delivery.
