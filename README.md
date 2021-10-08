# dev_utils
Utilities used in ROS development

## pilz_relay_utils
Makes usage of sainsmart usb relays in development more convenient.

## Usage
Execute a single relay command for sainsmart usb relays:
```
roslaunch pilz_relay_utils sainsmart_cmd_exec.launch byte_data:=4
```
This example switches the third relay channel on and all others off.
