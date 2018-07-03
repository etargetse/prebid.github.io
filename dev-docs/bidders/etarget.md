---
layout: bidder
title: Etarget
description: Prebid Etarget Bidder Adaptor 

top_nav_section: dev_docs
nav_section: reference

hide: true

biddercode: etarget

biddercode_longer_than_12: false

prebid_1_0_supported : true
media_types: video
gdpr_supported: true
---


### bid params

{: .table .table-bordered .table-striped }

| Name | Scope | Description | Example |
| :--- | :---- | :---------- | :------ |
| `refid` | required | | `12345` |
| `country` | required | The Etarget country code | `1` |

### refid

RefID is specific ID for each code generated in our system.
You can register and create your own ID on this site https://sk.etarget-media.com.

### country codes

Each country in which we providing our services has own country code.
Array of country codes and country domains that belonge to them.
{1:SK, 2:CZ, 3:HU, 4:RO, 5:RS, 6:BG, 7:PL, 8:HR, 9:AT, 10:CO, 11:DE, 255:EN}
