# Monitoring and Auditing

## Monitoring Tools

### Windows Event Viewer
1. **Configure Event Viewer:**
   - Use Event Viewer to monitor security logs, application logs, and system logs.
   - Filter logs to identify suspicious activities.

### Sysmon
1. **Install and Configure Sysmon:**
   - Download and install Sysmon from Sysinternals.
   - Configure Sysmon to log detailed information about system activities.

### SIEM Solutions
1. **Implement a SIEM Solution:**
   - Set up a Security Information and Event Management (SIEM) solution (e.g., Splunk, ELK Stack) to aggregate and analyze logs.

## Auditing

### Enable Auditing Policies
1. **Configure Audit Policies:**
   - In Group Policy Management, navigate to `Default Domain Policy`.
   - Enable auditing for account logon events, object access, and policy changes.

### Review Audit Logs
1. **Regularly Review Audit Logs:**
   - Periodically review audit logs for signs of unauthorized access or policy violations.
