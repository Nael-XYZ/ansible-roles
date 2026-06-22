# Ansible Roles 🎭

Production-ready Ansible roles for server management.

## Roles

- **hardening**: SSH, firewall, kernel tuning
- **docker**: Install + configure Docker CE
- **monitoring**: Node exporter + Prometheus
- **backup**: Automated backups to S3
- **users**: SSH keys + sudo access

## Usage

```yaml
- hosts: web_servers
  roles:
    - role: hardening
    - role: docker
    - role: monitoring
```

## License

MIT