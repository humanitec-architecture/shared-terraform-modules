# Deprecation notice

⚠️ The reference architecture implementations for [AWS](https://github.com/humanitec-architecture/reference-architecture-aws), [Azure](https://github.com/humanitec-architecture/reference-architecture-azure), [GCP](https://github.com/humanitec-architecture/reference-architecture-gcp), and [RHOS](https://github.com/humanitec-architecture/reference-architecture-rhos) have been deprecated. They will continue to be available for some time, but not receive further updates.

The deprecation only affects the reference implementation contained in their respective repositories, not the underlying conceptual architectures and supplementary materials shown on the [Humanitec website](https://humanitec.com/reference-architectures).

# shared-terraform-modules

Shared Terraform Modules used by Humanitec Reference Architectures.

## modules

* [github-app](./modules/github-app) Parses a GitHub Application credentials file created using [create-gh-app](https://github.com/humanitec-architecture/create-gh-app)
* [portal-backstage](./modules/portal-backstage) Deploys the [Humanitec Reference Architecture Backstage](https://github.com/humanitec-architecture/backstage) as Application into a specific Humanitec Organization.
