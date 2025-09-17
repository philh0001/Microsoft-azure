# 🔗 Project 01 – Data Connectors Deep Dive

## 🎯 Objective
Connect multiple data sources to Microsoft Sentinel, verify logs are flowing, and map each connector to SC-200 exam objectives.

---

## 🛠️ Tasks

### ✅ Task 1: Explore Available Connectors
1. Go to **Microsoft Sentinel → Configuration → Data connectors**.  
2. Browse categories:  
   - Microsoft sources (M365, Defender, Entra ID, Defender for Cloud).  
   - Azure services (Key Vault, SQL, Storage).  
   - Non-Microsoft (AWS, Palo Alto, Cisco, Fortinet, Syslog/CEF).  
3. 📌 Deliverable: Create a list of at least **5 connectors** you want to configure.

---

### ✅ Task 2: Connect Core Microsoft Sources
- **Microsoft 365 Defender connector** → brings email & collaboration alerts.  
- **Defender for Endpoint connector** → ingests endpoint detection events.  
- **Entra ID (Azure AD) connector** → collects sign-in & risky user logs.  
- **Defender for Cloud connector** → posture management & Secure Score alerts.  

📌 Deliverable: Verify each connector shows **“Connected”** status in Sentinel.

---

### ✅ Task 3: Verify Data Flow with KQL
Run quick test queries for each connector:  

- **Sign-in Logs (Entra ID)**  
```kql
SigninLogs | take 5
