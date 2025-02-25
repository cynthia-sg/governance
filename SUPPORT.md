# Support for deploying and using KEDA

Thank you for using KEDA!

KEDA is an open-source project under CNCF Foundation and provides best-effort support and use GitHub for tracking bugs and feature requests. Sandbox projects in our organization are offered as-is and are not supported for production.

Want to contribute a feature or fix? We are more than happy to review requests and contributions, but recommend going through our [contribution guide](https://github.com/kedacore/keda/blob/main/CONTRIBUTING.md).

## Documentation

* [User Documentation](https://keda.sh/)
* [Troubleshooting Guide](https://keda.sh/docs/latest/troubleshooting/)
* [FAQ](https://keda.sh/docs/latest/faq/)

## Community

We have a nice community that is always happy to help each other:

* [GitHub Discussions](https://github.com/kedacore/keda/discussions/new)
* [Slack](https://kubernetes.slack.com) ([registration](http://slack.k8s.io)):
The `#keda` channel is usually the place where people offer support.

## Kubernetes Support

The supported window of Kubernetes versions with KEDA is known as "N-2" which means that KEDA will provide support for running on N-2 at least.

However, maintainers can decide to extend this by supporting more minor versions based on the required CRDs being used; but there is no guarantee.

> Example - At time of writing, Kubernetes 1.25 is the latest minor version so KEDA can only use new features that were introduced in 1.23

You can learn more about the currently supported Kubernetes version in our [FAQ](https://keda.sh/docs/latest/faq/).
