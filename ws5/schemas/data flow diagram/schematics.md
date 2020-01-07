# Schematics Adjudication and Update
Glenn Abastillas | October 22, 2019 | Workstream 5 (?)


#### Log
   1. [2019-11-13 MVP with Connecticut](#20191113)
   1. [2019-11-12 Centralized Document per Registry](#20191112)
   1. [2019-11-05 Post-NY Call](#20191105)
   1. [2019-10-22 Kick-Off Call](#20191022)
   1. [Abbreviation Dictionary](#abbreviation_dictionary)

<hr/>

#### Status Update by Registry to Complete

State | Update
:-: | :--
CT | [2019-11-13](#20191113): Drafting MVP with old diagram format and generating simplified one for feedback.
HI |
IA |
MI |
NM |
NY |
UT |

<hr/>

#### 2019-11-13 MVP with Connecticut <a id="20191113"></a>

**Goal**: Create an MVP update with CT data.

`Note below deals with company called TransMed. TransMed mentioned in diagrams may refer to AIM TransMed`
**TransMed/Inteliquet Rebranding**: Found that [TransMed has rebranded to Inteliquet as of April 2019](https://www.businesswire.com/news/home/20190415005119/en/TransMed-Systems-Rebrands-Inteliquet). Also debuted [at ASCO 2019](https://events.jspargo.com/ASCO19/Public/eBooth.aspx?IndexInList=262&FromPage=Exhibitors.aspx&ParentBoothID=&ListByBooth=true&BoothID=593857).

**Notes**: For the transport section, would it be possible to also distill the `% reportability` and `%/# of pathology reports` routed through a particular Transport object?

**Registries**: List of registries examined and notes

State | Notes
:-: | :--
CT | <ul><li>Focus a lot of how AIM TransMed Server received inputs from other CAS</li><li>Other software include AIM TransMed, individual folders, PHINMS and CAS software</li></ul>
HI | <ul><li>Most labs use AIM TransMed Server</li><li>Some labs still us paper (about 100)</li></ul>
IO | .
GA | <ul><li>Had their `reportibility` rates by `Transport` type.</li></ul>

<hr/>

#### 2019-11-12 Centralized Document per Registry <a id="20191112"></a>

The idea is to have an Excel spreadsheet that contains all the required information for each registry.

Centralizing contributing information to a registry's schema update will facilitate updating the config file and providing context for why elements exist or changes are made.

**SVG Editor**: Use [this browser SVG editor](https://svg-edit.github.io/svgedit/releases/svg-edit-2.8.1/svg-editor.html) to assist in defining custom shape attributes for automation. Full Link: https://svg-edit.github.io/svgedit/releases/svg-edit-2.8.1/svg-editor.html

<hr/>

#### 2019-11-06 Post-NY Call <a id="20191105"></a>

Inventory of work.

_Completed Registries_

State | No. of Registries | Name(s) |
:-: | :-: | :-- |
CA | 3 | Greater California, Greater Bay Area of California, Los Angeles |
GA | 1 | Georgia |
KY | 1 | Kentucky |
LA | 1 | Louisiana |
WA | 1 | Seattle |

_Registries to Process_

State | No. of Registries | Names
:-: | :-: | :--
CT | 1 |
HI | 1 |
IA | 1 |
MI | 1 |
NM | 1 |
NY | 1 |
UT | 1 |

###### Script (Diagram and Artist)

Script successfully able to read configuration file (i.e., Excel), draw SVG shapes and save to file.

Currently, all shapes are `rect`s and there are no labels or colors except for regions.

*Next Step*:
  1. Properly configure master template configuration for customization for different states.
  2. Create custom SVG shape configurations for custom shapes to be used in diagram

<hr/>

#### 2019-10-22 Kick-Off Call <a id="20191022"></a>

**Participants**: Marina, Melissa, Glenn

**Discussion**: Participants talked about the goal of this task, the current resources and state of the schematic diagrams, and future changes to be recorded during registry-specific phone calls.

**Action Items**: Melissa to transfer current files from L drive to OneDrive to allow all parties to access modifiable files and folders. Glenn to ingest current state documents and extract knowledge from latest registry responses.

<span style='color: #ffffff;'>.</span>||
--: | :--|
**Task** | Update registry-level schematic diagrams
**Deliverable**| Schematic diagrams updated to latest data according to Survey Monkey results and schematic other diagrams dated 8/29
**Resources** | PDFs, Vizio files, and Survey Monkey results
**Timeline**| 2 - 3 months to complete
**Meetings** | Scheduled meetings at 2:30 pm on Tuesdays and scheduled meetings with registries

#### Abbreviation Dictionary <a id="abbreviation_dictionary"></a>

Abbreviation | Expansion | Variations
--- | --- | ---
PHINMS | Publich Health Information Network - Messaging System |
TransMed | AIM TransMed Server | AIM
CAS | Cancer Analysis Software |
RnR | Route not read | R and R
