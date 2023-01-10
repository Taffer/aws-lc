# aws-lc-fips-sys

[![crates.io](https://img.shields.io/crates/v/aws-lc-fips-sys.svg)](https://crates.io/crates/aws-lc-fips-sys)

Low level AWS-LC FIPS bindings for the Rust programming language. We do not recommend directly relying on these bindings.

[Documentation](https://github.com/awslabs/aws-lc).

## Release Support

This crate pulls in the source code of the latest AWS-LC FIPS branch to build with it. Bindings for platforms we officially support are pre-generated.
The platforms which `aws-lc-fips-sys` builds on is limited to the platforms where the AWS-LC FIPS static build is supported.

### Pregenerated Bindings Availability

CPU|OS
-------------|-------------
x86-64|Linux
arm-64|Linux

### Tested AWS-LC FIPS Build Environments

`aws-lc-fips-sys` currently relies on the AWS-LC FIPS static build, please see our CI documentation at [AWS-LC](https://github.com/awslabs/aws-lc/tree/main/tests/ci#unit-tests).

## Build Prerequisites

Since this crate builds AWS-LC as a native library, all build tools needed to build AWS-LC are applicable to `aws-lc-fips-sys` as well. This includes Go and Perl, which are hard dependencies for the AWS-LC FIPS build.

[Building AWS-LC](https://github.com/awslabs/aws-lc/blob/main/BUILDING.md)

If you use a different build combination for FIPS and would like us to support it, please open an issue to us at [AWS-LC](https://github.com/awslabs/aws-lc/issues/new?assignees=&labels=&template=build-issue.md&title=).

## Contribution

See contributing file at [AWS-LC](https://github.com/awslabs/aws-lc/blob/main/CONTRIBUTING.md)

## Licensing

See license at [AWS-LC](https://github.com/awslabs/aws-lc/blob/main/LICENSE)