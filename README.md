# PoCs & research

Public proof-of-concepts and security research maintained by godylockz.
Code, requirements, testing evidence, and attribution live in the linked repositories.
Some projects adapt prior research; inclusion here does not claim original discovery.

## Proof-of-concepts

| Project | Scope |
| --- | --- |
| [PHP2Shell — CVE-2026-109618 / CVE-2026-109619](https://github.com/godylockz/CVE-2026-109618-109619) | PHP memory corruption and stale request state; reproducible labs and RCE profiles tied to specific mod_php and PHP-FPM builds and configurations. |
| [Craft CMS — CVE-2026-92592](https://github.com/godylockz/CVE-2026-92592) | Authenticated RCE through signed-cookie reuse and Twig rendering; requires a Control Panel account without active 2FA. |
| [Craft CMS — CVE-2025-32432](https://github.com/godylockz/CVE-2025-32432) | Unauthenticated RCE through attacker-controlled asset-transform configuration and a Yii behavior gadget, with session-file and nginx-log inclusion methods. |
| [Gogs — CVE-2025-8110](https://github.com/godylockz/CVE-2025-8110) | Authenticated repository-content API writes through symlinks with the Gogs service account's permissions. |
| [Zabbix — CVE-2024-42327](https://github.com/godylockz/CVE-2024-42327) | Privilege escalation to remote code execution. |
| [Havoc — CVE-2024-41570](https://github.com/godylockz/CVE-2024-41570) | Adapted SSRF-to-RCE chain; the command-injection step requires valid teamserver credentials. |
| [Jenkins — CVE-2024-23897](https://github.com/godylockz/CVE-2024-23897) | Arbitrary file read through the Jenkins CLI. |
| [Ghost — CVE-2023-40028](https://github.com/godylockz/CVE-2023-40028) | Arbitrary file-read proof-of-concept for Ghost CMS. |
| [LimeSurvey — CVE-2021-44967](https://github.com/godylockz/CVE-2021-44967) | Authenticated remote code execution. |

Use these projects only on systems you own or are authorized to test.
Check each repository for prerequisites and evidence limits.

## License

This index is available under the [MIT License](LICENSE). Each linked project
is governed by the license in its own repository.
