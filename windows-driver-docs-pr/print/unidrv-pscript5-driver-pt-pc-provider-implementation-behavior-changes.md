---
title: Unidrv/PScript5 driver PT/PC provider implementation behavior
description: Unidrv and PScript5 driver PrintTicket or print provider (PT/PC) implementation behavior changes
ms.date: 04/20/2017
---

# Unidrv/PScript5 driver PT/PC provider implementation behavior changes


When running in XPSDrv mode, a Unidrv or PScript5 driver's PrintTicket or print provider (PT/PC) implementation must also disable any Unidrv/PScript5 hard-coded features. That is, the PrintCapabilities XML should not contain any hard-coded capabiity, and the default PrintTicket or validated PrintTicket should not contain any hardcoded features.

 

 


