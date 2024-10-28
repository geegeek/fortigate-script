# fortigate-script
A bunch of Fortigate scripts to automate some operation

# FortiGatePasswordChanger

An Expect script to change user passwords on FortiGate devices via SSH.

## Requirements

- A super_admin user account with SSH access to the FortiGate device.
- SSH key authentication set up for passwordless login.
- The user whose password you want to change must already exist on the device.
- `expect` package installed on your system.

## Usage

```bash
./FortiGatePasswordChanger.exp <admin_username> <target_username> <new_password> <device_IP> [<hostname> (optional)]

