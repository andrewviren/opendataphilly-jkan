---
category:
- Budget / Finance
- Economy
extras:
  department: Department of Finance
license: Other (City of Philadelphia)
maintainer: ''
maintainer_email: ''
notes: "__This data does not necessarily represent current salaries of employees and\
  \ is intended for informational purposes only. Formal requests to document salary\
  \ details or other personnel information should be made through the [City's Human\
  \ Resources department](https://www.phila.gov/departments/office-of-human-resources/).__\r\
  \n\r\nEarnings for all City employees, including elected officials and Court staff.\
  \ Please note that since employee counts fluctuate throughout the year, the sum\
  \ of the BASE_SALARY field does not reflect the total budgeted amount. Also, when\
  \ the BASE_SALARY column is blank, it represents part-time, temporary, or seasonal\
  \ employees paid by the hour. Please see [metadata](https://metadata.phila.gov/#home/datasetdetails/5543865520583086178c4ebd/representationdetails/604284dc49a209001d746460/?view_287_per_page=25&view_287_page=1)\
  \ for detailed explanations of each field."
organization: City of Philadelphia
resources:
- description: A visualization of the latest  available quarter's data on City of
    Philadelphia employee earnings.
  format: HTML
  name: Employee Earnings (Visualization)
  url: https://data.phila.gov/visualizations/employee-earnings
- description: 'Data from Calendar Year (CY) 2019 Q2 to the latest quarter. '
  format: CSV
  name: Employee Earnings 2019-latest quarter (CSV)
  url: https://phl.carto.com/api/v2/sql?filename=employee_earnings&format=csv&q=SELECT%20*%20FROM%20employee_earnings
- description: "Data from Calendar Year (CY) 2019 Q2 to the latest quarter. \r\n"
  format: API
  name: Employee Earnings 2019-latest quarter (API)
  url: https://cityofphiladelphia.github.io/carto-api-explorer/#employee_earnings
- description: ''
  format: HTML
  name: Employee Earnings 2019-latest quarter (Metadata)
  url: https://metadata.phila.gov/#home/datasetdetails/5543865520583086178c4ebd/representationdetails/604284dc49a209001d746460/?view_287_per_page=25&view_287_page=1
- description: "Data from Calendar Year (CY) 2019 Q2 onwards is extracted from the\
    \ newer OnePhilly payroll system and has a different data schema than the legacy\
    \ payroll system. Therefore, one cannot and should not compare this previous earnings\
    \ data (from 2016 to 2019 Q1) with the new data. \r\n"
  format: CSV
  name: 'ARCHIVED: Employee Salaries 2016 - CY2019 Q1 (CSV)'
  url: https://phl.carto.com/api/v2/sql?q=SELECT+*+FROM+employee_salaries_archive&filename=employee_salaries_archive&format=csv&skipfields=cartodb_id,the_geom,the_geom_webmercator
- description: 'Data from Calendar Year (CY) 2019 Q2 onwards is extracted from the
    newer OnePhilly payroll system and has a different data schema than the legacy
    payroll system. Therefore, one cannot and should not compare this previous earnings
    data (from 2016 to 2019 Q1) with the new data. '
  format: API Documentation
  name: 'ARCHIVED: Employee Salaries 2016 - CY2019 Q1  (API)'
  url: https://cityofphiladelphia.github.io/carto-api-explorer/#employee_salaries_archive
- description: 'Data from Calendar Year (CY) 2019 Q2 onwards is extracted from the
    newer OnePhilly payroll system and has a different data schema than the legacy
    payroll system. Therefore, one cannot and should not compare this previous earnings
    data (from 2016 to 2019 Q1) with the new data. '
  format: HTML
  name: 'ARCHIVED:  Employee Salaries 2016 - CY2019 Q1 (Metadata)'
  url: https://metadata.phila.gov/#home/datasetdetails/5543865520583086178c4ebd/representationdetails/5702f25233ec3695104ca926/
schema: default
tags:
- carto
- earnings
- employee salaries
- overtime
- salaries
- salary
- wages
title: City Employee Earnings
---