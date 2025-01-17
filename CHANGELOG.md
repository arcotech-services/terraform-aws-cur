# Changelog

### [0.1.2](https://www.github.com/nuuday/terraform-aws-cur/compare/v0.1.1...v0.1.2) (2021-06-08)


### Improvements

* support Terraform 1.0 ([#25](https://www.github.com/nuuday/terraform-aws-cur/issues/25)) ([f389ffd](https://www.github.com/nuuday/terraform-aws-cur/commit/f389ffd3b72b85838c788447d7517fa33d554d31))

### [0.1.1](https://www.github.com/nuuday/terraform-aws-cur/compare/v0.1.0...v0.1.1) (2021-06-02)


### Fixes

* prevent conflicting operations on creating S3 resources ([#22](https://www.github.com/nuuday/terraform-aws-cur/issues/22)) ([1a99651](https://www.github.com/nuuday/terraform-aws-cur/commit/1a99651a4259451cdc830633159e3f9cb12b3be1))


### Improvements

* optionally use KMS CMK for S3 SSE ([#24](https://www.github.com/nuuday/terraform-aws-cur/issues/24)) ([6cdc902](https://www.github.com/nuuday/terraform-aws-cur/commit/6cdc902dc19836665239f958883347f657d157e7))

## 0.1.0 (2021-05-31)


### Features

* optionally provision S3 bucket for CUR data ([#3](https://www.github.com/nuuday/terraform-aws-cur/issues/3)) ([96f16ee](https://www.github.com/nuuday/terraform-aws-cur/commit/96f16ee42f238454bab82bef2a985d32275a92c5))
* populate Athena Table with CUR data ([#6](https://www.github.com/nuuday/terraform-aws-cur/issues/6)) ([ffec446](https://www.github.com/nuuday/terraform-aws-cur/commit/ffec44651e3d51ce067d8e856b86fb30585987c8))


### Fixes

* actually create report definition ([#9](https://www.github.com/nuuday/terraform-aws-cur/issues/9)) ([a89251a](https://www.github.com/nuuday/terraform-aws-cur/commit/a89251a177eae79b7ca1e86b8d38994dada34079))
* prevent Lambda from erroring out if Crawler is already running ([#11](https://www.github.com/nuuday/terraform-aws-cur/issues/11)) ([a914ae3](https://www.github.com/nuuday/terraform-aws-cur/commit/a914ae38fb67a03542e0fe51d685ad76c3d29c55))


### Improvements

* output useful values from provisioned resources ([#19](https://www.github.com/nuuday/terraform-aws-cur/issues/19)) ([7904c5e](https://www.github.com/nuuday/terraform-aws-cur/commit/7904c5efa974cdcc1458b551a8f7d1fd882fe845))
