---
title: PCL XL Issues
description: PCL XL Issues
keywords:
- PCL XL vector graphics WDK Unidrv , additional considerations
ms.date: 04/20/2017
---

# PCL XL Issues





-   Windows XP and later supports print optimization functionality on the **Advanced** tab of the printer property pages. If **Print Optimizations** are disabled, Unidrv prints PCL XL data in raster mode.

-   \*MirrorRasterPage? is not supported in PCL XL mode.

-   PCL XL does not support switching between PCL XL and raster modes.

-   The GPD \*TextHalftoneThreshold attribute name is not supported on a PCL XL minidriver. Text in any resolution is grayscaled in PCL XL mode.

 

 




