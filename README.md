# CVE-2024-21107
Oracle VM VirtualBox for Windows prior to 7.0.16 - Elevation of Privileges

### Description:
A vulnerability has been identified in Oracle VM VirtualBox on Windows where the setup fails to set proper access rights for its installation folder if a non-default installation path was chosen during installation. This allows any authenticated local attacker to inject arbitrary code and escalate privileges to the SYSTEM context.

### Affected versions
Oracle VM VirtualBox up to 7.0.14

fixed starting with 7.0.16

### Impacted service(s)
Service Name: VBoxSDS (non-default installation path)

#### Discovered by: 
* Alaa Kachouh
* Ali Jammal of Deloitte Netherlands

