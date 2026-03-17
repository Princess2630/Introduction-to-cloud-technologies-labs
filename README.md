# Azure Cloud Technologies Labs - Full-Stack Portfolio ☁️

This repository documents a comprehensive journey through Microsoft Azure, evolving from foundational data storage to advanced event-driven architectures and serverless application integration.

---

##  Lab 01: Scalable Data Storage in Azure
*Focus: NoSQL Databases and Blob Storage Management*

<details>
<summary><b>📂 View Full Project Walkthrough (10 Screenshots)</b></summary>

### **Phase 1: NoSQL Database (Cosmos DB) Setup**
| Step 1: Provisioning | Step 2: Resource Overview | Step 3: Data Explorer |
| :---: | :---: | :---: |
| <img src="./images/azure2_1.png" width="250"> | <img src="./images/azure2_2.png" width="250"> | <img src="./images/azure2_3.png" width="250"> |
| *Creating the Cosmos DB account* | *Database dashboard & metrics* | *Accessing the SQL API interface* |

### **Phase 2: JSON Document & Schema Management**
| Step 4: Container Creation | Step 5: Item Entry | Step 6: JSON Structure |
| :---: | :---: | :---: |
| <img src="./images/azure2_4.png" width="250"> | <img src="./images/azure2_5.png" width="250"> | <img src="./images/azure2_6.png" width="250"> |
| *Defining the 'Songs' collection* | *Adding new data items* | *Verifying metadata schema* |

### **Phase 3: Blob Storage & File Management**
| Step 7: Storage Account | Step 8: Container Logic | Step 9: Access Tiers | Step 10: Final Verification |
| :---: | :---: | :---: | :---: |
| <img src="./images/azure2_7.png" width="200"> | <img src="./images/azure2_8.png" width="200"> | <img src="./images/azure2_9.png" width="200"> | <img src="./images/azure2_10.png" width="200"> |
| *Provisioning storage* | *Creating image containers* | *Blob property settings* | *Successful storage deployment* |

**Key Takeaways:** * Successfully implemented **Cosmos DB** for high-velocity metadata storage.
* Managed unstructured data via **Azure Blob Storage** with dedicated containers for ingestion.
* Validated data integrity using the **Data Explorer** tool.

</details>
---

##  Lab 02: Running Applications in Azure
*Focus: Azure App Service and Serverless Functions*

<details>
<summary><b>📂 View Full Project Walkthrough (10+ Screenshots)</b></summary>

### **Implementation Highlights**
* **Azure App Service:** Deployed the "Psotify" web application to a live cloud environment.
* **Azure Functions:** Implemented serverless HTTP triggers to handle backend logic with automatic scaling.
* **Monitoring:** Used Application Insights to troubleshoot "500 Internal Server Errors."

| Step 1: App Service Setup | Step 2: Deployment Status | Step 3: Live Application |
| :---: | :---: | :---: |
| <img src="./images/azure3_1.png" width="250"> | <img src="./images/azure3_4.png" width="250"> | <img src="./images/azure3_5.png" width="250"> |
| *Creating Web App resources* | *Deployment success logs* | *Live Psotify API endpoint* |

| Step 4: Function Setup | Step 5: Error Diagnostics | Step 6: Log Streaming |
| :---: | :---: | :---: |
| <img src="./images/azure3_7.png" width="250"> | <img src="./images/azure3_8.png" width="250"> | <img src="./images/azure3_9.png" width="250"> |
| *Developing Serverless triggers* | *Root cause analysis in logs* | *Real-time console output* |

</details>

---

##  Lab 03: Integrating Applications in Azure
*Focus: Decoupled Architecture & Service Bus Messaging*

<details>
<summary><b>📂 View Full Project Walkthrough (10+ Screenshots)</b></summary>

### **Implementation Highlights**
* **Azure Service Bus:** Implemented asynchronous messaging using the publish-subscribe pattern.
* **Queue Management:** Created the `newsongqueue` to decouple the API from the backend processor.
* **Logic Apps:** Integrated automated workflows to react to messaging events.

| Step 1: Service Bus Setup | Step 2: Queue Creation | Step 3: API Development |
| :---: | :---: | :---: |
| <img src="./images/azure4_1.png" width="250"> | <img src="./images/azure4_2.png" width="250"> | <img src="./images/azure4_3.png" width="250"> |
| *Provisioning the namespace* | *Configuring newsongqueue* | *Building the Async backend* |

| Step 4: Topic Setup | Step 5: Logic App Flow | Step 6: Execution Logs |
| :---: | :---: | :---: |
| <img src="./images/azure4_10.png" width="250"> | <img src="./images/azure4_13.png" width="250"> | <img src="./images/azure4_15.png" width="250"> |
| *Pub-Sub topic broadcasting* | *Visualizing the workflow* | *Message processing success* |

</details>

---

##  Lab 04: The "Face-Anonymizer" - Final Integration
*Focus: Full-Stack Integrated Cloud Solution*

<details>
<summary><b>📂 View Full Project Walkthrough (10+ Screenshots)</b></summary>

### **Final Project Workflow**
1. **Ingestion:** User-uploaded images are stored in a "requested" Blob container.
2. **Messaging:** An `anonymizationrequested` message is sent to the Service Bus Queue.
3. **Persistence:** User metadata and processing status are tracked in Azure Cosmos DB.
4. **Completion:** The processed image is moved to the "completed" container for retrieval.

| Step 1: Web Interface | Step 2: Queue Logic | Step 3: Storage Workflow |
| :---: | :---: | :---: |
| <img src="./images/azure5_10.png" width="250"> | <img src="./images/azure5_7.png" width="250"> | <img src="./images/azure5_8.png" width="250"> |
| *The Face-Anonymizer UI* | *Handling request messages* | *Blob lifecycle management* |

| Step 4: Cosmos DB Logs | Step 5: Solution Structure | Step 6: Final Verification |
| :---: | :---: | :---: |
| <img src="./images/azure5_12.png" width="250"> | <img src="./images/azure5_11.png" width="250"> | <img src="./images/azure5_9.png" width="250"> |
| *Anonymization metadata* | *Project file hierarchy* | *End-to-end system success* |

</details>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%">
</p>

<p align="center">
  <b>   | MSc Cybersecurity Candidate</b><br>
  <i>Current Focus: Cloud Security, Serverless Architectures, and System Integration</i>
</p>

<p align="center">
  <a href="https://github.com/Princess2630">
    <img src="https://img.shields.io/badge/Follow-Princess2630-blue?style=for-the-badge&logo=github" alt="Follow on GitHub">
  </a>
</p>
