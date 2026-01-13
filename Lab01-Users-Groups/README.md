
# Lab 01 – User & Group Management

## 🎯 Scenario
Create and manage Linux users and groups following least privilege principles.

## 🎯 Objectives
- Create users and groups
- Assign secondary group membership
- Enforce password change on first login

## 🛠 Steps
1. Create group `it_admins`
2. Create users `ahmed` and `mohamed`
3. Add users to secondary group
4. Set password policy

## ✅ Verification
- `id ahmed`
- `getent group it_admins`
- `/etc/passwd`
