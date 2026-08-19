📊 Data Analysis: Technical Support Performance Dashboard
🔍 Discoveries

The dataset contains key indicators for a technical support line, including:

Survey results (customer satisfaction).
Number of interactions (volume of support activity).
SLA compliance (adherence to response and resolution deadlines).

Channel differences: Response times for chat and phone differ significantly from email, impacting SLA metrics.
Opportunities identified: Variations in response and resolution times across categories and lines of business (LOB) reveal areas for improvement.

🧹 Data Cleaning & Preparation

Standardized SLA Metrics:

Converted SLA first response and resolution into binary (Y/N) for quantifiable analysis.

Handled Missing Data:

Filled empty values for close and resolution times to ensure completeness.

Categorized Support Lines:

Defined Lines of Business (LOB) to align with organizational structure.

Added Time-Based Aggregation:

Created a Quarter column (based on ticket creation date) to enable time-series analysis and dashboard filtering.


📈 Analysis & Visualization

Shifted Focus:

Transitioned from individual agent performance to category and LOB-level insights to identify systemic trends.

Compiled Supporting Reports:

Generated pivot tables (saved as supporting_pivots sheet) for deeper analysis.

Dashboard Charts:

Bar charts to showcase:

Case handling by quarter.
Quality and interactions by agent.

Survey Performance:

Added linear trendlines to agent survey charts to highlight top vs. bottom performers.

Geographic Participation:

Included a country-based chart to show ticket handling distribution across regions.


