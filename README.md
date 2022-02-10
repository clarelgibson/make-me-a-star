# Make Me A Star
A collection of projects to transform raw or flat data into a "star schema" model for use in BI tools (primarily Power BI).

The [star schema](https://en.wikipedia.org/wiki/Star_schema) is considered [best practice](https://docs.microsoft.com/en-us/power-bi/guidance/star-schema) for developing business intelligence (BI) data models and data warehouses that are optimized for performance and usability. It is the system of modeling that is most recommended for use in the BI tool [Power BI](https://powerbi.microsoft.com/en-gb/).

In this repository I aim to showcase various examples of creating a star schema from raw data. While the primary target of these models is for use in Power BI, and while it is perfectly possible to build a star schema using Power BI infrastructure ([Power Query](https://powerquery.microsoft.com/en-us/) and [DAX](https://support.microsoft.com/en-gb/office/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a)), for the purposes of my repository I intend to create the required tables using R so that the steps taken to reach the star model can be easily documented.
