---
layout: connectors-tutorial-single_layout
title: Connect Your Charts and Dashboards to Parquet files with Apache Drill
subtitle: Graph data from your Parquet files using Apache Drill database with Chart Studio and Falcon.
permalink: /database-connectors/apache-drill/
imageurl:  /static/images/falcon/logos/apache-drill.png
state: active
tags: other
section: Basics
meta_description: Follow these steps to connect to your Parquet files using Apache Drill
popularity: featured
actioncall-url: https://github.com/plotly/electron-sql-connector/releases

steps:
 - title: Download and Install Falcon
   sub-steps:
    - copy: "If you haven't downloaded and installed Falcon yet, please follow the instructions for either [personal setup](https://help.plot.ly/database-connectors/personal-login/) or [company on-premise](https://help.plot.ly/database-connectors/on-prem-login/)."
 - title: Launch and Connect
   sub-steps:
    - copy: "After launching Falcon, select *Apache Drill* by clicking on its icon."
      img: "![Connect](/static/images/falcon/apache-drill/apache-drill.png)"
    - copy: "Enter your host, port number, S3 bucket name, access key ID, secret access key and click *CONNECT*."
      img: "![Credentials](/static/images/falcon/apache-drill/credentials.png)"
    - copy: "Have no database? Try it out with our read-only Apache Drill database. Simply, click Show Sample Credentials, copy, paste and click *CONNECT*."
      img: "![Sample Credentials](/static/images/falcon/apache-drill/sample-credentials.png)"
    - copy: "Once connection is established, your connection credentials will be saved and greyed out to avoid unintentional changes. If you wish to modify your connection, click on *Edit Credentials*."
      img: "![Edit Credentials](/static/images/falcon/apache-drill/edit-credentials.png)"
 - title: Query
   sub-steps:
    - copy: "For a tutorial on the query tab, which features schema preview, the ability execute sql queries, perform inline data visualization, preview tables and export CSV files, see [Query From Falcon](https://help.plot.ly/database-connectors/query-from-falcon/)."
 - title: Query Apache Drill From Chart Studio
   sub-steps:
    - copy: "If you want to unlock the full power of Chart Studio, you can click the PLOT.LY tab and QUERY [DATABASE] FROM Chart Studio. To learn more about this feature, navigate to the [Query From Chart Studio](https://help.plot.ly/database-connectors/query-from-plotly/) tutorial."
 - title: Plotting in Chart Studio
   sub-steps:
    - copy: "If you opted to run your queries from Chart Studio, check out our [Chart Studio](https://help.plot.ly/tutorials/) tutorials to add interactivity and styling."

---
