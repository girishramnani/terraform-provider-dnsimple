## master

## 0.9.2

* Adds the deprecated `resource_dnsimple_record`

## 0.9.1

* Brings the `dnsimple_record` configuration back and adds a deprecation warning

## 0.9.0

* Adds the zone data-source
* Adds the domain resource (to create domains in DNSimple)

## 0.6.0

NOTES

* Migrated SDK to v2 (version 2.7.0)
* Updated dependencies

## 0.5.3

NOTES

* Include darwin_arm64 builds in release

## 0.5.3

NOTES

* Removes /vendor directory

## 0.5.2

NOTES

* Updated dependencies
* Include darwin_arm64 builds

## 0.5.1

NOTES

* Move to GH Actions for publishing

## 0.5.0

FEATURES:

* **New Resource:** `dnsimple_email_forward` ([#28](https://github.com/terraform-providers/terraform-provider-dnsimple/pull/28), [#30](https://github.com/terraform-providers/terraform-provider-dnsimple/pull/30))
* Abilty to switch to sandbox environment ([#12](https://github.com/terraform-providers/terraform-provider-dnsimple/pull/12))

## 0.4.0 (May 12, 2020)

ENHANCEMENTS

* Upgraded to dnsimple-go v0.61.0

## 0.3.0 (February 11, 2020)

NOTES

* Upgraded plugin to use the Terraform Plugin SDK v1.0.0 instead of Terraform Core ([#21](https://github.com/terraform-providers/terraform-provider-dnsimple/pulls/21))
* Remove support for deprecated API v1 attributes ([#22](https://github.com/terraform-providers/terraform-provider-dnsimple/pulls/22))

ENHANCEMENTS

* Upgraded to dnsimple-go v0.31.0 ([#23](https://github.com/terraform-providers/terraform-provider-dnsimple/pulls/23))

## 0.2.0 (June 20, 2019)

NOTES

* This release includes a Terraform upgrade with compatibility for Terraform v0.12. The provider remains backwards compatible with Terraform v0.11 and there should not be any significant behavioural changes. ([#16](https://github.com/terraform-providers/terraform-provider-dnsimple/issues/16))

## 0.1.0 (June 20, 2017)

NOTES

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
