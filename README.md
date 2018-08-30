Windows Event Log XML subscriptions that mimic SwiftOnSecurity's Sysmon config file. Unfortunately a limitation of XPATH 1.0 is that it does not allow wildcard selections so some items were not included.

Keep in mind most of these subscriptions require the necessary Windows auditing to be enabled. They do NOT come out of the box. Use recommendation from [Malware Archaeology](https://static1.squarespace.com/static/552092d5e4b0661088167e5c/t/5aad62bb0e2e725448c6337f/1521312444131/Windows+Advanced+Logging+Cheat+Sheet_ver_Mar_2018_v1.01.pdf) and/or [Palantir](https://github.com/palantir/windows-event-forwarding/tree/master/group-policy-objects).

Contributions:
[Palantir](https://github.com/palantir/windows-event-forwarding) for their work on WEF.
[SwiftOnSecurity's](https://github.com/SwiftOnSecurity/sysmon-config) Sysmon config file.