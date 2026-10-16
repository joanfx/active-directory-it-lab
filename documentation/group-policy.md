# Group Policy

Created and deployed an account lockout policy through Group Policy.

## Policy Settings

- Lockout duration: 15 minutes
- Lockout threshold: 5 invalid attempts
- Reset counter: 15 minutes

![Account Lockout GPO](../screenshots/08-account-lockout-gpo.png)

## Client Verification

Verified that CLIENT01 successfully received the domain policy.

![GPO Applied](../screenshots/09-gpo-applied-client01.png)