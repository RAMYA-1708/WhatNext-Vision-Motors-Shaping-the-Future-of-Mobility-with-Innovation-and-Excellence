# WhatNext-Vision-Motors-Shaping-the-Future-of-Mobility-with-Innovation-and-Excellence

# WhatsNext Vision Motors – Salesforce CRM Transformation

## Project Overview
WhatsNext Vision Motors embarked on a Salesforce CRM transformation to modernize vehicle order processing, dealer management, and customer engagement. This digital initiative automated manual workflows, reduced order errors, and empowered real-time business decisions.

## Objectives
- Automate dealer assignment and vehicle ordering workflows.
- Implement real-time stock validation during order placement.
- Send automated reminders for test drives.
- Enable real-time dashboards for business insights.
- Reduce manual workload and processing delays.

## Technologies Used
- Salesforce Platform
- Lightning App Builder
- Flow Builder
- Apex Triggers & Classes
- Batch Apex & Scheduled Apex
- Reports & Dashboards

## Key Features

### Dealer Assignment Automation
Using Salesforce Flows, customers are automatically assigned to the nearest authorized dealer based on their city or location.

### Stock Validation via Apex
Apex triggers and handlers validate vehicle stock availability before accepting orders, preventing overbooking and cancellations.

### Batch & Scheduled Apex
A nightly batch job updates pending orders based on updated stock, ensuring timely fulfillment without manual intervention.

### Test Drive Reminder Flow
Flow automation sends email reminders to customers a day before their scheduled test drives, reducing no-shows.

### Dashboards & Reports
Real-time dashboards show order status, inventory levels, and dealer performance—helping management make quick, data-driven decisions.

### 📁 Project Folder Structure

```
WhatsNext-Vision-Motors-Salesforce-CRM/
│
├── apex/
│   ├── VehicleOrderTrigger.trigger
│   ├── VehicleOrderHandler.cls
│   ├── VehicleOrderBatch.cls
│   └── VehicleOrderBatchScheduler.cls
│
├── flows/
│   ├── DealerAssignmentFlow.flow-meta.xml
│   └── TestDriveReminderFlow.flow-meta.xml
│
├── objects/
│   ├── Vehicle__c.object-meta.xml
│   ├── Dealer__c.object-meta.xml
│   └── Customer__c.object-meta.xml
│
├── reports_dashboards/
│   ├── OrderSummaryDashboard.dashboard-meta.xml
│   └── DealerPerformanceDashboard.dashboard-meta.xml
│
├── README.md
```
