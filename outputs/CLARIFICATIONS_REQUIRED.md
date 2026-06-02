# CLARIFICATIONS REQUIRED

1. Confirm complete mandatory field list for Add New User form.
2. Confirm username rules (allowed characters, min/max length, case sensitivity).
3. Confirm password policy (complexity, expiry, history, first-login reset).
4. Confirm exact semantics of note: "button enabled only if selected user was previously blocked".
5. Confirm exact maximum failed-login count that enables Reset Password button.
6. Confirm all Blocker Type values and whether remarks are mandatory per reason.
7. Confirm additional access row mandatory/optional fields (especially Reporting To, On Behalf Of, Remarks).
8. Confirm notification channel/lead-time/retry behavior for additional-role expiry reminder.
9. Confirm whether overlapping additional-role timelines are allowed for same user.
10. Confirm expected behavior for integration failures (retry count, timeout, duplicate prevention).
11. Confirm exact validation/error message text catalog expected in UI.
12. Confirm audit logging requirements for create/edit/block/unblock/reset/role assignment events.

## Assumptions used

- Standard enterprise field, duplicate, boundary, date-range, and role-permission validations are enforced.
- Save/Push operations display success and error feedback and prevent duplicate submission.
- Role-based permissions are enforced at UI and backend authorization levels.
- Additional role status auto-transitions based on From/To timeline.
- Reminder notifications are generated before role expiry.
