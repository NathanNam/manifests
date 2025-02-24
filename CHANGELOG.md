# [1.0.0](https://github.com/observeinc/manifests/compare/v0.35.3...v1.0.0) (2024-02-05)


### Bug Fixes

* **metrics:** bump global scrape interval to 60s ([90864a9](https://github.com/observeinc/manifests/commit/90864a931918a6f6ad7c7125d2e6046681061abb))


* fix(metrics)!: Stop collecting container_fs_xxx metrics to reduce a data volume and make the data collection opted-in ([a530c66](https://github.com/observeinc/manifests/commit/a530c6641b6a3a4cce7c798970218459def324a5))


### BREAKING CHANGES

* PROM_SCRAPE_POD_ACTION was previously set to keep but is changed to drop to reduce a data volume and make the data collection of pod metrics opted-in.
https://docs.observeinc.com/en/latest/content/integrations/kubernetes/collecting_pod_metrics_cadvisor_metrics.html



## [0.35.3](https://github.com/observeinc/manifests/compare/v0.35.2...v0.35.3) (2024-01-30)


### Bug Fixes

* **deps:** Update fluenbit and grafana agent ([#147](https://github.com/observeinc/manifests/issues/147)) ([ff19f22](https://github.com/observeinc/manifests/commit/ff19f2271e2e3016907ff1fbd0c365268a07d387))
* **logs:** add FB_IGNORE_OLDER ([#150](https://github.com/observeinc/manifests/issues/150)) ([daa2eee](https://github.com/observeinc/manifests/commit/daa2eee14595d7dc2e38d5b60181f8b9f48b8446))
* **metrics:** bump cadvisor interval to 60s ([#148](https://github.com/observeinc/manifests/issues/148)) ([8646829](https://github.com/observeinc/manifests/commit/8646829b76127c076ee861cb7ab9373cbc8f3fc9))
* **traces:** bump otel-collector-contrib to 0.93.0 ([07c222e](https://github.com/observeinc/manifests/commit/07c222ebb6088480308688c199723f314098892f))



## [0.35.2](https://github.com/observeinc/manifests/compare/v0.35.1...v0.35.2) (2024-01-16)


### Bug Fixes

* bump grafana agent and otel versions ([72f8608](https://github.com/observeinc/manifests/commit/72f8608231f73736e4f8d9fd728f2bcc2404ac46))



## [0.35.1](https://github.com/observeinc/manifests/compare/v0.35.0...v0.35.1) (2024-01-02)


### Bug Fixes

* **logs:** bump fluent-bit to 2.2.1 ([a287540](https://github.com/observeinc/manifests/commit/a287540f959cafd233f4edc823ec2dd03e151687))



# [0.35.0](https://github.com/observeinc/manifests/compare/v0.34.0...v0.35.0) (2023-12-21)


### Bug Fixes

* bump kube-state-events to 0.11.1 ([#143](https://github.com/observeinc/manifests/issues/143)) ([570249f](https://github.com/observeinc/manifests/commit/570249f2268b6b75facfd381a896ee90f4c0d264))
* **traces:** update otlphttp endpoint to v2 ([#141](https://github.com/observeinc/manifests/issues/141)) ([6e3a091](https://github.com/observeinc/manifests/commit/6e3a09185d9c052dc4a8729cbd5d798c61519c52))


### Features

* **traces:** update otel-collector-contrib to 0.91.0 ([cffe059](https://github.com/observeinc/manifests/commit/cffe059a898a7104b8b0327521f4efa78d0ddc78))



