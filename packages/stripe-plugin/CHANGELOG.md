# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.1.0 (2026-10-28)

### Features

* **stripe-plugin:** add opt-in manual capture (authorize then capture) ([#58](https://github.com/vendurehq/community-plugins/pull/58))

### Bug Fixes

* **stripe-plugin:** tolerate webhook events whose object has no metadata ([#62](https://github.com/vendurehq/community-plugins/pull/62))
* **stripe-plugin:** verify webhook signature before order lookup ([#60](https://github.com/vendurehq/community-plugins/pull/60))
* **stripe-plugin:** pass requestOptions to customer list/create calls ([#38](https://github.com/vendurehq/community-plugins/pull/38))

## 1.0.0 (2026-03-30)

Initial release as `@vendure-community/stripe-plugin`, extracted from `@vendure/payments-plugin`.
Equivalent to the functionality in Vendure core v3.5.6.

No additional feature changes from the v3.6.0 development branch.
