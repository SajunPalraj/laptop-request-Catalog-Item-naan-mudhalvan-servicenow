# Project Update Set (XML)

This folder contains the final output of the "Laptop Request Catalog" project, exported as a single XML file.

This file is a **ServiceNow Update Set**. It bundles all the project components (the catalog item, variables, UI policies, UI actions, etc.) into one package that can be easily imported into any other ServiceNow instance for testing or deployment.

---

## 🚀 How to Install This Project

You can deploy and test this project in your own ServiceNow Personal Developer Instance (PDI) by following these steps:

1.  **Download:**
    Download the `.xml` file located in this folder.

2.  **Navigate to Retrieved Update Sets:**
    In your ServiceNow instance, use the filter navigator to go to `System Update Sets > Retrieved Update Sets`.

3.  **Import:**
    At the bottom of the list, click the link that says **"Import Update Set from XML"**.

4.  **Upload:**
    Click **"Choose File"**, select the `.xml` file you just downloaded, and click **"Upload"**.

5.  **Preview:**
    Once uploaded, find the update set in the list (it will be named "Project - Laptop Request Catalog" or similar). Open it and click the **"Preview Update Set"** button.

6.  **Commit:**
    After the preview finishes successfully (it should show no errors), click the **"Commit Update Set"** button.

Once committed, the "Laptop Request" catalog item and all its associated workflows and logic will be fully installed in your instance.
