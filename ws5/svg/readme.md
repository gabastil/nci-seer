# Data Diagram Wireframes
February 5, 2020 | Glenn Abastillas

This folder contains the data diagram wireframes for registries. These wireframes are in .svg format and can be opened via [draw.io](draw.io) or Visio software.

## Contents <a id="contents"></a>

Registries with data diagrams completed are listed below with the month and year of their latest versions. A link to a draft of the new data diagram template for each state accessible via the link in the parenthesis.

State |  8/2018 | 1/2020 | 02/2020
--- | --- | --- | ---
[Connecticut](#Connecticut) ([New](#Connecticut_New)) | | | &check;
[Detroit](#Detroit) ([New](#Detroit_New)) | | &check; |
[Georgia](#Georgia) ([New](#Georgia_New)) | &check; | |
[Greater_Bay_Area_of_California](#Greater_Bay_Area_of_California) ([New](#Greater_Bay_Area_of_California_New)) | | | &check;
[Greater_California](#Greater_California) ([New](#Greater_California_New)) | | &check; |
[Hawaii](#Hawaii) ([New](#Hawaii_New)) | | | &check;
[Iowa](#Iowa) ([New](#Iowa_New)) | | | &check;
[Kentucky](#Kentucky) ([New](#Kentucky_New)) | | | &check;
[Los_Angeles](#Los_Angeles) ([New](#Los_Angeles_New)) | | | &check;
[Louisiana](#Louisiana) ([New](#Louisiana_New)) | | | &check;
[New_Mexico](#New_Mexico) ([New](#New_Mexico_New)) | | | &check;
[New_York](#New_York) ([New](#New_York_New)) | | | &check;
[Seattle](#Seattle) ([New](#Seattle_New)) | &check; | |
[Utah](#Utah) ([New](#Utah_New)) | | &check; |

---

#### Data References and the Draft Schemas <a id="other_useful_data"></a>

  1. [eMaRC Plus Coverage](#emarc)
  2. [Master schema draft](#master_schema_draft)
---

### eMaRC Plus Coverage <a id="emarc"></a>

Electronic Mapping, Reporting, and Coding (eMaRC) Plus coverage map screenshot taken in Feb. 10 2020. Status of coverage reported as last updated December 2016. [More information about eMaRC Plus can be found on the CDC's website.](https://www.cdc.gov/cancer/npcr/tools/registryplus/mp.htm).
([Back to Top](#contents))

<img src="20200210_emarc_states.PNG" width="75%" />

### Master Schema Draft <a id="master_schema_draft"></a>

This draft is a redesign and simplification of the original source data diagrams presented in subsequent sections. The aim of this master schema draft (MSD) is to accurately convey as much information regarding the flow of data from data sources to SEER\*DMS in the simplest visual manner as possible.
([Back to Top](#contents))

<img src="master_schema.svg?sanitize=True" width="75%" />

### Connecticut <a id="Connecticut"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Connecticut.svg?sanitize=True" width="75%" />

##### Meeting Notes

Date | Note
--- | ---
2/13/2020 | Registry did not agree with all the metrics presented in the PPT
2/13/2020 | Marina asked Jennifer Stevens to review her pull and the instructions to get those data just to confirm.
2/13/2020 | JS histological confirmation comes from the CTC not the path report.
2/13/2020 | JS just looking at the specimen date, it includes reports that must have been linked to a CTC
2/13/2020 | IMS needs to double check with regard to how they are calculating statistics based on PDFs, ePath, and paper reports coming to the registry for coverage.
2/13/2020 | Will need to rerun the metrics and will use 2018 and 2019 data instead
2/13/2020 | From AIM, data goes to registry, get uploaded manually through WSAPI
2/13/2020 | Data through PHINMS, data goes to registry, processed in transmed and then uploaded to IMS

### Detroit <a id="Detroit"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Detroit.svg?sanitize=True" width="75%" />

### Georgia <a id="Georgia"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Georgia.svg?sanitize=True" width="75%" />

### Greater_Bay_Area_of_California <a id="Greater_Bay_Area_of_California"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Greater_Bay_Area_of_California.svg?sanitize=True" width="75%" />

### Greater_California <a id="Greater_California"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Greater_California.svg?sanitize=True" width="75%" />

### Hawaii <a id="Hawaii"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Hawaii.svg?sanitize=True" width="75%" />

Notes from 2/7/2020 -- Responses are from HI

    1. AIM CNS Imagining is not implemented. Not part of their normal processing.
    1. AIM EPath Network probably not being used, HI was not familiary with its implementation.
    1. EPath Monitor is realistically just there for a QC of sorts.
    1. After AIM processing, the files go to the in-house DB processing system.
    1. For paper reports, it would be an external source called FAX. It is scanned into an internal document management system and then data entered into SEER\*DMS.
    1. Currently not utilizing DMS's imaging system.
    1. All images are external to SEER*DMS

### Iowa <a id="Iowa"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Iowa.svg?sanitize=True" width="75%" />

### Kentucky <a id="Kentucky"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Kentucky.svg?sanitize=True" width="75%" />

### Los_Angeles <a id="Los_Angeles"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Los_Angeles.svg?sanitize=True" width="75%" />

### Louisiana <a id="Louisiana"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Louisiana.svg?sanitize=True" width="75%" />

##### Meeting Notes

Date | Note
--- | ---
2/20/2020 | Add PHINMS, Fax, and Mail routes
2/20/2020 | Change sFTP route to go through the registry's local file system first
2/20/2020 | New route that goes through APHL (sFTP) to the state's DoH, which sFTPs the data to the registry



### New_Mexico <a id="New_Mexico"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="New_Mexico.svg?sanitize=True" width="75%" />

Notes from 2/12/2020
	1. NM to change processes to better link scanned reports to CTCs as opposed to patient profile.

### New_York <a id="New_York"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="New_York.svg?sanitize=True" width="75%" />

### Seattle <a id="Seattle"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Seattle.svg?sanitize=True" width="75%" />

### Utah <a id="Utah"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Utah.svg?sanitize=True" width="75%" />


## New Data Diagrams <a id="new_data_diagrams"></a>


### Connecticut (New) <a id="Connecticut_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Connecticut_New.svg?sanitize=True" width="75%" />

### Detroit (New) <a id="Detroit_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Detroit_New.svg?sanitize=True" width="75%" />

### Georgia (New) <a id="Georgia_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Georgia_New.svg?sanitize=True" width="75%" />

### Greater_Bay_Area_of_California (New) <a id="Greater_Bay_Area_of_California_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Greater_Bay_Area_of_California_New.svg?sanitize=True" width="75%" />

### Greater_California (New) <a id="Greater_California_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Greater_California_New.svg?sanitize=True" width="75%" />

### Hawaii (New) <a id="Hawaii_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Hawaii_New.svg?sanitize=True" width="75%" />

### Iowa (New) <a id="Iowa_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Iowa_New.svg?sanitize=True" width="75%" />

### Kentucky (New) <a id="Kentucky_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Kentucky_New.svg?sanitize=True" width="75%" />

### Los_Angeles (New) <a id="Los_Angeles_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Los_Angeles_New.svg?sanitize=True" width="75%" />

### Louisiana (New) <a id="Louisiana_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Louisiana_New.svg?sanitize=True" width="75%" />

### New_Mexico (New) <a id="New_Mexico_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="New_Mexico_New.svg?sanitize=True" width="75%" />

Notes from 2/12/2020
	1. NM to change processes to better link scanned reports to CTCs as opposed to patient profile.

### New_York (New) <a id="New_York_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="New_York_New.svg?sanitize=True" width="75%" />

### Seattle (New) <a id="Seattle_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Seattle_New.svg?sanitize=True" width="75%" />

### Utah (New) <a id="Utah_New"></a>
Registry data flow diagram show how data flows from data sources to SEER\*DMS. ([Back to Top](#contents))
<img src="Utah_New.svg?sanitize=True" width="75%" />