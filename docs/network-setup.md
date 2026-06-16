# Network Setup Documentation

## Equipment

| Device | Model | Role |
|---|---|---|
| Switch 1 | Allied Telesyn CentreCOM FH724SW | 24-port patch switch |
| Switch 2 | Cisco 2500 Series | Core lab switch |
| Switch 3 | Cisco 2500 Series | Redundant / secondary |
| Switch 4 | Cisco Catalyst 1900 Series | Access layer switch |

## Port Status Summary

| Device | Status | Notes |
|---|---|---|
| CentreCOM FH724SW | Partial | Ports 4, 8, 12 disabled |
| Cisco 2500 (Unit 1) | Operational | W ON — verified |
| Cisco 2500 (Unit 2) | Operational | W ON — verified |
| Cisco Catalyst 1900 | Operational | ALL PORTS OK |

## Network Services Configured

- **DHCP:** Automatic IP address assignment for lab workstations
- **DNS:** Local name resolution configured
- **VLANs:** Network segments created for lab isolation

## Network Testing Performed

- Ping tests between all deployed workstations
- `ipconfig /all` output verified on each machine
- Port-by-port physical verification on each switch
- Connectivity confirmed between workstations and network services
