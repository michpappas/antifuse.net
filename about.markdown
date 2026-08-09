---
layout: page
title: About
permalink: /about/
---

This is a collection of integrated circuit photography taken using my custom-built IC imaging system, aka afscope.
You can also find my die-shots at [siliconpr0n.org](https://siliconpr0n.org/).

### Imaging Setup

![afscope](/assets/afscope-gen2.jpeg){:style="display:block; margin-left: auto; margin-right: auto;"}

**Microsocope Body:** Olympus BXF-M parts with modified BH2-UMA epi-illumination.
* Tube lenns: [U-TLU](https://evidentscientific.com/en/oem-components/tube-lens-units) (Φ22μμ, 1x, f180).
* Focusing unit: [BXFM-F](https://evidentscientific.com/de/products/upright/bxfm)
* Nosepiece: U-5RE-2 (quintuple)
* Epi-illumination: Olympus [BH2-UMA](https://www.alanwood.net/downloads/olympus-bh2-uma-instructions.pdf) with tube lens removed. Halogen lamp replaced with 18mm fiber adapter.
* Camera adapter: [U-TV1X-2 + U-CMAD3](https://share.google/7BoNqjjb5tA8F7tVv)
* Custom-built aluminum adapters to connect epi-illumination

**Microscope Stand:**
* Unbranded aluminum stand with custom-built aluminum BXFM-F adapter.

**Illumination:** CCS RGB illumination with randomized fiber bundle.

* Fiber bundle: [HFS-14-500](https://www.ccs-grp.com/products/model/1660) 18mm, randomized.
* Head: [HLV2-3M-RGB-3W](https://www.ccs-grp.com/products/model/1676).
* LEDs: [HLV2-22RD-NR-3W](https://www.ccs-grp.com/products/model/1672)(645nm), [HLV2-22RD-NG-3W]()(520nm), [HLV2-22RD-NB-3W](https://www.ccs-grp.com/products/model/1674)(456nm).
* Controller: [PJ-1505-3CA](https://static.optosigma.com/en/page_pdf/1666832372_M_PJ_e.pdf).

**Camera:** [Rasperry Pi HQ](https://pip-assets.raspberrypi.com/categories/659-raspberry-pi-high-quality-camera/documents/RP-008202-DS-1-hq-camera-product-brief.pdf)

**XY Stage:** Refurbished Zolix TSA30-C
* Stage: [Zolix TSA30-C](https://www.zolix.com.cn/filespath/files/Motion%20Control/MotorizedStages-en/TSAxx-C.pdf).
* Controller: [BigTreeTech Octopus V1.1](https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-V1.0/blob/master/BIGTREETECH_Octopus_EN_updated_0719.pdf) controlled with Marlin.
* PSU: [Meanwell LRS-350-24](https://www.meanwell.eu/productPdf.aspx?i=459).

**Z Stage:** DIY stick-slip piezo stage
* Based on the [Low-cost, open source XYZ nanopositioner for high precision analytical applciations](https://www.hardware-x.com/article/S2468-0672(22)00062-1/fulltext) paper by Hsien-Shun Liao et al.
* Custom 3.3V to 150V piezo driver

**Tilt Stage:** Generic 2-axis goniometer

**Objectives**: Olympus LMplanFL 5x/0.13 BD, Olympus UMplanFL 10x BD, Olympus UPlanSApo 20x / 0.75, Olympus MPlan N 50x/0.75.

**Software**: Custom-built control and imaging software.

### Old Microscope

![afscope](/assets/afscope.jpeg){:style="display:block; margin-left: auto; margin-right: auto;"}

| Component | Details |
|----------|---------|
| **Stand** | Olympus BH2 BHT mounted on a 20cm x 30cm optical breadboard.
| **Epi-illumination** | Olympus BH2 UMA with brightfield and darkfield cubes. Halogen lamp replaced with high power LED and passive cooling. |
| **Head** | Olympus BH2-TR30 trinocular observation tube with Olympus WHK10x/20 widefield eyepieces. |
| **Camera** | Basler aca2500 20gc. 2592 x 2048, 4.8um x 4.8um pixel size, 1" sensor with 15.9mm diagonal, global shutter. |
| **Objectives** | Olympus LMplanFL 5x/0.13 BD, Olympus UMplanFL 10x BD, Olympus UPlanSApo 20x / 0.75, Olympus MPlan N 50x/0.75. |
| **Stage** | XYZ precision linear stage + 2-axis precision goniometer stage. Custom built motorization based on the [UC2-MicronStage](https://github.com/openUC2/UC2-MicronStage), controlled with GRBL. |
| **Software** | Custom built control and imaging software. |
