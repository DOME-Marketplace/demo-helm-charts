# The DOME DSS-Demo Helm Charts

[![License (LGPL version 2.1)](https://img.shields.io/badge/license-GNU%20LGPL%20version%202.1-blue.svg?style=flat-square)](https://www.gnu.org/licenses/lgpl-2.1.html)

The [DSS-Demo](./charts/dss-demo) Helm Charts to be used by [VCVerifier](https://github.com/DOME-Marketplace/VCVerifier)
for validating JAdES signatures

If you are using self-issued certificates for integration tests, you need to add them to the
trusted source of the DSS-Demo application (section `trustedSource` in the [values.yaml](./charts/dss-demo/values.yaml)).