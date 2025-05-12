# dp-700-lab-13

# Real-Time Bike Dashboard with Microsoft Fabric

This project demonstrates how to build a real-time analytics dashboard using Microsoft Fabric's Real-Time Intelligence tools.

## 🧩 Features

- Stream ingestion via Eventstream using sample "Bicycles" data
- Real-time visualization using KQL-based dashboards
- Interactive tiles (bar chart & map) showing live bike availability by neighborhood
- Parameter-based filtering by neighborhood
- Base queries for code reuse and optimization
- Auto-refreshing dashboard
- Multi-page layout

## 🚀 Technologies Used

- Microsoft Fabric
- Eventhouse
- Eventstream
- KQL (Kusto Query Language)
- Real-Time Dashboards

## 🛠️ Setup Instructions

1. Create a workspace in Microsoft Fabric with Fabric capacity.
2. Add an Eventhouse and link it to an Eventstream using sample "Bicycles" data.
3. Use KQL to build a dashboard with:
   - Bar chart for bikes and empty docks
   - Map for bike locations
4. Create a base query to manage shared data.
5. Add a parameter to filter data by neighborhood.
6. Enable auto-refresh (30-minute interval).
7. Save and share your dashboard!

## 📦 Cleanup

To remove the workspace and free up resources, go to Workspace Settings > Remove this workspace.

## 📸 Screenshot


https://github.com/user-attachments/assets/579396f8-99a0-4d60-9e02-39e39e2088d5




---
