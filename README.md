# base-elk

My local stack ELK setup

## Prerequisits

```bash
# Take into account the parameter now
sudo sysctl -w vm.max_map_count=262144

# Set it for the next reboot
echo "vm.max_map_count=262144" | sudo tee -a /etc/sysctl.conf >/dev/null
```