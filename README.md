# app-configs

Public, JSON-only remote configuration for OuadieZerhouni's apps, plus their
privacy and support pages (served with GitHub Pages).

**Nothing in this repo is secret.** Apps fetch these files anonymously over
HTTPS; every value has a safe default compiled into the app, so a missing or
broken file only means "use the defaults".

| App | Config | Pages |
| --- | --- | --- |
| Ocarina Pocket | [`ocarina-pocket/config.json`](ocarina-pocket/config.json) | [privacy](https://ouadiezerho.me/app-configs/ocarina-pocket/privacy/) · [support](https://ouadiezerho.me/app-configs/ocarina-pocket/support/) |
| Tumbloc | [`tumbloc/config.json`](tumbloc/config.json) | [privacy](tumbloc/PRIVACY.md) · [support](tumbloc/SUPPORT.md) |
| Raft Battle | [`raft-battle/config.json`](raft-battle/config.json) | [privacy](https://ouadiezerho.me/app-configs/raft-battle/privacy/) · [support](https://ouadiezerho.me/app-configs/raft-battle/support/) |
| Mofu | [`mofu-pet/config.json`](mofu-pet/config.json) | [privacy](mofu-pet/PRIVACY.md) · [support](mofu-pet/SUPPORT.md) |
| Boop! | [`boop/config.json`](boop/config.json) | [privacy](boop/PRIVACY.md) · [support](boop/SUPPORT.md) |
| Wuff | [`wuff-pet/config.json`](wuff-pet/config.json) | [privacy](wuff-pet/PRIVACY.md) · [support](wuff-pet/SUPPORT.md) |

Raw URL used by the app:
`https://raw.githubusercontent.com/OuadieZerhouni/app-configs/main/ocarina-pocket/config.json`

Schema and defaults live in the app repo (`config/remote_config_template.json`).
Validate JSON before every push — a malformed file silently falls back to defaults.
