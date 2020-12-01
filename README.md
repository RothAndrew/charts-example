# charts-example

## Prerequisites

- Unix-like OS
- [chart-releaser](https://github.com/helm/chart-releaser) installed and available on the path as `helm-cr`. The recommended way to install chart-releaser is to use ASDF. `asdf plugin-add helm-cr https://github.com/Antiarchitect/asdf-helm-cr.git`
- [pre-commit](https://pre-commit.com/)

## Getting Started

1. Update [.chart-releaser-config.yaml](.chart-releaser-config.yaml) with the correct values for your project.

## Notes

1. This project does not support signing charts at this time. It is something we are looking into doing in the future. Please let us know if creating signed charts is something you can't live without.
