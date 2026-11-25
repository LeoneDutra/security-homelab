# Security Homelab

A documented home SOC lab: Wazuh SIEM, Windows and Linux endpoints with Sysmon, an Active Directory domain, and Atomic Red Team for attack simulation.

## Focus areas
- Log collection and analysis
- Host and network visibility (Sysmon, Wazuh, Zeek)
- Detection engineering basics (rules live in [detection-engineering-lab](https://github.com/LeoneDutra/detection-engineering-lab))
- Incident response workflows (cases live in [dfir-casebook](https://github.com/LeoneDutra/dfir-casebook))
- Packet capture and analysis exercises

> No real or sensitive data is included. All logs are generated in the lab for educational purposes.

## Roadmap

- [ ] Network diagram and component overview
- [ ] Wazuh manager + Linux and Windows agents
- [ ] Sysmon deployed with a community config
- [ ] Cloud-hosted AD domain with users and GPOs
- [ ] Atomic Red Team tests producing alerts in Wazuh
- [ ] v2: everything as code (Docker Compose / Terraform)

## Repository structure

```
docs/
diagrams/
configs/sysmon/
configs/wazuh/
docker/
```

## Notes

This repo replaces my earlier `soc-home-lab`.

## Skills demonstrated

Wazuh · Sysmon · Active Directory · Docker · UTM · Atomic Red Team · pfSense/OPNsense

## Part of my cybersecurity portfolio

Career changer (head brewer → SOC / Cloud & AI Security), based in Calgary, AB. See all projects on my [GitHub profile](https://github.com/LeoneDutra).
