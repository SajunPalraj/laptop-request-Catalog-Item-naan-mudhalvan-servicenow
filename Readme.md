# ServiceNow Laptop Request Catalog (Naan Mudhalvan Project)

![ServiceNow](https://img.shields.io/badge/ServiceNow-Platform-brightgreen?style=for-the-badge&logo=servicenow)

This project was developed as part of the **Naan Mudhalvan** program, a large-scale upskilling initiative by the Government of Tamil Nadu. This project was completed for the "ServiceNow System Administrator" certification track.

**Project Demo Link:** [**Watch the Video Demo on Google Drive**](https://drive.google.com/file/d/16DtiT50C-msj4VGsBRl_PC0kutw-Gkqt/view?usp=drive_link)

---

## 1. Project Abstract

This project focuses on developing a ServiceNow Catalog Item that streamlines the laptop request process within an organization. The existing manual system causes delays and inaccuracies due to a lack of automation and dynamic guidance. The proposed solution introduces a user-friendly, interactive Service Catalog form that allows employees to quickly and accurately request laptops.

## 2. Problem Statement

Employees in the organization need a quick and efficient way to request laptops for work. The current process is manual and prone to delays, with no dynamic form behavior to guide users or ensure accurate data collection. This project solves that by creating a single, automated, and intelligent form.

## 3. What is ServiceNow?

ServiceNow is a powerful cloud-based platform that automates IT and business workflows. It helps organizations manage digital processes and services by replacing unstructured, manual tasks with intelligent automation. This project uses the **Service Catalog** module, which allows IT departments to offer a "storefront" of services (like requesting a laptop) to employees in a user-friendly way.

---

## 4. Key Project Features

This catalog item includes several key features to improve the user experience and ensure data accuracy:

* **Dynamic Form:** Uses **Catalog UI Policies** to dynamically show or hide fields based on user selections. For example, a "Graphics Card" option only becomes visible and mandatory if a "High-End" laptop is selected.
* **Form Usability (UI Action):** A "Reset Form" button was added using a **UI Action**. This button runs a client-side JavaScript snippet to clear all fields, allowing users to start over easily.
* **Deployment Ready:** The entire project (item, variables, policies, scripts) is captured in a single **Update Set**, allowing it to be easily exported from a development instance and imported into a testing or production instance.

---

## 5. Project Visuals

### Development Flowchart

This flowchart outlines the entire development and testing process for the project.

![Project Development Flowchart](https://github.com/SajunPalraj/laptop-request-Catalog-Item-naan-mudhalvan-servicenow/blob/main/Planning%20Phase/project%20flow%20chart.png)

### Final Output

This screenshot shows the final "Order Status" page after a user successfully submits a request through the new catalog item.

![Final Project Output](https://github.com/SajunPalraj/laptop-request-Catalog-Item-naan-mudhalvan-servicenow/blob/main/Output%20Phase/service-now.com.png)

---

## 6. Technology Stack

* **Platform:** ServiceNow
* **Modules:** Service Catalog, Update Sets
* **Components:** Catalog UI Policy, UI Action
* **Scripting Language:** JavaScript (for client-side scripts)

---

## 7. How to Install & Test

You can deploy this entire project in your own ServiceNow Personal Developer Instance (PDI):

1.  Navigate to the `update-set` folder in this repository and download the `.xml` file.
2.  In your ServiceNow instance, navigate to **System Update Sets > Retrieved Update Sets**.
3.  Click the link **"Import Update Set from XML"**.
4.  Choose the `.xml` file you downloaded and click **Upload**.
5.  Once uploaded, open the update set, **Preview** it, and then **Commit** it.
6.  The "Laptop Request" item will now be available in your Service Catalog.

---

## 8. Project Team Members

This project was a collaborative effort.

| Name | Role | Naan Mudhalvan ID |
| :--- | :--- | :--- |
| **Rajasekar R K** | **Team Leader** | `B9DCBD8AABF8E389F4941BB93FA926F1` |
| Sajun Palraj | Team Member | `A3724D9FDA64B37B01C4CB4763C5751C` |
| Pavithran S R | Team Member | `438FCA6EBFA448C82A44D071F459293B` |
| Lekshmikanth L | Team Member | `ED55D06E3F534D1A83E43E80BDA56E41` |
