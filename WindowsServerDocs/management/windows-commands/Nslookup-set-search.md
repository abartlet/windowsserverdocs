---
title: Nslookup set search
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 064ac660-8b04-4af9-8b2c-e4e0549771b8
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# Nslookup set search

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Appends the Domain Name System (DNS) domain names in the DNS domain search list to the request until an answer is received. This applies when the set and the lookup request contain at least one period, but do not end with a trailing period.
## Syntax
```
set [no]search
```
## Parameters
|Parameter|Description|
|-------|--------|
|**nosearch**|Stops appending the Domain Name System (DNS) domain names in the DNS domain search list to the request.|
|**search**|Appends the Domain Name System (DNS) domain names in the DNS domain search list to the request until an answer is received. The default syntax is **search**.|
|{help &#124; ?}|Displays a short summary of **nslookup** subcommands.|
## Additional references
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)