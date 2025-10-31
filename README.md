## Call Centre Performance Dashboard

### Project Overview

This Power BI project provides a comprehensive, interactive dashboard for monitoring and analyzing the key trends and performance indicators (KPIs) of a call center operation. The goal is to offer actionable insights into agent productivity, customer service efficiency, and overall operational health, enabling timely decision-making and performance improvements.

The dashboard, titled **"CALL CENTRE TRENDS,"** aggregates data to provide a high-level view of call volume, handling times, resolution rates, and agent performance.

### Key Performance Indicators (KPIs)

The dashboard prominently features six critical KPIs, providing an immediate snapshot of the call center's performance:

| Metric | Description | Example Value (from screenshot) |
| :--- | :--- | :--- |
| **Total Calls** | The total number of inbound calls handled over the period. | 5,000 |
| **Total Answered Calls** | The total number of calls successfully connected to an agent. | 4,054 |
| **Total Abandoned Calls** | The total number of calls dropped by the caller before connecting to an agent. | 946 |
| **Average Handle Time (s)** | The average duration of a complete call transaction (talk time + wrap-up). | 224.92 seconds |
| **Average Speed of Answer** | The average time a caller waits before being connected to an agent. | 67.52 seconds |
| **Average Satisfaction Rate** | The mean customer satisfaction score (e.g., from post-call surveys). | 3.40 (on a 5.0 scale) |

### Dashboard Visualizations and Analysis

The project includes several interactive charts to dissect performance data:

1.  **Answered vs Abandoned (Donut Chart):**
    * Visually represents the call answering efficiency, highlighting the **18.92% abandonment rate**, which is a key area for operational focus.

2.  **Resolved vs Unresolved (Pie Chart):**
    * Shows the efficacy of the agents in resolving issues on the first contact (**89.94% Resolved**).

3.  **Calls by Time Period (Bar Chart):**
    * Identifies peak call volumes, showing, for example, that the **Afternoon** period has the highest traffic. This is crucial for optimizing staffing levels.

4.  **Total calls by Topic (Bar Chart):**
    * Categorizes call drivers by topic (e.g., Streaming related, Payment related, Technical Support, Admin support, Contract related) to identify systematic issues or training needs.

5.  **Total calls Answered by Agents (Bar/Table):**
    * Ranks individual agent performance by the number of answered calls, allowing managers to easily identify top performers (e.g., Jim) and agents who may require additional support.

### Technical Requirements
* **Visualization Tool:** Microsoft Power BI Desktop
* **Data Model:** A star schema (assumed) linking facts (calls) to dimensions (Agents, Time, Topic, Resolution Status).

### Setup and Usage
To view and interact with this dashboard:

1.  **Prerequisites:** Ensure you have **Power BI Desktop** installed on your machine.
2.  **Clone Repository:** Clone or download this project to your local machine.
3.  **Open File:** Locate and open the `.pbix` file (e.g., `Call_Centre_Trends.pbix`) in Power BI Desktop.
4.  **Data Refresh:** To update the data, you may need to re-point the data sources to your live SQL server, spreadsheet, or data warehouse, and click **Refresh**.
