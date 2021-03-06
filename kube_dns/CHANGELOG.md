# CHANGELOG - Kube-dns

## 2.0.0 / 2018-09-04

* [Changed] Update kube_dns to use the new OpenMetricsBaseCheck. See [#1980](https://github.com/DataDog/integrations-core/pull/1980).
* [Added] Limit Prometheus/OpenMetrics checks to 2000 metrics per run by default. See [#2093](https://github.com/DataDog/integrations-core/pull/2093).
* [Added] Make HTTP request timeout configurable in prometheus checks. See [#1790](https://github.com/DataDog/integrations-core/pull/1790).
* [Fixed] Add data files to the wheel package. See [#1727](https://github.com/DataDog/integrations-core/pull/1727).

## 1.4.0 / 2018-06-13

* [Added] Package `auto_conf.yaml` for appropriate integrations. See [#1664](https://github.com/DataDog/integrations-core/pull/1664).

## 1.3.0 / 2018-05-11

* [IMPROVEMENT] Add metrics `kubedns.request_count.count`, `kubedns.error_count.count` and `cachemiss_count.count`, alternative metrics submitted as monotonic\_counts. See [#1341][]

## 1.2.0 / 2018-01-10

* [IMPROVEMENT] Bumping protobuf to version 3.5.1. See [#965][]

## 1.1.0 / 2017-11-21

* [UPDATE] Update auto\_conf template to support agent 6 and 5.20+. See [#860][]

## 1.0.0 / 2017-07-18

* [FEATURE] Add kube-dns integration, based on new PrometheusCheck class. See [#410][] and [#451][], thanks [@aerostitch][]

<!--- The following link definition list is generated by PimpMyChangelog --->
[#410]: https://github.com/DataDog/integrations-core/issues/410
[#451]: https://github.com/DataDog/integrations-core/issues/451
[#860]: https://github.com/DataDog/integrations-core/issues/860
[#965]: https://github.com/DataDog/integrations-core/issues/965
[#1341]: https://github.com/DataDog/integrations-core/issues/1341
[@aerostitch]: https://github.com/aerostitch
