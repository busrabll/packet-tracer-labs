## 🔹 Lab 04 - Basic Device Security

This lab demonstrates basic Cisco IOS device configuration and security settings using the Command Line Interface (CLI).

### ⚙️ Step-by-Step Configuration

#### Step 1 – Access Global Configuration Mode

- Use the `enable` command to enter Privileged EXEC Mode, then `configure terminal` to access Global Configuration Mode.
- [View Privileged EXEC Mode](images/user-exec-to-privileged-exec.png)
- [View Global Configuration Mode](images/global-configuration-mode.png)

#### Step 2 – Configure Switch Hostname

- Change the switch hostname to `SW1` for easier identification and management.
- [View Hostname Configuration](images/change-hostname.png)

#### Step 3 – Configure and Verify Enable Password

- Use the `enable password` command to configure an unencrypted password, then verify its configuration using `show running-config`.
- [View Password Configuration](images/add-password-for-privileged-mode.png)
- [View Running Configuration](images/show-running-config.png)

#### Step 4 – Enable and Verify Password Encryption

- Enable password encryption using the `service password-encryption` command and verify the encrypted password with `show running-config`.
- [View Password Encryption Configuration](images/password-encryption.png)
- [View Encrypted Configuration](images/password-encryption-show-running.png)

#### Step 5 – Configure Enable Secret Password

- Use the `enable secret` command to configure a more secure password for Privileged EXEC Mode access.
- [View Enable Secret Configuration](images/enable-secret.png)

#### Step 6 – Save the Configuration

- Save the `running-config` to `startup-config` using the `write` command to preserve changes after a reboot.
- [View Saved Configuration](images/save-configuration.png)
