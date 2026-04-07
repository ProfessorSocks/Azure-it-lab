# Conditional Access Login Failure Scenario

## Scenario

A user was unable to log in even after:

- password reset
- confirming correct username
- verifying MFA was working
- confirming the account was not blocked

## Troubleshooting Approach

At this stage, basic authentication issues were ruled out.

The next step was to review sign-in logs to identify the exact failure reason.

## Key Finding

The sign-in logs indicated that access was blocked by a Conditional Access policy.

## What This Means

Conditional Access policies enforce rules such as:

- requiring specific devices
- restricting access by location
- enforcing security conditions

Even if user credentials are correct, login can still fail if these conditions are not met.

## Resolution Approach

- Review the conditional access policy requirements
- Determine which condition is not satisfied
- Adjust the policy or guide the user to meet the requirements

## Lesson Learned

Not all login failures are caused by user error or credentials. Policies and environment conditions can prevent access even when everything appears correct.

## IT Support Relevance

This scenario reflects real-world escalation cases where basic troubleshooting does not resolve the issue. Understanding conditional access is key to diagnosing advanced login problems.
