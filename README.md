# speedtest-prometheus
aggretation of RichiH/speedtest_exporter (https://github.com/RichiH/speedtest_exporter) and sivel/speedtest-cli (https://github.com/sivel/speedtest-cli) to push the result of speedtest.net to prometheus pushgateway


we use it via a jenkins job like: ./speedtest_exporter.pl http://metrics.prometheus.local/metrics/job/speedtest_exporter
