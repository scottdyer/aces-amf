<!-- SPDX-License-Identifier: Apache-2.0 -->
<!-- Copyright Contributors to the ACES Project. -->

# ACES Metadata File (AMF)

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![AMF Schema and Example
Validation](https://github.com/aces-aswf/aces-amf/actions/workflows/validate-xml.yml/badge.svg)
![GitHub release (with
filter)](https://img.shields.io/github/v/release/aces-aswf/aces-amf) [![CLA
assistant](https://cla-assistant.io/readme/badge/aces-aswf/aces-amf)](https://cla-assistant.io/aces-aswf/aces-amf)

The ACES Metadata File (AMF) is an XML sidecar format for exchanging the
metadata required to reconstruct ACES viewing pipelines. It specifies the
transforms needed to configure an ACES pipeline for a set of related image
files.

This directory includes:

- The ACES Metadata File XML Schema:
  [acesMetadataFile.xsd](./schema/acesMetadataFile.xsd)

- Copies of dependent XML schemas

- [Example AMF files](./examples/)

For details on the AMF format and its use cases, see the [ACES
Documentation](https://docs.acescentral.com/amf/specification/).

## Contributing

ACES depends on community participation. Developers, manufacturers, and end
users are encouraged to contribute code, bug fixes, documentation, and other
technical artifacts.

All contributors must have a signed Contributor License Agreement (CLA) on file
to ensure that the project can freely use your contributions. 

See [CONTRIBUTING](https://github.com/aces-aswf/.github/blob/main/CONTRIBUTING.md) for more details.

## Governance

This repository is a submodule of the ACES project, which is itself governed by the
Academy Software Foundation.

For details about how the ACES project operates, please see
[GOVERNANCE](https://github.com/aces-aswf/.github/blob/main/GOVERNANCE.md).

## Reporting Issues

To report a problem with AMF, please open an
[issue](https://github.com/aces-aswf/aces-amf/issues).

If the issue is senstive in nature or a security related issue, please do not
report in the issue tracker. Instead refer to [SECURITY](https://github.com/aces-aswf/.github/blob/main/SECURITY.md)
for more information about the project security policy.

## License

The ACES Project is licensed under the [Apache 2.0 license](./LICENSE).