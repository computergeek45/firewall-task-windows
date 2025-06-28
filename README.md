# firewall-task-windows

# Firewall Configuration Task (Windows)

## Objective
Configure and test basic Windows Firewall rules to block and allow traffic on specific ports (Telnet and SSH).

---

## 🛠 Steps Performed

### Step 1: Opened Windows Firewall (Advanced Security)
- Used the Windows Defender Firewall with Advanced Security tool.

### Step 2: Listed Inbound Rules
- Viewed current inbound and outbound rules.

### Step 3: Blocked Port 23 (Telnet)
- Added an inbound rule to block TCP traffic on port 23.

### Step 4: Tested Telnet Connection
- Installed Telnet Client via Control Panel.
- Tested with `telnet 127.0.0.1 23` → connection was blocked as expected.

###  Step 5: Allowed SSH (Port 22)
- Created a rule to allow inbound TCP traffic on port 22.

### Step 6: Removed Telnet Block Rule
- Deleted the test rule to restore original firewall configuration.

---

## 📸 Screenshots Included

- `step1_firewall_open.png` – Firewall tool opened
- `step3_block_telnet.png` – Telnet block rule added
- `step4_telnet_test.png` – Telnet connection blocked
- `step5_allow_ssh.png` – SSH allowed rule added
- `step6_telnet_rule_removed.png` – Telnet rule removed

## Outcome
Gained hands-on experience with basic firewall configuration and traffic filtering using Windows Firewall.

