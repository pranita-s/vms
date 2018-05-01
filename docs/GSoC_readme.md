 Synchronize R API with the Python Data Retriever API and improve usability of R package
==============

The Data Retriever handles downloading, pre-processing and storing of datasets in the user environment. It eases life of analysts and gives a head start by providing clean and normalized (analysis - ready) data with the goal that the users can reserve their time for studying/analyzing. The Data Retriever is written in Python and can be accessed by three major data science languages - Python(Retriever), R(Rdataretriever) and Julia(Retriever.jl).

Technical Details
--------

**Individual `install` functions for different database support:**

* Making the `install` function more versatile to provide the end user the liberty of accessing the datasets in their preferred database.

**Detecting the Retriever Python API:**

* Improve the cross platform detection of Python installation.

**Supplement R API for Retriever with visualization widgets:**

* Add visualization widgets to derive insights.

Schedule of deliverables
------------

* **April 24th to May 13th - Community Bonding Period (3 weeks)**
  * Set up Blog if not yet and community bonding.
  
* **May 14th to May 24th - Commencement of work for the install suite (1.5 weeks)**
  * Initiation of the work on the individual install functions for all the supported DBMS and altering behavior of current install function to ensure backward compatibility.

* **May 25th to May 29th - Initiation of Retriever detection (4 days)**
  * A robust function for Retriever detection will be written on a Windows system.
  
* **June 1st to June 10th - Functional testing of independent operations (1.5 weeks)**
  * Test the functional behavior of the independent tasks - `install` and `detect Python`.

* **June 11th to June 15th - Phase I evaluation submission (4 days)**
  * Perform integration testing of the entire package and remove redundant code.

* **June 16th to June 26th - Design decisions taken (1.5 weeks)**
  * RDataRetriever supports varieties of datasets, hence the final list of visualization widgets will contain at least a desired number of visualizations for each data set.

* **June 27th to July 8th - Inception of coding for visualization widgets (>1 week)**
  * The work on most common widgets which will be frequently required among all the datasets will begin.

* **July 9th to July 13th - Phase II evaluations submission (4 days)**
  * Functional testing of the completed widgets will be done and documentation for the usage of widgets will be added.

* **July 15th to July 30th - Adding more widgets and tests (< 1 week)**
  * The ultimate aim will be to give the visualization utility a wholesome capability to envision a broad spectrum of datasets.

* **August 1st to August 6th - Testing and documentation (1 week)**
  * Integration testing of the successfully completed widgets will be carried out and documentation update.

* **August 7th to August 14th - Final submission (< 1 week)**
  * Resolving issues that come up after the finalizing code and submission.
