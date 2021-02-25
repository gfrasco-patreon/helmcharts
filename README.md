# Helm Chart Repository

To add a new chart
- create its source under **helm-chart-sources**
- package the new chart under **/**
  > `helm package helm-chart-sources/name_of_your_chart`

- recreate the index
  > `helm repo index --url https://gfrasco-patreon.github.io/helmcharts/ --merge index.yaml .`
