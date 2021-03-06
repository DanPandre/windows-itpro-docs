---
title: Software developer FAQ
ms.reviewer: 
description: This page provides answers to common questions we receive from software developers
keywords: wdsi, software, developer, faq, dispute, false-positive, classify, installer, software, bundler, blocking
search.product: eADQiWindows 10XVcnh
ms.prod: m365-security
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: ellevin
author: levinec
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance
ms.topic: article
ms.technology: mde
---

# Software developer FAQ

This page provides answers to common questions we receive from software developers. For general guidance about submitting malware or incorrectly detected files, read the submission guide.

## Does Microsoft accept files for a known list or false-positive prevention program?

No. We don't accept these requests from software developers. Signing your program's files in a consistent manner, with a digital certificate issued by a trusted root authority, helps our research team quickly identify the source of a program and apply previously gained knowledge. In some cases, this might result in your program being quickly added to the known list. Far less frequently, in will add your digital certificate to a list of trusted publishers.

## How do I dispute the detection of my program?

Submit the file in question as a software developer. Wait until your submission has a final determination.

If you're not satisfied with our determination of the submission, use the developer contact form provided with the submission results to reach Microsoft. We'll use the information you provide to investigate further if necessary.

We encourage all software vendors and developers to read about [how Microsoft identifies malware and Potentially Unwanted Applications (PUA)](criteria.md).

## Why is Microsoft asking for a copy of my program?

Providing copies can help us with our analysis. Participants of the [Microsoft Active Protection Service (MAPS)](https://www.microsoft.com/msrc/mapp) may occasionally receive these requests. The requests will stop once our systems have received and processed the file.

## Why does Microsoft classify my installer as a software bundler?

It contains instructions to offer a program classified as unwanted software. You can review the [criteria](criteria.md) we use to check applications for behaviors that are considered unwanted.

## Why is the Windows Defender Firewall blocking my program?

Firewall blocks aren't related to Microsoft Defender Antivirus and other Microsoft antimalware. [Learn about Windows Defender Firewall](../windows-firewall/windows-firewall-with-advanced-security.md).

## Why does the Microsoft Defender Windows Defender SmartScreen say my program isn't commonly downloaded?

This isn't related to Microsoft Defender Antivirus and other Microsoft antimalware. [Learn about Microsoft Defender Windows Defender SmartScreen](../microsoft-defender-smartscreen/microsoft-defender-smartscreen-overview.md)