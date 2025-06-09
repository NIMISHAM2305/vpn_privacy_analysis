# vpn_privacy_analysis
Cybersecurity Internship Task 8:Working and understanding VPN

# VPN Analysis & Leak Test Report

## ✅ Tasks Performed

### 🔐 1. Connected to VPN using Windscribe
- Selected “Best Location” using **WireGuard protocol**
- Location assigned: **Victoria, Hong Kong**
- Verified IP masking successfully

📸 Screenshot: [`vpn_connection_status.png`](./vpn_connection_status.png)

---

### 📶 2. Internet Speed Test (With & Without VPN)
- Compared internet speeds with VPN ON vs OFF using **Fast.com**
- Observed significant speed drop due to encryption overhead

| State       | Speed      |
|-------------|------------|
| VPN OFF     | 34 Mbps    |
| VPN ON      | 700 Kbps   |

📸 Screenshots:
- [`no_vpn_speed.png`](./no_vpn_speed.png)
- [`vpn_speed.png`](./vpn_speed.png)

---

### 🌐 3. IP Address Verification
- Visited [WhatIsMyIPAddress.com](https://whatismyipaddress.com)
- Verified that real IP was hidden and replaced with a VPN-based IP

📸 Screenshot: [`whatsmyip.png`](./whatsmyip.png)

---

### 🛡️ 4. DNS Leak Test
- Conducted a full DNS leak test using a browser-based tool
- ✅ No DNS leaks found — confirms VPN is protecting DNS queries

📸 Screenshot: [`dns_leak_test_result.png`](./dns_leak_test_result.png)

---

### 📄 Full Report
For detailed explanations, screenshots, protocol breakdown, benefits/limitations, and extra value-added insights, please refer to the attached documentation.

📄 [View Full Report (documentation.pdf)](./documentation.pdf)

---

## ✅ Learnings
- VPNs mask IP addresses and encrypt internet traffic
- DNS leaks can expose real location even if IP is hidden
- VPNs may cause speed drops due to traffic encryption
- Protocol choice (WireGuard, OpenVPN) impacts performance
- Useful for accessing restricted content and staying safe on public networks

---


