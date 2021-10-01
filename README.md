# standards-usa
Controlled vocabularies and curriculum standards data for USA (only CCSS so far).

Jurisdiction info
-----------------
Curriculum standards in the USA are complicated. Each state has their own standards
and there are also national standards adopted by many (but not all) states.

The Common Core is a set academic standards in mathematics and English language arts/literacy (ELA),
outlining what students should know and be able to do at the end of each grade.
The standards were created to ensure that all students graduate from high school
with the skills and knowledge necessary to succeed in college, career, and life,
regardless of where they live. Forty-one states, the District of Columbia,
four territories, and the Department of Defense Education Activity (DoDEA)
have voluntarily adopted the Common Core standards.

This code repo contains only the Common Core State Standards published by the 
Council of Chief State School Officers (CCSSO) and the National Governors Association Center for Best Practices (NGA Center). For other USA standards see https://commonstandardsproject.com/.



Contents
--------
- [`sourcedocuments/`](./sourcedocuments): source documents (PDFs and scans)
- [`sourcedata/`](./sourcedata): machine-readable source documents (spreadsheets)
- [`terms/`](./terms): controlled vocabularies used in the digitized standards:
  - [`CCSSCurriculumElements.yml`](./terms/CCSSCurriculumElements.yml): terms describing
    the different "types" of elements within the Common Core standards
  - [`Subjects.yml`](./terms/Subjects.yml): terms for the academic subjects within the jurisdiction
  - [`GradeLevels.yml`](./terms/GradeLevels.yml): localized grade levels
- [`standards/`](./standards): curriculum standards ROCdata



Digitization notes
------------------
- CCSS data is available as XML sourcedata
- CCSS data is also available as ASN (RDF) and in CASE formats




License
-------
All documents and are under copyright © 2021 Common Core State Standards Initiative.
The digital representations of terms and standards data in this repository are
for illustrative purposes part of the [ROC data project](https://rocdata.global/)
and should not be considered endorsed or approved by the CCSS Initiative in any way.

