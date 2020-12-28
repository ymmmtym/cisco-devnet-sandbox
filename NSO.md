# NSO

## Access

- NSO/NCS Host
  - Address: 10.10.20.49
  - Username: developer
  - Password: C1sco12345
  - SSH Port for Linux Host: 22
  - HTTPS Port for NSO GUI/API: 443
  - Example Connection: <https://10.10.20.49>
  - SSH Port for direct NSO access: 2024
  - Example Connection:
  - ssh -p 2024 developer@10.10.20.49
- Devbox
  - Address: 10.10.20.50
  - Username: developer
  - Password: C1sco12345
  - SSH Port: 22
  - RDP Port: 3389

## Devices

|    Component    |  Type  |  IP Address  | Method |  Credentials  |
|:---------------:|:------:|:------------:|:------:|:-------------:|
| internet-host01 | Linux  | 10.10.20.182 | SSH    | cisco / cisco |
| internet-rtr01  | IOS XE | 10.10.20.181 | TELNET | cisco / cisco |
| edge-firewall01 | ASA    | 10.10.20.171 | TELNET | cisco / cisco |
| edge-sw01       | IOS    | 10.10.20.172 | TELNET | cisco / cisco |
| core-rtr01      | IOS XR | 10.10.20.173 | TELNET | cisco / cisco |
| core-rtr02      | IOS XR | 10.10.20.174 | TELNET | cisco / cisco |
| dist-rtr01      | IOS XE | 10.10.20.175 | TELNET | cisco / cisco |
| dist-rtr02      | IOS XE | 10.10.20.176 | TELNET | cisco / cisco |
| dist-sw01       | NX-OS  | 10.10.20.177 | TELNET | cisco / cisco |
| dist-sw02       | NX-OS  | 10.10.20.178 | TELNET | cisco / cisco |
| inside-host01   | Linux  | 10.10.20.179 | SSH    | cisco / cisco |
| inside-host02   | Linux  | 10.10.20.180 | SSH    | cisco / cisco |
