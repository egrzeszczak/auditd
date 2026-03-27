# auditd

Best practice configuration for Linux Audit Daemon (`auditd`) based on [Florian Roth's GitHub repository](https://github.com/Neo23x0/auditd), split into pluggable rule sets.

## Rulesets

|File name|Description|
|-|-|
|[80-custom-initialize.rules](./rulesets/80-custom-initialize.rules)|Initialization of auditd ruleset|
|[81-custom-auditd.rules](./rulesets/81-custom-auditd.rules)|Audit deamon, audit utils usage self-auditing|
|[83-custom-time.rules](./rulesets/83-custom-time.rules)|Rules that will monitor time changes within the operating system|
|[89-custom-finalize.rules](./rulesets/89-custom-finalize.rules)|Finalization of auditd ruleset|

## Additional resources

|Name|Link|
|-|-|
|Gov.uk auditd rules|https://github.com/gds-operations/puppet-auditd/pull/1|
|CentOS 7 hardening|https://highon.coffee/blog/security-harden-centos-7/#auditd---audit-daemon|
|Linux audit repo|https://github.com/linux-audit/audit-userspace/tree/master/rules|
|Auditd high performance linux auditing|https://linux-audit.com/tuning-auditd-high-performance-linux-auditing/|
|PCI DSS compliance|https://github.com/linux-audit/audit-userspace/blob/master/rules/30-pci-dss-v31.rules|
|NISPOM compliance|https://github.com/linux-audit/audit-userspace/blob/master/rules/30-nispom.rules|