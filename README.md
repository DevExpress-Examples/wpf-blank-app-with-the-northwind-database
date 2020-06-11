# WPF Blank App with the Northwind Database


This example contains a data access layer generated with Entity Framework Database First. In this example, the blank sample project is connected to the **Northwind** database.

Database structure:

![](/Images/DatabaseStructure.png)

You can use this example to create DevExpress projects and explore our features.

To connect your project to a database:

1. Add the **ADO.NET Entity Data Model** to your project:

    ![](/Images/AddDataModel.png)
    
2. In the **Entity Data Model Wizard** select **EF Designer from database**:

    ![](/Images/EntityDataModel.png)
    
3. Click **New Connection**.

4. Select the **Microsoft SQL Server Database File** as a data source and specify the path to a database file:

    ![](/Images/ConnectionProperties.png)
    
5. Connect to a database:

    ![](/Images/CreateDataConnection.png)
    
6. Select tables and views to include them in the model:

    ![](/Images/SelectTables.png)
    
7. Set the database's **Copy to Output Directory** property to **Copy if newer**:

    ![](/Images/DatabaseProperties.png)
