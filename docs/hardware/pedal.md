---
description: Comma Pedal info and products
---

# Pedal

## About

To enable stop-and-go functionality in some vehicles, a Comma Pedal must be installed. This pedal is created and supported by community members, not by comma.ai. It is compatible with [popular forks](../software/popular-forks.md) of the software.

## Purchase&#x20;

Beartech

{% embed url="https://shop.tlbb.ca/products/comma-pedal-non-customizable-toyota-honda-gm-vw-benz" %}

## Install

Refer to the installation guide below for the Comma Pedal. Ensure your Comma device is running software that supports the pedal.

Reference: [YouTube → Pedal Commander → Accessing the pedal connector](https://youtu.be/Gisbi94opSM?si=H8-fX46Xf-AcuWQm\&t=7)

{% embed url="https://www.figma.com/board/k0BxdkGouE5FyeCBjZRSmG/Camma-Setup?node-id=0-1&t=CnKRu0kSojQWWZZ9-0" %}

## Q & A

<details>

<summary>Will stock openpilot work with a Comma Pedal</summary>

No, openpilot no longer supports the Comma Pedal, use a fork that does support it like FrogPilot or sunnypilot. Comma Pedal is not manufactured by comma either.&#x20;

</details>

<details>

<summary>Will community forks continue to support the Comma Pedal?</summary>

There is obviously no way to know the future, but the forks that currently support it have no plans on dropping support.

</details>

<details>

<summary>How can I update the firmware on the Comma Pedal</summary>

Flashing the firmware is done with the DFU Key, available from Beartech. [See this link](https://shop.tlbb.ca/products/dfu-key) for more information.&#x20;

For pedal/SDSU firmware, check here: [https://github.com/fraserxiong/panda\_firmware](https://github.com/fraserxiong/panda\_firmware).

Tutorial for flashing Pedal: [https://www.youtube.com/watch?v=DNf0OGwXUUQ](https://www.youtube.com/watch?v=DNf0OGwXUUQ)

</details>

## The New Car Harness Issues

Installing the Comma Pedal requires connection to the car harness via RJ45.

**The new** [**harness kit**](https://comma.ai/shop/car-harness) **from comma.ai no longer includes an RJ45 port and is incompatible with the old harness box. Note that the images on the comma.ai website still show the old hardware, but only the new hardware is being sold.**

To use the Comma Pedal, you will need an old harness kit or a community-created one with an RJ45 port. Beartech is currently developing a solution to use the pedal with the new harness.&#x20;

## Reference

Links to code and information regarding the Comma Pedal

| Link                                                                                                                                        | Info                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [GitHub / fraserxiong / panda\_firmware / main\_pedal\_firmware](https://github.com/fraserxiong/panda\_firmware/tree/main\_pedal\_firmware) | Pedal firmware                                                    |
| [YouTube / tlbb studio / Flash Comma Pedal in DFU Mode Tutorial](https://www.youtube.com/watch?v=DNf0OGwXUUQ)                               | Tutorial for flashing Comma Pedal                                 |
| [GitHub / comma.ai / openpilot / wiki / Toyota/Lexus](https://github.com/commaai/openpilot/wiki/Toyota-Lexus)                               | Information regarding Toyota and Lexus integration with openpilot |
