# 🧩 Domain 1 – User & Group Management (RHEL)

### Description
Enterprise-level **user and group management** on **Red Hat Enterprise Linux (RHEL)** simulating six departments (two users each), with sudo privileges, department folders, shared directories, and password policies.

---

## 🏢 Departments
| Department | Group | Users |
|-------------|--------|--------|
| IT | it_team | alex_it, jenny_it |
| HR | hr_team | linda_hr, james_hr |
| Finance | finance_team | emma_fin, brian_fin |
| Security | security_team | jack_sec, grace_sec |
| Engineering | eng_team | david_eng, olivia_eng |
| Marketing | mkt_team | noah_mkt, sophia_mkt |

---

## ⚙️ Highlights
- 12 users, 6 groups  
- Sudo access for IT & Security  
- Department folders with `770` permissions  
- `/dept/shared` for collaboration  
- Password aging policy using `chage`  
- Bash script automating password setup  

---

## 📸 Screenshots
| Step | Description | Image |
|------|--------------|--------|
| 1 | System Info | `./screenshots/01_system_info.png` |
| 2 | Groups Created | `./screenshots/02_groups_created.png` |
| 3 | Users Added | `./screenshots/03_users_added.png` |
| 4 | Folder Permissions | `./screenshots/04_directory_permissions.png` |
| 5 | Access Denied Test | `./screenshots/05_access_denied.png` |
| 6 | Shared Folder | `./screenshots/06_shared_folder.png` |
| 7 | Bash Script Execution | `./screenshots/07_script_execution.png` |

---

## 🧠 Files Included
| File | Description |
|------|-------------|
| `user_group_management_lab.md` | Full detailed lab walkthrough |
| `set_user_passwords.sh` | Bash script to automate password setup |
| `screenshots/` | All image proofs |

---

## ✅ Summary
This project demonstrates enterprise-grade user and group administration on Red Hat Enterprise Linux (RHEL) with role-based access, automation, and security policies.

👉 **Next:** [Domain 2 – File Management & Permissions](../domain2-file-permission-management)
