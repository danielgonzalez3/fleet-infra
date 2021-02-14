
#### Releases

- controller v2.21.2 -> v2.21.3
- fluentd v2.15.0 -> v2.15.1
- nsq v2.5.0 -> v2.5.1
- slugbuilder v2.7.7 -> v2.7.8
- workflow v2.22.2 -> v2.22.3
- workflow-cli v2.22.2 -> v2.22.3
- workflow-e2e v2.22.2 -> v2.22.3

#### Features

- [`8344d5e`](https://github.com/teamhephy/controller/commit/8344d5eb3b384fbe83f5cd619ece7a5262caf7a6) (controller) - controller: permit setting GUNICORN_WORKERS
- [`787faf4`](https://github.com/teamhephy/controller/commit/787faf4b689f367ca1ba6b65b6e0dd41470920ce) (controller) - controller: document added chart values

#### Fixes

- [`0312315`](https://github.com/teamhephy/controller/commit/0312315538d2812615e7b4da8fccdeba77c33687) (controller) - HPAs: add continue in try and catch block
- [`aabfeb8`](https://github.com/teamhephy/fluentd/commit/aabfeb892ecab2abcc38a6fc7b803151506e93ca) (fluentd) - charts: env var should point to nsqd service
- [`77f09e3`](https://github.com/teamhephy/nsq/commit/77f09e365d4f3c43a6c9cba3e240746e4e794c3f) (nsq) - chart: Helm 3 validates, error on statefulset
- [`e0a2ae9`](https://github.com/teamhephy/slugbuilder/commit/e0a2ae983a7b7735312236dd8a404fc80ac16cb8) (slugbuilder) - build.sh: Quotes on variable causes build detect to break
- [`09e9bb5`](https://github.com/teamhephy/slugbuilder/commit/09e9bb55b4018aacb48932323f9bd3de0f702120) (slugbuilder) - slugbuilder: really fix buildpack detection

#### Maintenance

- [`b4c53b6`](https://github.com/teamhephy/slugbuilder/commit/b4c53b655c9cd712471995967791dc9b0df5b647) (slugbuilder) - buildpacks: update all buildpacks to latest versions
- [`2f14761`](https://github.com/teamhephy/workflow/commit/2f14761f927561e239fa1503cbdda26e493b32ba) (workflow) - mkdocs: fixing mkdocs so it builds in strict mode
