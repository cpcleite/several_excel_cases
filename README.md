# Several Excel Files

This repository contais several Excel files created to facilitate the creation of executive presentations and consistency check routines.

## Files' Descriptions

#### 1. Dados do Essbase - SUDAM.xlsx
Contains VBA code used to extract data from company's BI Cube using Essbase interface. It automates data retrieval for several spreadsheets.

#### 2. BRM GSR Latam.xlsm
Contais several pre-formated spreadsheets that are updated using Essbase. Data is retrieved from company's BI Cube. This file is later used for creation of Executive Review's PowerPoint file.

#### 3. Cria Apresentação.xlsm
Contains VBA code to copy information from BRM GSR Latam.xlsm file and create a standard PowerPoint Presentation for Executive Review Meetings.

#### 4. Publicação Relatórios.xlsm
Contains VBA code to retrieve data from company's BI Cube anda create segmented Sales Dasboards (see Management Dashboard 2019 - SUDAM.xlsx file). Reports generated by this file are used by Segment Managers for monitoring sales performance.

#### 5. Folhas.xlsm
Contains VBA code to consolidate payroll information from reports (txt files) from three distinct systems. This code generates a database used to check several consolidated figures with executive reports. For exemple: total payroll expenses by company, headcount turnover, provisions. Consolidated data was used in Business Review Presentation, and budget planning and control.

#### 6. Resumo FP.xlsx
Contains Excel Dynamic Tables, conneted to the Access Database, created by Folhas.xlsm code. These tables where used to check payroll data with corporate consolidation SAP files.

#### 7. Consolidação da Contabilidade.xlsm
Contains VBA Code and spreadsheet used to check consistency between two distinct local accounting systems and the flat file used to upload data to company's consolidation system.
