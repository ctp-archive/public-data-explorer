# The COVID Tracking Project Data Explorer

## Datasets

Data in the explorer comes from a variety of platforms and technologies. Where possible, we not only preserved the original, published version of datasets, but also used whatever revision history was available.

### Testing & outcomes

- **Field definitions** — Stored on the content management system [Contentful](https://contentful.com/). We downloaded the entire revision history of each field definition.
- **Testing & outcomes** — Data in a state's main testing and outcomes data table is published data pulled from the last date of our API.
- **State metadata** — State metadata like notes were stored in a Git repository. We walked through the revision history and created snapshots of changes of these metadata over time.
- **Outreach** — When the Outreach and Reporting team talked to a state representative, these questions and answers were stored in an Airtable database. Some redacted outreach data from that database is included in the data explorer.
- **Data quality log** — Data on major issues affecting a state's data quality were stored in an Airtable database.
- **Batches** — Batches were bulk changes made to several state or date's data at once. These updates were downloaded from an internal publishing API.
- **Edits & history** — Data published through the CTP API was stored in a Git repository. Using the revision history, we walked through every commit to this repository and compared different versions of a state's data. If there were any changes over time, that is captured in the **History** page of a date's data.
- **Screenshots** — Every state and date has multiple screenshots stored in the COVID Tracking Project archive. The data explorer has a list of these screenshots to ease requesting them from the archive.
- **Slack threads** — The CTP Data Entry Team used structured threads in Slack to talk about specific problems or potential issues with a state's data. If these threads were tagged as particularly interesting, they were included in the data explorer. Names of individuals have been redacted.
