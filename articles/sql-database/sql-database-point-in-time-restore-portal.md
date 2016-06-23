<properties
	pageTitle="Restore an Azure SQL Database to a previous point in time (Azure Portal) | Microsoft Azure"
	description="Restore an Azure SQL Database to a previous point in time."
	services="sql-database"
	documentationCenter=""
	authors="stevestein"
	manager="jhubbard"
	editor=""/>

<tags
	ms.service="sql-database"
	ms.devlang="NA"
	ms.date="06/17/2016"
	ms.author="sstein"
	ms.workload="sqldb-bcdr"
	ms.topic="article"
	ms.tgt_pltfrm="NA"/>


# Restore an Azure SQL Database to a previous point in time with the Azure Portal


> [AZURE.SELECTOR]
- [Overview](sql-database-point-in-time-restore.md)
- [Azure portal](sql-database-point-in-time-restore-portal.md)
- [PowerShell](sql-database-point-in-time-restore-powershell.md)

This article shows you how to restore your database to an earlier point in time from [SQL Database automated backups](sql-database-automated-backups.md) using the Azure Portal.

## Select a database to restore to a previous point in time

To restore a database in the Azure Portal do the following:

1.	Open the [Azure Portal](https://portal.azure.com).
2.  On the left side of the screen select **BROWSE** > **SQL databases**.
3.  Navigate to the database you want to restore and select it.
4.  At the top of your database's blade, select **Restore**:

    ![Restore an Azure SQL database](./media/sql-database-point-in-time-restore-portal/restore.png)

5.  Specify a database name, point in time and then click Ok:

    ![Restore an Azure SQL database](./media/sql-database-point-in-time-restore-portal/restore-details.png)


## Next steps

- For detailed steps to recover to a point in time using PowerShell, see [Point-In-Time Restore using PowerShell](sql-database-point-in-time-restore-powershell.md).
- For information about how to recover to a point in time using the REST API, see [Point-In-Time Restore using the REST API](https://msdn.microsoft.com/library/azure/mt163685.aspx).
- For an overview of point in time restore, see [Point-In-Time Restore](sql-database-point-in-time-restore.md).
- For a full discussion about how to recover from a user or application error, see [User error recovery](sql-database-user-error-recovery.md).

## Additional resources

- [Business continuity scenarios](sql-database-business-continuity-scenarios.md)
