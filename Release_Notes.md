---
pagetitle: Release Notes for LSM6DSV Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSV Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSV component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 05-Dic-2022</label>
<div>

## Main changes

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.0.1 / 19-Apr-2023</label>
<div>

## Main changes

- Fix enum values names
- Add __weak directive to read/write registers routines

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V1.1.0 / 18-May-2023</label>
<div>

## Main changes

- read sh status from mainpage
- sensor_hub: change fifo_batch_sh_slave_xxx() API name
- sensor_hub: add sh_status_get() API
- sensor_hub: change sh_read_data_raw_get() API signature
- lsm6dsv_reg.c: review read/write reg ret value checks
- lsm6dsv_STdC: Align to DS V3.0

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V1.2.0 / 23-May-2023</label>
<div>

## Main changes

- Use a single lsm6dsv_sh_slv_cfg_read() API for all targets
- Use a single lsm6dsv_fifo_sh_batch_slave_xxx() API for all targets
- Fix MISRA errors

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V1.2.1 / 25-July-2023</label>
<div>

## Main changes

- Fix gyro FS 4000dps value typo error

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Align to lsm6dsv16x driver in term of style and bug fixing
- Fix code style
- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section7" checked aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V2.0.1 / 02-May-2024</label>
<div>

## Main changes

- Fix BDR counter regsters get/set APIs

##

</div>
:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSV,
visit:
[LSM6DSV](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsv.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 1.0">Info</abbr>
:::
:::
</footer>
