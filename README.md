# Suricata rules

This repository provides Indicators of Compromise (IOCs) for various malware and known malicious networks. PiRogue automatically fetches and updates these Suricata rules daily.

We generate these Suricata rules from reliable threat intelligence sources:

* [ProofPoint Emerging Threat Open](https://community.emergingthreats.net/t/frequently-asked-questions/56)
* [Echap](https://github.com/AssoEchap/stalkerware-indicators)

For a full list of malware and samples, please refer to this section:[Echap Stalkerware list](https://github.com/AssoEchap/stalkerware-indicators?tab=readme-ov-file#stalkerware).

## Manually Enable These Suricata Rules 

To enable those rules, run the following commands on your PiRogue:

```
sudo suricata-update add-source PTS https://piroguetoolsuite.github.io/suricata-rules/suricata.rules
```

For more information on managing Suricata rules using `suricata-update`, refer to the [Suricata-update documentation](https://suricata-update.readthedocs.io/en/latest/quickstart.html#discover-other-available-rule-sources).
