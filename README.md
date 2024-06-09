# Dashboard to Automate HR Reporting

## Table of Contents
1. [Introduction](#introduction)
2. [System Requirements](#system-requirements)
3. [System Design](#system-design)
4. [System Implementation](#system-implementation)
5. [Results](#results)
6. [Conclusion and Future Enhancements](#conclusion-and-future-enhancements)
7. [Documentation and Journal Publication](#documentation-and-journal-publication)

## Introduction
The "Dashboard to Automate HR Reporting" project aims to simplify the process of analyzing large amounts of HR data related to employee attendance and work modes (e.g., work from home, part-time, full-time). By creating a dashboard, organizations can easily track employee attendance, generate reports, and make data-driven decisions to improve workforce management and productivity. The dashboard is designed to automatically refresh data and send alert notifications via email when specific thresholds are met.

## System Requirements

### Hardware Requirements
- **Processor**: x64 Processor (AMD Opteron, AMD Athlon 64, Intel Xeon with Intel EM64T support, Intel Pentium IV with EM64T)
- **RAM**: 4GB or higher
- **Hard Disk**: Minimum of 1GB, additional space required for the database
- **Operating System**: Windows 8.1 or higher

### Software Requirements
- **Languages Used**: DAX Query Language, JSON
- **Visualization Tool**: Power BI
- **Other Software Tools**: Gateway, Power Automate
- **Data Storage Tool**: Microsoft Excel

## System Design
The system architecture consists of four major steps:
1. **Data Sourcing**: Collecting data from various HR databases.
2. **Data Transformation**: Cleaning and preprocessing the data to remove missing or useless values and applying certain rules for transformation.
3. **Report Creation**: Generating reports based on the cleaned data, using visualizations such as graphs and pie charts.
4. **Dashboard Creation**: Pinning individual report elements to create interactive dashboards. These dashboards are refreshed automatically and can send alerts when specific conditions are met.

## System Implementation

### List of Modules
1. **Understanding the Requirements**: Defining the problem and the scope of the project.
2. **Gathering and Transforming Data**: 
   - Data Cleaning and Preparation
   - Exploratory Data Analysis
   - Creating Metrics using DAX
3. **Visualization or Dashboarding**: Creating visualizations and dashboards in Power BI.
4. **Publishing the Report to Web**: Making the reports accessible online.
5. **Installing Gateway Software**: Setting up the Power BI Gateway for data refreshes.
6. **Email Notification**: Setting up automated alerts for specified conditions.

## Results
The project successfully created a dashboard that provides a comprehensive view of key HR metrics. The dashboard can track employee attendance, visualize trends, and generate reports efficiently. The automation features ensure that data is always up-to-date and alerts are sent out as needed.

## Conclusion and Future Enhancements

### Conclusion
The HR dashboard project has achieved its goal of automating the analysis and reporting of HR data. By leveraging tools like Power BI, Power Automate, and DAX, the project has created a robust solution that enhances the ability of HR managers to monitor and improve employee productivity.

### Future Enhancements
- **Integration with More Data Sources**: Extending the dashboard to include data from additional HR systems.
- **Advanced Analytics**: Incorporating machine learning models to predict trends and provide deeper insights.
- **User Customization**: Allowing end-users to customize the dashboard according to their specific needs.
- **Mobile Access**: Developing a mobile-friendly version of the dashboard for on-the-go access.

## Appendix

## Documentation and Journal Publication
This project has been documented thoroughly to aid future developers and researchers. The detailed project report has been published in the International Journal of Novel Research and Development (IJNRD), under the title "Dashboard to Automate HR Reporting". The publication outlines the project's objectives, methodologies, results, and potential for future work.
[Download the PDF here](/images/dashborad.pdf)

### Reference
- **IJNRD Journal Publication**: Harini K N, Harini S, Janani T, "Dashboard to Automate HR Reporting", IJNRD, May 2023. [Link to the publication]

---

This README file provides an overview of the project and guides users and developers through the system requirements, design, implementation, and results. For more detailed information, please refer to the full project documentation and the IJNRD journal publication.
