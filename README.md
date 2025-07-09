# siem-dashboard-splunk

# 🛡️ Splunk SIEM Dashboard & Alerting System

## 📌 Overview

This project demonstrates the creation of a basic SIEM (Security Information and Event Management) system using **Splunk Free** on a **Windows 11 virtual machine**. It involves ingesting sample logs, building interactive dashboards, and configuring real-time alerts for potential security incidents like brute-force login attempts or access from suspicious IPs.

---

## 🧰 Tools Used

- **Splunk Free**
- **Windows 11 VM**
- **Public Sample Logs**
  - Windows Security Event Logs (Event ID 4625 – Failed Logins)
  - Firewall Logs
  - Web Server Access Logs
- **SPL (Search Processing Language)**

---

## 📁 Project Structure

<pre><code>
splunk-siem-project/
├── dashboards/               # Dashboard screenshots & summary
│   ├── failed_logins.png
│   ├── ip_access_patterns.png
│   └── dashboard_summary.md
│
├── alerts/                   # Alert config screenshots & documentation
│   ├── multiple_failed_logins.png
│   └── alert_config.md
│
├── logs/                     # Sample log data used for testing
│   ├── windows_security.log
│   └── firewall.log
│
├── SIEM_Project_Report.md    # Detailed project write-up (optional)
├── README.md                 # Main project overview
└── LICENSE                   # Optional license file
</code></pre>

---

## 📊 Dashboards

### 🔐 Failed Login Attempts
- Shows top usernames and source IPs associated with failed logins.
- Uses `EventCode=4625` from Windows Security logs.

### 🌍 IP Access Patterns
- Visualizes top source IPs and their frequency.
- Optional: Can include geolocation mapping using external IP data.

### 🕒 Login Activity Timeline
- Displays login activity by hour and day.

> 📷 Screenshots available in the `dashboards/` folder.

---

## 🚨 Alerts Configured

### 📌 Multiple Failed Login Attempts

---

### 📝 Summary Report



---

### 📚 References



---

### 💡 Lessons Learned
 

---

### 🚀 Future Enhancements



---

### 🧾 License


