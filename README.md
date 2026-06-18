# Financial-Complaints-Dashboard
An interactive Power BI report that provides an end-to-end overview of financial consumer complaints — tracking volume, response performance, dispute rates, and geographic distribution to support data-driven insights for compliance and customer experience teams.
Dashboard Preview


<img width="1278" height="750" alt="Financial Complaints" src="https://github.com/user-attachments/assets/f9a39f45-c104-4805-9400-3bd06bbdbdf9" />





📋 Report Overview

PropertyDetailsToolMicrosoft Power BI DesktopFileFinancial_Complaints_Overview.pbixPages1 (Overview)Data SourceFinancial Consumer Complaints dataset


🔢 KPI Cards

Five summary cards anchor the top of the report:

KPIDescriptionTotal ComplaintsOverall count of complaints receivedTimely Response %Percentage of complaints responded to on timeIn Progress ComplaintsComplaints currently under reviewConsumer Disputed RateRate at which consumers disputed the company's resolutionResolved at No CostProportion of complaints resolved without monetary compensation


📈 Visualizations

VisualTypeDescriptionComplaints by IssueHorizontal Bar ChartRanks complaint volume by issue categoryComplaints by StateMapGeographic bubble map showing complaint density by U.S. stateMonthly TrendArea ChartTracks complaint volume over time by monthComplaints by ProductTreemapHierarchical breakdown of complaints by financial product% Consumer DisputedDonut ChartSplits complaints by whether the consumer disputed the outcome


🎛️ Filters / Slicers

SlicerFieldDate ReceivedFilter the full report by complaint receipt date rangeMedia / ChannelFilter by submission channel (e.g., Web, Phone, Referral)

All slicers are cross-report filters — selecting a value updates every visual on the page simultaneously.


🗂️ Data Model

The report is built on a single table:

Financial Consumer Complaints

Key fields used across visuals:


Date Received — date the complaint was filed
Product — financial product category (e.g., Mortgage, Credit card)
Issue — nature of the complaint
State — U.S. state where the complaint originated
Submitted via — submission channel
Consumer disputed? — whether the consumer disputed the resolution


Key measures:


Total Complaints
Timely Response %
In Progress Complaints
Consumer Disputed Rate
Resolved at No Cost


Open Power BI Desktop
Go to File → Open report and select Financial_Complaints_Overview.pbix
If prompted to refresh data, connect to your data source or use the embedded model
Interact with the slicers and visuals to explore the data



📁 Repository Structure

├── Financial_Complaints_Overview.pbix   # Power BI report file
├── README.md                            # Project documentation
└── data/                                # (Optional) Raw data files
    └── financial_complaints.csv


🤝 Contributing

Contributions, suggestions, and issue reports are welcome. Feel free to open a pull request or raise an issue.


📄 License

This project is licensed under the MIT License.


🙋 Author

GitHub: @karthikvishak
