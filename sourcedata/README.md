Source data
===========
This folder contains curriculum standards data in machine readable formats like
spreadsheets and CSV files that are used as part of the digitization process.
See [docs](https://rocdata.readthedocs.io/en/latest/importers/standards_spreadsheet.html) for more info.

Data sources
------------
 - The original XML data export from CCSS website:
   http://www.corestandards.org/wp-content/uploads/ccssi.zip
 - CCSSM [json data](https://github.com/learningequality/design2align-backend/blob/master/imports/curriculumdocuments/CCSSM.json)
   from Hackathon, which in turn was obtained from https://commonstandardsproject.com/
   via the [standards-importer](https://github.com/commonstandardsproject/standards-importer) scripts.
 - RDF data from ASN including the [CCSS](http://asn.jesandco.org/resources/ASNJurisdiction/CCSS)
   and [many other states and countries](http://asn.jesandco.org/resources/ASNJurisdiction).
   See [this file](https://github.com/commonstandardsproject/api/blob/master/importer/matchers/source_to_subject_mapping_grouped.rb) for a comprehensive list of ASN documents.
 - CASE-format standards data from the CASE Network, including
   [CCSSM](https://casenetwork.imsglobal.org/cftree/doc/1912)
   [ELA-Literacy](https://casenetwork.imsglobal.org/cftree/doc/1911), and 
   standards from [many more states](https://casenetwork.imsglobal.org/cfdoc/).


Other resources
---------------
 - CCSS en Español: https://commoncore-espanol.sdcoe.net/ (available only as PDF)
