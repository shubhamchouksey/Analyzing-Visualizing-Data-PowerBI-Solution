# Exercise 1- Import Data from Access Database

## Lab Steps
VanArsdel's US office stores the sales data on an Access database. You will need to perform analysis on that data, but before you can do so, you need to import the data to Power BI Desktop and perform some transformations.       

**IMPORTANT!** Before you start, if your locale settings is not English (United States), you might want to change this, since the data you will import is based on this locale. This is covered in ["Changing Locale"](https://courses.edx.org/courses/course-v1:Microsoft+DAT207x+2T2017/course/).

1. Download the VanArsdel's [Access database](https://github.com/shubhamchouksey/Analyzing-Visualizing-Data-PowerBI-Solution/blob/master/PowerBI_Lab1/AccessDatabasePowerBI.zip). Extract the file to “C:\DAT207x”. You can use other folders, but if you are going to use the starter file provided at each lab instead of your own file, then it is recommended to use the absolute path given above in order to successfully perform the schedule refresh in Lab 4.

**NOTE:** If you are having issues with the direct link, head over to the github repository and download from there. https://github.com/shubhamchouksey/Analyzing-Visualizing-Data-PowerBI-Solution

2. Click **Start**.
3. Type **Power BI Desktop**.
4. Click **Get data**.
5. Click **Access database**, and click **Connect**.
6. Navigate to **C:\DAT207x**, click **PowerBI.accdb**, and click **Open**.
7. Select **bi_date**, **bi_geo**, **bi_manufacturer**, **bi_product**, and **bi_salesFact** and click **Edit**.
8. In **Queries**, select **bi_salesFact**.
9. Select the **Date** column.
10. Click the **Transform** ribbon.
11. In the **Any Column** group, select **Data Type** and select **Date**.
12. Click the drop-down button at the top of the **Date** column.
13. Click **Date Filters** and click **After**.
14. In the first **Enter or select a value** field, type **12/31/1999** if you are using DD/MM/YYYY dates and **31/12/1999** if you are using DD/MM/YYYY dates and click **OK**.
15. In **Queries**, select **bi_Date**.
16. Select the **Date** column.
17. Click the **Transform** ribbon.
18. In the **Any Column** group, select **Data Type** and select **Date**.
19. Click the drop-down button at the top of the **Date** column.
20. Click **Date Filters** and click **After**.
21. In the first Enter or select a value field, type **12/31/1999** if you are using DD/MM/YYYY dates and **31/12/1999** if you are using DD/MM/YYYY dates and click **OK**.
22. Rename the queries as follows:
- In **Queries**, right click **bi_date**, click **Rename**, replace the text with **Date**, and press **Enter**.
- In **Queries**, right click **bi_geo**, click **Rename**, replace the text with **Locations**, and press **Enter**.
- In **Queries**, right click **bi_manufacturer**, click **Rename**, replace the text with **Manufacturers**, and press **Enter**.
- In **Queries**, right click **bi_product**, click **Rename**, replace the text with **Products**, and press **Enter**.
- In **Queries**, right click **bi_salesFact**, click **Rename**, replace the text with **Sales**, and press **Enter**.
23. Click the **Home** ribbon.
24. Click **Close and Apply**.
25. Click **Data** and explore the imported data in the Data View
