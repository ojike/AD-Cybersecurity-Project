# Securing Active Directory

## Security Measures

### Password Policies
1. **Configure Password Policies:**
   - Open Group Policy Management.
   - Navigate to `Default Domain Policy`.
   - Edit the policy to enforce strong password requirements (e.g., minimum length, complexity).

### Account Lockout Policies
1. **Configure Account Lockout Policies:**
   - In Group Policy Management, navigate to `Default Domain Policy`.
   - Edit the policy to set account lockout thresholds and durations.

### Administrative Accounts
1. **Secure Administrative Accounts:**
   - Create separate accounts for administrative tasks.
   - Remove unnecessary administrative privileges from regular user accounts.
   - Enable multi-factor authentication for administrative accounts.

### Group Policies
1. **Implement Group Policies:**
   - Define and apply group policies to enforce security settings across the domain.
   - Examples include disabling unnecessary services, configuring firewall settings, and enforcing software restrictions.

### Audit Policies
1. **Configure Audit Policies:**
   - In Group Policy Management, navigate to `Default Domain Policy`.
   - Enable auditing for account logon events, object access, and policy changes.

### Security Updates
1. **Apply Security Updates:**
   - Regularly update Windows Server and client machines.
   - Use Windows Update or WSUS to manage updates.
