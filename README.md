# WPF Blank App with the Northwind Database


This example contains a data access layer generated with Entity Framework Database First. In this example, the blank sample project is connected to the **Northwind** database.

Database structure:

![](/Images/DatabaseStructure.png)

You can use this example to create DevExpress projects and explore our features.

We used the [DevExpress Template Gallery](https://docs.devexpress.com/WPF/16495/whats-installed/template-gallery) to create this project, so it includes the [DevExpress ThemedWindow](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.ThemedWindow) as a root element. Refer to the [Themes](https://docs.devexpress.com/WPF/7406/common-concepts/themes) topic for more information about custom-designed themes.

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
