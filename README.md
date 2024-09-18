# Chrome-uBO
# Need to be updated
Reg file without DNS over HTTPS:

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google]

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome]
"ExtensionManifestV2Availability"=dword:00000002

Reg file with DNS over HTTPS:

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google]

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome]
"DnsOverHttpsMode"="automatic"
"DnsOverHttpsTemplates"="https://dns.google/dns-query{?dns}"
"ExtensionManifestV2Availability"=dword:00000002
Note: You can replace the DNS server with something else if you want.

EDGE

Reg file without DNS over HTTPS:

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge]
"ExtensionManifestV2Availability"=dword:00000002
Reg file with DNS over HTTPS:

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge]
"DnsOverHttpsMode"="secure"
"DnsOverHttpsTemplates"="https://dns.google/dns-query{?dns}"
"ExtensionManifestV2Availability"=dword:00000002
For refence
