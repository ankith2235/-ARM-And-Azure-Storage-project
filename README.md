# 🌩 Azure Storage Assignments – README

## 📚 Overview
This repository documents five hands-on Azure assignments completed using the Azure Portal.  
Each assignment focuses on real-world tasks involving resource provisioning, file storage, CDN, and blob lifecycle management.

---

## 📝 Assignment 1 — Resource Groups & Storage Move
### ✔ Tasks Completed
- Created two Resource Groups: `rg-1` and `rg-2`
- Created a Storage Account inside `rg-1`
- Moved the Storage Account from `rg-1` ➝ `rg-2`

### 💡 Skills Learned
- Resource Group creation and management
- Understanding resource movement limitations
- Subscription and region awareness

---

## 📝 Assignment 2 — Tagging & Filtering
### ✔ Tasks Completed
- Created three Storage Accounts with tag:
- Added an additional Storage Account for team2
- Filtered Azure resources using Tag explorer (Team = team2)

### 💡 Skills Learned
- Resource tagging for organization
- Tag-based filtering and search
- Azure governance best practices

---

## 📝 Assignment 3 — Azure File Share & Mounting
### ✔ Tasks Completed
- Created an Azure File Share inside a storage account
- Mounted the share:
- Windows via `net use Z: \\storageaccount\share`
- Linux via `cifs-utils`
- Unmounted the file share on Windows

### 💡 Skills Learned
- Working with Azure Files (SMB protocol)
- Cross-platform storage mounting
- Storage access keys and permissions

---

## 📝 Assignment 4 — CDN + Blob Storage (with Free Tier Limitation)
### ✔ Tasks Completed
- Created a Storage Account and uploaded blobs
- Attempted to deploy Azure CDN profile and endpoint
- Encountered subscription restriction:
- Explored alternative options:
- Static website hosting in Blob Storage
- Cloudflare CDN (optional free alternative)

### 💡 Skills Learned
- CDN & caching concepts
- Blob storage hosting with public endpoints
- Subscription limitations and workarounds

---

## 📝 Assignment 5 — Blob Access Tier Switching
### ✔ Tasks Completed
- Created a new Storage Account
- Uploaded files into a Blob Container
- Changed Blob Access Tier from:

### 💡 Skills Learned
- Tiered storage cost optimization
- Archive tier behavior (rehydration latency)
- Blob lifecycle management

---

## 🏁 Summary of Skills Gained
- Azure Storage Management
- Resource groups, tagging & governance
- Blob and File Share usage
- Hosting files from storage (static & CDN concepts)
- Switching between Hot, Cool & Archive access tiers
- Troubleshooting connectivity (Linux DNS, CIFS, SMB)

---

## 🛠 Tools Used
- Azure Portal
- PowerShell (Windows)
- Ubuntu/WSL for Linux mounting
- Browser-based uploads

---

## 🎉 Conclusion
These assignments build a strong foundation in Azure:
From basic resource provisioning to real-world enterprise concepts  
like tagging, lifecycle storage, file mounting, and CDN routing.

