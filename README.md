🧩 BashSelect-AdminToolkit
An Interactive Linux User & Group Management Toolkit (Select-Based Version)
Easy-to-use Bash scripts with a select-based interface for terminal-based system administration.

![Made with Bash](https://img.shields.io/badge/Made%20with-Bash-blue?logo=gnubash)

🛠️ About the Project
This project offers a menu-driven Bash interface (using select) for Linux system administrators to efficiently manage users and groups. It simplifies common admin tasks such as adding users, modifying attributes, and handling groups—all without memorizing complex commands.
📌 Features
✅ Add users (single, from file, or bulk)
✅ Modify usernames, UIDs, shells, and group membership
✅ Lock and unlock user accounts
✅ Change user passwords
✅ Add groups manually or via CSV/txt file
✅ Modify group names and GIDs
✅ View users and groups (simple list)


| Script Name                 | Functionality                            |
| --------------------------- | ---------------------------------------- |
| `add_users_select.sh`       | Add a single user, from file, or in bulk |
| `modify_user_select.sh`     | Rename user, update UID, shell, etc.     |
| `list_users_select.sh`      | View system users                        |
| `lock_user_select.sh`       | Lock a user account                      |
| `unlock_user_select.sh`     | Unlock a user account                    |
| `change_password_select.sh` | Change a user’s password                 |
| `add_groups_select.sh`      | Create new group(s) manually or via file |
| `modify_group_select.sh`    | Rename group, change GID                 |
| `list_groups_select.sh`     | View groups                              |
| `admin_menu.sh`             | Main menu launcher for all modules       |

🚀 How to Run
⚠️ Must be run as root or with sudo privileges:
```bash
sudo bash admin_menu.sh
```
Make sure all *_select.sh scripts are in the same directory as admin_menu.sh or update the relative paths accordingly.



## 📂 Folder Structure
```bash
BashSelect-AdminToolkit/
├── admin_menu.sh
├── add_users_select.sh
├── modify_user_select.sh
├── list_users_select.sh
├── lock_user_select.sh
├── unlock_user_select.sh
├── change_password_select.sh
├── add_groups_select.sh
├── modify_group_select.sh
├── list_groups_select.sh
├── credentials/        # (auto-generated output)
└── DataSelect/         # user & group input files

```
🛡️ Requirements
1) Linux OS
2) bash
3) passwd, usermod, groupmod, useradd, groupadd, etc.
4) openssl (for generating random passwords)

👩‍💻 Author
Amira Mohamed

🔗 License
This project is open-source and available under the MIT License.



🚀 Push BashSelect-AdminToolkit to GitHub 🚀
# 1) Navigate to your project directory:
 ```bash cd /home/amiramohamed/BashSelect-AdminToolkit ```

# 2) Initialize a new Git repository:
```bash git init ```

# 3) Connect your local repo to GitHub:
```bash git remote add origin https://github.com/amiramohamed/BashSelect-AdminToolkit.git```

# 4) Add all project files to staging:
```bash git add . ```

# 5) Commit the files with a message:
```bash git commit -m "Initial commit - admin toolkit using select interface" ```

# 6) Rename the current branch to main:
```bash git branch -M main ```

# 7) Push the project to GitHub:
```bash git push -u origin main ```


