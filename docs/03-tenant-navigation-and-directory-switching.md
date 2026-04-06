# Tenant Navigation and Directory Switching

## Problem

After entering Microsoft Entra ID, I did not initially see the expected Users section. Instead, I only saw Managed Tenants.

This made it look like user management was unavailable.

## Cause

The issue was that I was not in the correct directory context. I was viewing a management-focused section instead of the actual tenant where user objects were available.

## Fix

I navigated to the correct tenant/directory and then returned to Microsoft Entra ID.

After switching to the correct tenant, the Users section became visible.

## Lesson Learned

This was an important troubleshooting moment because it demonstrated that the problem was not a lack of capability in the platform, but a context issue.

In Microsoft administration, being in the wrong tenant or directory can make it appear that users, roles, or resources are missing even when they exist.

## IT Support Relevance

This is relevant to real-world support because admins and technicians often work across multiple environments, tenants, or portals. One of the first things to verify is whether the current tenant or directory is the correct one.
