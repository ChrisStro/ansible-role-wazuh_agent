# Ansible Role: wazuh_agent

Ansible role for wazuh agent installations

## Role Variables

For available variables see `defaults/main.yml`
```yaml
# required
wazuh_agent_wazuh_manager: MyWazuhIpOrFqdn.dns.suffix

# optional
wazuh_agent_password: "my_own_secret"

```

## Notes

- Simplfied version for git submodule
- Look for ansible-wazuh for official support
- Currently supported base distributions: Debian
