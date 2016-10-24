---
# required metadata

title: Connect and query SQL Server on Linux | SQL Server vNext CTP1
description: 
author: rothja 
ms.author: jroth 
manager: jhubbard
ms.date: 10-20-2016
ms.topic: article
ms.prod: sql-non-specified
ms.service: 
ms.technology: 
ms.assetid: 

# optional metadata

# keywords: ""
# ROBOTS: ""
# audience: ""
# ms.devlang: ""
# ms.reviewer: ""
# ms.suite: ""
# ms.tgt_pltfrm: ""
# ms.custom: ""
---
# Connect and query SQL Server on Linux

This topic provides an overview of how to connect and run Transact-SQL (TSQL) queries on SQL Server vNext CTP1 running on Linux. In many ways the connection techniques and T-SQL commands do not differ between platforms. But this topic looks at the requirements and tools for Linux and then provides references to other resources.

## Connection requirements

In order to remotely connect to SQL Server on Linux, you must open the port that SQL Server is listening on. The default instance of SQL Server listens on TCP port 1433.

## Connection scenarios
There are several tools that you can use to connect and query SQL Server.

- sqlcmd.exe
- Visual Studio Code
- SQL Server Management Studio (SSMS)

### sqlcmd.exe
Sqlcmd.exe is a command line tool that can be run from any Windows or Linux machine that has the SQL Server tools installed. It has a basic interface but is good for quickly connecting and running T-SQL commands. For a walkthrough of using sqlcmd.exe on Linux, see [Connect and query SQL Server on Linux (SqlCmd)](sql-server-linux-connect-and-query-sqlcmd.md).

### Visual Studio Code
Visual Studio Code is a lightweight, cross-platform development tool for writing code. The MSSQL extension provides the ability to execute TSQL commands. This is especially useful in development scenarios where you need to write both application code and database functionality. For more information, see [Connect and query SQL Server on Linux (VS Code)](sql-server-linux-connect-and-query-vs-code.md).

### SQL Server Management Studio (SSMS)
SQL Server Management Studio is a Windows tool for both querying and managing SQL Server instances. This is best for when you are working with both Windows and Linux machines. You can connect SSMS running on Windows to SQL Server running on Linux. The advantage of SSMS is that it provide a graphical user interface for many server and database management tasks. For more information, see [Connect and query SQL Server on Linux (SSMS)](sql-server-linux-connect-and-query-ssms.md).

## Next Steps
TBD