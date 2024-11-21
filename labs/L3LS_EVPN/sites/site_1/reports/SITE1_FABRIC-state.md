# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 368 | 368 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| s1-brdr1 |  51 | 51 | 0 | - |
| s1-brdr2 |  51 | 51 | 0 | - |
| s1-leaf1 |  50 | 50 | 0 | - |
| s1-leaf2 |  50 | 50 | 0 | - |
| s1-leaf3 |  50 | 50 | 0 | - |
| s1-leaf4 |  50 | 50 | 0 | - |
| s1-spine1 |  33 | 33 | 0 | - |
| s1-spine2 |  33 | 33 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  8 | 8 | 0 |
| Interface State |  114 | 114 | 0 |
| LLDP Topology |  36 | 36 | 0 |
| MLAG |  6 | 6 | 0 |
| IP Reachability |  24 | 24 | 0 |
| BGP |  66 | 66 | 0 |
| Routing Table |  66 | 66 | 0 |
| Loopback0 Reachability |  48 | 48 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | s1-brdr1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | s1-brdr2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | s1-leaf1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | s1-leaf2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | s1-leaf3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | s1-leaf4 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | s1-spine1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | s1-spine2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 9 | s1-brdr1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_s1-brdr2_Ethernet1 | PASS | - |
| 10 | s1-brdr1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - MLAG_PEER_s1-brdr2_Ethernet6 | PASS | - |
| 11 | s1-brdr1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-SPINE1_Ethernet7 | PASS | - |
| 12 | s1-brdr1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-SPINE2_Ethernet7 | PASS | - |
| 13 | s1-brdr1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_s2-brdr1_Ethernet4 | PASS | - |
| 14 | s1-brdr2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_s1-brdr1_Ethernet1 | PASS | - |
| 15 | s1-brdr2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - MLAG_PEER_s1-brdr1_Ethernet6 | PASS | - |
| 16 | s1-brdr2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-SPINE1_Ethernet8 | PASS | - |
| 17 | s1-brdr2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-SPINE2_Ethernet8 | PASS | - |
| 18 | s1-brdr2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_s2-brdr2_Ethernet5 | PASS | - |
| 19 | s1-leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_s1-leaf2_Ethernet1 | PASS | - |
| 20 | s1-leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - MLAG_PEER_s1-leaf2_Ethernet6 | PASS | - |
| 21 | s1-leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-SPINE1_Ethernet2 | PASS | - |
| 22 | s1-leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-SPINE2_Ethernet2 | PASS | - |
| 23 | s1-leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - s1-host1_eth1 | PASS | - |
| 24 | s1-leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_s1-leaf1_Ethernet1 | PASS | - |
| 25 | s1-leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - MLAG_PEER_s1-leaf1_Ethernet6 | PASS | - |
| 26 | s1-leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-SPINE1_Ethernet3 | PASS | - |
| 27 | s1-leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-SPINE2_Ethernet3 | PASS | - |
| 28 | s1-leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - s1-host1_eth2 | PASS | - |
| 29 | s1-leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_s1-leaf4_Ethernet1 | PASS | - |
| 30 | s1-leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - MLAG_PEER_s1-leaf4_Ethernet6 | PASS | - |
| 31 | s1-leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-SPINE1_Ethernet4 | PASS | - |
| 32 | s1-leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-SPINE2_Ethernet4 | PASS | - |
| 33 | s1-leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - s1-host2_eth1 | PASS | - |
| 34 | s1-leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_s1-leaf3_Ethernet1 | PASS | - |
| 35 | s1-leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - MLAG_PEER_s1-leaf3_Ethernet6 | PASS | - |
| 36 | s1-leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-SPINE1_Ethernet5 | PASS | - |
| 37 | s1-leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-SPINE2_Ethernet5 | PASS | - |
| 38 | s1-leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - s1-host2_eth2 | PASS | - |
| 39 | s1-spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-LEAF1_Ethernet2 | PASS | - |
| 40 | s1-spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-LEAF2_Ethernet2 | PASS | - |
| 41 | s1-spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_S1-LEAF3_Ethernet2 | PASS | - |
| 42 | s1-spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_S1-LEAF4_Ethernet2 | PASS | - |
| 43 | s1-spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_S1-BRDR1_Ethernet2 | PASS | - |
| 44 | s1-spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet8 - P2P_LINK_TO_S1-BRDR2_Ethernet2 | PASS | - |
| 45 | s1-spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_S1-LEAF1_Ethernet3 | PASS | - |
| 46 | s1-spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_S1-LEAF2_Ethernet3 | PASS | - |
| 47 | s1-spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_S1-LEAF3_Ethernet3 | PASS | - |
| 48 | s1-spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_S1-LEAF4_Ethernet3 | PASS | - |
| 49 | s1-spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_S1-BRDR1_Ethernet3 | PASS | - |
| 50 | s1-spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet8 - P2P_LINK_TO_S1-BRDR2_Ethernet3 | PASS | - |
| 51 | s1-brdr1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_s1-brdr2_Po1 | PASS | - |
| 52 | s1-brdr2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_s1-brdr1_Po1 | PASS | - |
| 53 | s1-leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_s1-leaf2_Po1 | PASS | - |
| 54 | s1-leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel4 - s1-host1 | PASS | - |
| 55 | s1-leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_s1-leaf1_Po1 | PASS | - |
| 56 | s1-leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel4 - s1-host1 | PASS | - |
| 57 | s1-leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_s1-leaf4_Po1 | PASS | - |
| 58 | s1-leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel4 - s1-host2 | PASS | - |
| 59 | s1-leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_s1-leaf3_Po1 | PASS | - |
| 60 | s1-leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel4 - s1-host2 | PASS | - |
| 61 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 62 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 63 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Ten | PASS | - |
| 64 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Twenty | PASS | - |
| 65 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Thirty | PASS | - |
| 66 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - Forty | PASS | - |
| 67 | s1-brdr1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf OVERLAY | PASS | - |
| 68 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 69 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 70 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Ten | PASS | - |
| 71 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Twenty | PASS | - |
| 72 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Thirty | PASS | - |
| 73 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - Forty | PASS | - |
| 74 | s1-brdr2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf OVERLAY | PASS | - |
| 75 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 76 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 77 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Ten | PASS | - |
| 78 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Twenty | PASS | - |
| 79 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Thirty | PASS | - |
| 80 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - Forty | PASS | - |
| 81 | s1-leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf OVERLAY | PASS | - |
| 82 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 83 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 84 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Ten | PASS | - |
| 85 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Twenty | PASS | - |
| 86 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Thirty | PASS | - |
| 87 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - Forty | PASS | - |
| 88 | s1-leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf OVERLAY | PASS | - |
| 89 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 90 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 91 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Ten | PASS | - |
| 92 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Twenty | PASS | - |
| 93 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Thirty | PASS | - |
| 94 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - Forty | PASS | - |
| 95 | s1-leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf OVERLAY | PASS | - |
| 96 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 97 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 98 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - Ten | PASS | - |
| 99 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Twenty | PASS | - |
| 100 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan30 - Thirty | PASS | - |
| 101 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan40 - Forty | PASS | - |
| 102 | s1-leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf OVERLAY | PASS | - |
| 103 | s1-brdr1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 104 | s1-brdr2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 105 | s1-leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 106 | s1-leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 107 | s1-leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 108 | s1-leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 109 | s1-brdr1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 110 | s1-brdr1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 111 | s1-brdr2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 112 | s1-brdr2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 113 | s1-leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 114 | s1-leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 115 | s1-leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 116 | s1-leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 117 | s1-leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 118 | s1-leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 119 | s1-leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 120 | s1-leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 121 | s1-spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 122 | s1-spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 123 | s1-brdr1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: s1-brdr2_Ethernet1 | PASS | - |
| 124 | s1-brdr1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: s1-brdr2_Ethernet6 | PASS | - |
| 125 | s1-brdr1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-spine1_Ethernet7 | PASS | - |
| 126 | s1-brdr1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-spine2_Ethernet7 | PASS | - |
| 127 | s1-brdr2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: s1-brdr1_Ethernet1 | PASS | - |
| 128 | s1-brdr2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: s1-brdr1_Ethernet6 | PASS | - |
| 129 | s1-brdr2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-spine1_Ethernet8 | PASS | - |
| 130 | s1-brdr2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-spine2_Ethernet8 | PASS | - |
| 131 | s1-leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: s1-leaf2_Ethernet1 | PASS | - |
| 132 | s1-leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: s1-leaf2_Ethernet6 | PASS | - |
| 133 | s1-leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-spine1_Ethernet2 | PASS | - |
| 134 | s1-leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-spine2_Ethernet2 | PASS | - |
| 135 | s1-leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: s1-leaf1_Ethernet1 | PASS | - |
| 136 | s1-leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: s1-leaf1_Ethernet6 | PASS | - |
| 137 | s1-leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-spine1_Ethernet3 | PASS | - |
| 138 | s1-leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-spine2_Ethernet3 | PASS | - |
| 139 | s1-leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: s1-leaf4_Ethernet1 | PASS | - |
| 140 | s1-leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: s1-leaf4_Ethernet6 | PASS | - |
| 141 | s1-leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-spine1_Ethernet4 | PASS | - |
| 142 | s1-leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-spine2_Ethernet4 | PASS | - |
| 143 | s1-leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: s1-leaf3_Ethernet1 | PASS | - |
| 144 | s1-leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: s1-leaf3_Ethernet6 | PASS | - |
| 145 | s1-leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-spine1_Ethernet5 | PASS | - |
| 146 | s1-leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-spine2_Ethernet5 | PASS | - |
| 147 | s1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-leaf1_Ethernet2 | PASS | - |
| 148 | s1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-leaf2_Ethernet2 | PASS | - |
| 149 | s1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: s1-leaf3_Ethernet2 | PASS | - |
| 150 | s1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: s1-leaf4_Ethernet2 | PASS | - |
| 151 | s1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: s1-brdr1_Ethernet2 | PASS | - |
| 152 | s1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: s1-brdr2_Ethernet2 | PASS | - |
| 153 | s1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: s1-leaf1_Ethernet3 | PASS | - |
| 154 | s1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: s1-leaf2_Ethernet3 | PASS | - |
| 155 | s1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: s1-leaf3_Ethernet3 | PASS | - |
| 156 | s1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: s1-leaf4_Ethernet3 | PASS | - |
| 157 | s1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: s1-brdr1_Ethernet3 | PASS | - |
| 158 | s1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: s1-brdr2_Ethernet3 | PASS | - |
| 159 | s1-brdr1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 160 | s1-brdr2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 161 | s1-leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 162 | s1-leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 163 | s1-leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 164 | s1-leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 165 | s1-brdr1 | IP Reachability | ip reachability test p2p links | Source: s1-brdr1_Ethernet2 - Destination: s1-spine1_Ethernet7 | PASS | - |
| 166 | s1-brdr1 | IP Reachability | ip reachability test p2p links | Source: s1-brdr1_Ethernet3 - Destination: s1-spine2_Ethernet7 | PASS | - |
| 167 | s1-brdr2 | IP Reachability | ip reachability test p2p links | Source: s1-brdr2_Ethernet2 - Destination: s1-spine1_Ethernet8 | PASS | - |
| 168 | s1-brdr2 | IP Reachability | ip reachability test p2p links | Source: s1-brdr2_Ethernet3 - Destination: s1-spine2_Ethernet8 | PASS | - |
| 169 | s1-leaf1 | IP Reachability | ip reachability test p2p links | Source: s1-leaf1_Ethernet2 - Destination: s1-spine1_Ethernet2 | PASS | - |
| 170 | s1-leaf1 | IP Reachability | ip reachability test p2p links | Source: s1-leaf1_Ethernet3 - Destination: s1-spine2_Ethernet2 | PASS | - |
| 171 | s1-leaf2 | IP Reachability | ip reachability test p2p links | Source: s1-leaf2_Ethernet2 - Destination: s1-spine1_Ethernet3 | PASS | - |
| 172 | s1-leaf2 | IP Reachability | ip reachability test p2p links | Source: s1-leaf2_Ethernet3 - Destination: s1-spine2_Ethernet3 | PASS | - |
| 173 | s1-leaf3 | IP Reachability | ip reachability test p2p links | Source: s1-leaf3_Ethernet2 - Destination: s1-spine1_Ethernet4 | PASS | - |
| 174 | s1-leaf3 | IP Reachability | ip reachability test p2p links | Source: s1-leaf3_Ethernet3 - Destination: s1-spine2_Ethernet4 | PASS | - |
| 175 | s1-leaf4 | IP Reachability | ip reachability test p2p links | Source: s1-leaf4_Ethernet2 - Destination: s1-spine1_Ethernet5 | PASS | - |
| 176 | s1-leaf4 | IP Reachability | ip reachability test p2p links | Source: s1-leaf4_Ethernet3 - Destination: s1-spine2_Ethernet5 | PASS | - |
| 177 | s1-spine1 | IP Reachability | ip reachability test p2p links | Source: s1-spine1_Ethernet2 - Destination: s1-leaf1_Ethernet2 | PASS | - |
| 178 | s1-spine1 | IP Reachability | ip reachability test p2p links | Source: s1-spine1_Ethernet3 - Destination: s1-leaf2_Ethernet2 | PASS | - |
| 179 | s1-spine1 | IP Reachability | ip reachability test p2p links | Source: s1-spine1_Ethernet4 - Destination: s1-leaf3_Ethernet2 | PASS | - |
| 180 | s1-spine1 | IP Reachability | ip reachability test p2p links | Source: s1-spine1_Ethernet5 - Destination: s1-leaf4_Ethernet2 | PASS | - |
| 181 | s1-spine1 | IP Reachability | ip reachability test p2p links | Source: s1-spine1_Ethernet7 - Destination: s1-brdr1_Ethernet2 | PASS | - |
| 182 | s1-spine1 | IP Reachability | ip reachability test p2p links | Source: s1-spine1_Ethernet8 - Destination: s1-brdr2_Ethernet2 | PASS | - |
| 183 | s1-spine2 | IP Reachability | ip reachability test p2p links | Source: s1-spine2_Ethernet2 - Destination: s1-leaf1_Ethernet3 | PASS | - |
| 184 | s1-spine2 | IP Reachability | ip reachability test p2p links | Source: s1-spine2_Ethernet3 - Destination: s1-leaf2_Ethernet3 | PASS | - |
| 185 | s1-spine2 | IP Reachability | ip reachability test p2p links | Source: s1-spine2_Ethernet4 - Destination: s1-leaf3_Ethernet3 | PASS | - |
| 186 | s1-spine2 | IP Reachability | ip reachability test p2p links | Source: s1-spine2_Ethernet5 - Destination: s1-leaf4_Ethernet3 | PASS | - |
| 187 | s1-spine2 | IP Reachability | ip reachability test p2p links | Source: s1-spine2_Ethernet7 - Destination: s1-brdr1_Ethernet3 | PASS | - |
| 188 | s1-spine2 | IP Reachability | ip reachability test p2p links | Source: s1-spine2_Ethernet8 - Destination: s1-brdr2_Ethernet3 | PASS | - |
| 189 | s1-brdr1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 190 | s1-brdr2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 191 | s1-leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 192 | s1-leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 193 | s1-leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 194 | s1-leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 195 | s1-spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 196 | s1-spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 197 | s1-brdr1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.252.1.9 | PASS | - |
| 198 | s1-brdr1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.16 | PASS | - |
| 199 | s1-brdr1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.18 | PASS | - |
| 200 | s1-brdr1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.255.1 | PASS | - |
| 201 | s1-brdr2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.252.1.8 | PASS | - |
| 202 | s1-brdr2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.20 | PASS | - |
| 203 | s1-brdr2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.22 | PASS | - |
| 204 | s1-brdr2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.255.3 | PASS | - |
| 205 | s1-leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.252.1.1 | PASS | - |
| 206 | s1-leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.0 | PASS | - |
| 207 | s1-leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.2 | PASS | - |
| 208 | s1-leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.252.1.0 | PASS | - |
| 209 | s1-leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.4 | PASS | - |
| 210 | s1-leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.6 | PASS | - |
| 211 | s1-leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.252.1.5 | PASS | - |
| 212 | s1-leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.8 | PASS | - |
| 213 | s1-leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.10 | PASS | - |
| 214 | s1-leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.252.1.4 | PASS | - |
| 215 | s1-leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.12 | PASS | - |
| 216 | s1-leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.14 | PASS | - |
| 217 | s1-spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.1 | PASS | - |
| 218 | s1-spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.5 | PASS | - |
| 219 | s1-spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.9 | PASS | - |
| 220 | s1-spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.13 | PASS | - |
| 221 | s1-spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.17 | PASS | - |
| 222 | s1-spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.21 | PASS | - |
| 223 | s1-spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.3 | PASS | - |
| 224 | s1-spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.7 | PASS | - |
| 225 | s1-spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.11 | PASS | - |
| 226 | s1-spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.15 | PASS | - |
| 227 | s1-spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.19 | PASS | - |
| 228 | s1-spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.16.1.23 | PASS | - |
| 229 | s1-brdr1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.1 | PASS | - |
| 230 | s1-brdr1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.2 | PASS | - |
| 231 | s1-brdr1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.2.7 | PASS | - |
| 232 | s1-brdr2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.1 | PASS | - |
| 233 | s1-brdr2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.2 | PASS | - |
| 234 | s1-brdr2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.2.8 | PASS | - |
| 235 | s1-leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.1 | PASS | - |
| 236 | s1-leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.2 | PASS | - |
| 237 | s1-leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.1 | PASS | - |
| 238 | s1-leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.2 | PASS | - |
| 239 | s1-leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.1 | PASS | - |
| 240 | s1-leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.2 | PASS | - |
| 241 | s1-leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.1 | PASS | - |
| 242 | s1-leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.2 | PASS | - |
| 243 | s1-spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.7 | PASS | - |
| 244 | s1-spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.8 | PASS | - |
| 245 | s1-spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.3 | PASS | - |
| 246 | s1-spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.4 | PASS | - |
| 247 | s1-spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.5 | PASS | - |
| 248 | s1-spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.6 | PASS | - |
| 249 | s1-spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.7 | PASS | - |
| 250 | s1-spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.8 | PASS | - |
| 251 | s1-spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.3 | PASS | - |
| 252 | s1-spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.4 | PASS | - |
| 253 | s1-spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.5 | PASS | - |
| 254 | s1-spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 10.250.1.6 | PASS | - |
| 255 | s1-brdr1 | Routing Table | Remote VTEP address | 10.255.1.7 | PASS | - |
| 256 | s1-brdr1 | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 257 | s1-brdr1 | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 258 | s1-brdr2 | Routing Table | Remote VTEP address | 10.255.1.7 | PASS | - |
| 259 | s1-brdr2 | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 260 | s1-brdr2 | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 261 | s1-leaf1 | Routing Table | Remote VTEP address | 10.255.1.7 | PASS | - |
| 262 | s1-leaf1 | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 263 | s1-leaf1 | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 264 | s1-leaf2 | Routing Table | Remote VTEP address | 10.255.1.7 | PASS | - |
| 265 | s1-leaf2 | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 266 | s1-leaf2 | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 267 | s1-leaf3 | Routing Table | Remote VTEP address | 10.255.1.7 | PASS | - |
| 268 | s1-leaf3 | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 269 | s1-leaf3 | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 270 | s1-leaf4 | Routing Table | Remote VTEP address | 10.255.1.7 | PASS | - |
| 271 | s1-leaf4 | Routing Table | Remote VTEP address | 10.255.1.3 | PASS | - |
| 272 | s1-leaf4 | Routing Table | Remote VTEP address | 10.255.1.5 | PASS | - |
| 273 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.7 | PASS | - |
| 274 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.8 | PASS | - |
| 275 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.3 | PASS | - |
| 276 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.4 | PASS | - |
| 277 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.5 | PASS | - |
| 278 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.6 | PASS | - |
| 279 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.1 | PASS | - |
| 280 | s1-brdr1 | Routing Table | Remote Lo0 address | 10.250.1.2 | PASS | - |
| 281 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.7 | PASS | - |
| 282 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.8 | PASS | - |
| 283 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.3 | PASS | - |
| 284 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.4 | PASS | - |
| 285 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.5 | PASS | - |
| 286 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.6 | PASS | - |
| 287 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.1 | PASS | - |
| 288 | s1-brdr2 | Routing Table | Remote Lo0 address | 10.250.1.2 | PASS | - |
| 289 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.7 | PASS | - |
| 290 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.8 | PASS | - |
| 291 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.3 | PASS | - |
| 292 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.4 | PASS | - |
| 293 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.5 | PASS | - |
| 294 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.6 | PASS | - |
| 295 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.1 | PASS | - |
| 296 | s1-leaf1 | Routing Table | Remote Lo0 address | 10.250.1.2 | PASS | - |
| 297 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.7 | PASS | - |
| 298 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.8 | PASS | - |
| 299 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.3 | PASS | - |
| 300 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.4 | PASS | - |
| 301 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.5 | PASS | - |
| 302 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.6 | PASS | - |
| 303 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.1 | PASS | - |
| 304 | s1-leaf2 | Routing Table | Remote Lo0 address | 10.250.1.2 | PASS | - |
| 305 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.7 | PASS | - |
| 306 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.8 | PASS | - |
| 307 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.3 | PASS | - |
| 308 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.4 | PASS | - |
| 309 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.5 | PASS | - |
| 310 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.6 | PASS | - |
| 311 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.1 | PASS | - |
| 312 | s1-leaf3 | Routing Table | Remote Lo0 address | 10.250.1.2 | PASS | - |
| 313 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.7 | PASS | - |
| 314 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.8 | PASS | - |
| 315 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.3 | PASS | - |
| 316 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.4 | PASS | - |
| 317 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.5 | PASS | - |
| 318 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.6 | PASS | - |
| 319 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.1 | PASS | - |
| 320 | s1-leaf4 | Routing Table | Remote Lo0 address | 10.250.1.2 | PASS | - |
| 321 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.7 | PASS | - |
| 322 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.8 | PASS | - |
| 323 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.3 | PASS | - |
| 324 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.4 | PASS | - |
| 325 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.5 | PASS | - |
| 326 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.6 | PASS | - |
| 327 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.1 | PASS | - |
| 328 | s1-brdr1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr1 - 10.250.1.7 Destination: 10.250.1.2 | PASS | - |
| 329 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.7 | PASS | - |
| 330 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.8 | PASS | - |
| 331 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.3 | PASS | - |
| 332 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.4 | PASS | - |
| 333 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.5 | PASS | - |
| 334 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.6 | PASS | - |
| 335 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.1 | PASS | - |
| 336 | s1-brdr2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-brdr2 - 10.250.1.8 Destination: 10.250.1.2 | PASS | - |
| 337 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.7 | PASS | - |
| 338 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.8 | PASS | - |
| 339 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.3 | PASS | - |
| 340 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.4 | PASS | - |
| 341 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.5 | PASS | - |
| 342 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.6 | PASS | - |
| 343 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.1 | PASS | - |
| 344 | s1-leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf1 - 10.250.1.3 Destination: 10.250.1.2 | PASS | - |
| 345 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.7 | PASS | - |
| 346 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.8 | PASS | - |
| 347 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.3 | PASS | - |
| 348 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.4 | PASS | - |
| 349 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.5 | PASS | - |
| 350 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.6 | PASS | - |
| 351 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.1 | PASS | - |
| 352 | s1-leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf2 - 10.250.1.4 Destination: 10.250.1.2 | PASS | - |
| 353 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.7 | PASS | - |
| 354 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.8 | PASS | - |
| 355 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.3 | PASS | - |
| 356 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.4 | PASS | - |
| 357 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.5 | PASS | - |
| 358 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.6 | PASS | - |
| 359 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.1 | PASS | - |
| 360 | s1-leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf3 - 10.250.1.5 Destination: 10.250.1.2 | PASS | - |
| 361 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.7 | PASS | - |
| 362 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.8 | PASS | - |
| 363 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.3 | PASS | - |
| 364 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.4 | PASS | - |
| 365 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.5 | PASS | - |
| 366 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.6 | PASS | - |
| 367 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.1 | PASS | - |
| 368 | s1-leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: s1-leaf4 - 10.250.1.6 Destination: 10.250.1.2 | PASS | - |