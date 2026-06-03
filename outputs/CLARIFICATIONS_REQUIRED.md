# Clarifications Required

1. The exact UI control labels/icons are unclear in multiple steps (for example, action controls before Edit and location assignment button). Please confirm the exact control names.
2. Reminder notification behavior for additional role expiry is described, but notification channel (in-app, email, SMS) and reminder lead time are not specified.
3. Reset Password flow does not define whether the system issues a temporary password, sends a reset link, or forces immediate password change on next login.
4. Mandatory field list for user creation is not explicitly enumerated in the requirement document.

## Assumptions Used

- Positive scenarios were generated using valid data and authorized users.
- Super Admin has unrestricted proposal access across all locations as specified.
- Timeline-based status updates and role activation are system-driven and can be validated with controlled test dates.
