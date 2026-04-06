# Password Reset Troubleshooting

## Scenario

I wanted to practice password reset workflows in Microsoft Entra ID as part of a basic help desk lab.

## What I Observed

I confirmed that my account showed Global Administrator access plus at least one additional role. However, I still could not access the expected password reset functionality for the user I was reviewing.

## Why This Matters

Password resets are one of the most common help desk tasks, so this was an important workflow to investigate.

## Possible Causes Considered

- I may have been viewing the user through the wrong interface or blade
- The user object may not have been the type I expected
- The role assignment may not have fully reflected in the current session
- The portal UI may have limited or hidden the action in the current path

## Troubleshooting Approach

To troubleshoot this, I considered the following steps:

1. Verify that I am in the correct tenant
2. Verify that the account truly has Global Administrator privileges
3. Sign out and sign back in to refresh role application
4. Open the user from the standard Users section in Microsoft Entra ID
5. Check whether the issue is portal-path specific rather than permission-related

## Lessons Learned

This was a useful reminder that administrative capability is not always just about having the role. In cloud portals, the exact view, tenant, object type, and session state can all affect what actions are available.

## IT Support Takeaway

Even when a task seems simple, it is important to verify:

- the correct tenant
- the correct user object
- the correct portal path
- the correct permissions
- the current session state

This is a realistic example of how cloud administration sometimes requires careful troubleshooting rather than assuming the first missing option means the feature is unavailable.
