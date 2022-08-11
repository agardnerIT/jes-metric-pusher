# Job Executor Service Metric Exporter
This repository shows how to push metrics from a [Keptn job executor service](https://github.com/keptn-contrib/job-executor-service) run to Observability backends such as Prometheus or Dynatrace.

Often you will run an existing container / tool with the [job executor service](https://github.com/keptn-contrib/job-executor-service) which outputs results. Most likely you want to use these metrics in a subsequent Keptn task (eg. a quality gate evaluation). To do so, you will need to push the metrics to a metric backend. This repository demonstrates how this can be done.

- [Prometheus Integration](TODO)
- [Dynatrace Integration](TODO)

Rather than directly running your container image, you'll need to wrap it in a "parent script" and run that parent script instead (shell scripts, python scripts, powershell scripts etc.).

The samples in this repository use Python, but the instructions should provide enough information to adapt to any language you prefer.

## Push Metrics to Prometheus
TODO

## Push Metrics to Dynatrace
TODO

## Contributing

- Enhancements: Contributions welcome! Create a Pull Request. 
- Bugs: Create an issue.
- Assistance / Questions: Join [Keptn on Slack](https://slack.keptn.sh) and ask for help in `#keptn-integrations`
