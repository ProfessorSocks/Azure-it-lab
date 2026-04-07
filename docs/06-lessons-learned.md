# Lessons Learned

## 1. Tenant Context Is Critical

One of the biggest takeaways from this lab is that being in the wrong tenant or directory can completely change what is visible and what actions are available.

Initially, I could not see users because I was viewing Managed Tenants instead of the correct directory.

## 2. The Portal Can Be Misleading

The Microsoft Entra interface can make it appear as though features are unavailable when, in reality, the issue is related to navigation or context.

This reinforces the importance of verifying the environment before assuming a feature is missing.

## 3. Roles vs. Capabilities

Even though I had Global Administrator access, I was not immediately able to perform all expected actions (such as password reset).

This highlights that:

- roles must be verified
- permissions may take time to apply
- portal views can affect available actions

## 4. Troubleshooting Is About Process

Instead of assuming something is broken, I learned to follow a structured approach:

- Verify environment (tenant/directory)
- Verify user existence
- Verify permissions and roles
- Verify correct portal path

## 5. Identity Is Foundational

This lab reinforced that identity (users, authentication, permissions) is central to most Microsoft-related IT issues.

Even problems that appear to involve other services often trace back to identity.

## Overall Takeaway

This lab emphasized that successful IT troubleshooting is less about memorizing steps and more about understanding systems, context, and process.
