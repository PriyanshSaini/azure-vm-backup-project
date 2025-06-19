# 💾 Azure VM Backup and Disaster Recovery using Recovery Services Vault

This project demonstrates a real-world use case of **configuring automated backup and disaster recovery** for an Azure Virtual Machine using **Azure Recovery Services Vault**, aligned with **AZ-104** (Azure Administrator Associate) certification learning.

---

## 📌 Project Objective

Set up daily backup for an Azure VM, customize retention policies, and validate disaster recovery through a VM restore operation. Also configure **email alerts** to notify about **backup failures**.

---

## ⚙️ Technologies Used

- Azure Virtual Machines  
- Recovery Services Vault  
- Backup Policies  
- Log Analytics / Backup Jobs  
- Alerts & Notifications  
- Azure Portal

---

## 🪜 Steps Performed

### 1. Create Recovery Services Vault
Created a vault named `RSV-BackupVault` in the same region as the VM.


---

### 2. Configure Backup for VM
Selected the existing Azure VM and enabled backup using the vault.


---

### 3. Create Custom Backup Policy
Configured a daily backup at 10:00 PM with a 30-day retention period.


---

### 4. Run Initial Backup & Verify
Ran the first backup manually and verified its success.

---

### 5. Simulate Disaster Recovery (Restore VM)
Restored the backed-up VM using the latest recovery point.

---

### 6. Configure Email Alerts for Backup Failures
Enabled email alerts for backup job failures to receive real-time notifications.


---

## ✅ Outcome

- Successful automated backups and restore
- Recovery validation of Azure VM
- Real-time backup failure alerting via email

---

## 🧠 Learnings

- Hands-on experience with **Recovery Services Vault**
- Implementing backup schedules and policies
- Understanding disaster recovery with restore points
- Monitoring and alerting best practices

