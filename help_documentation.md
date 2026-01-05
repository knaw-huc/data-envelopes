# Help documentation for fields
This page contains help documentation, including examples, for the fields in a data-envelope as implemented in the Huygens Data-Envelope editor. If you want general help in creating data-envelopes, then read the [guidelines](guidelines.md)

# Basic workflow
* Follow the link you have been given to the editor and enter the login information you have been given.

* The editor opens showing a list of all data-envelopes in a table. 

* You create a data-envelope by clicking the plus icon in the top of the table. 

* Fill in as much of the information in the data-envelope as you can, referring to the help information below. You may know the information yourself, or you may need to look it up in existing dataset documentation, such as the Resource page. For some fields, you may need to ask colleagues for assistance. They can fill in the data-envelope themselves if they have a log-in, or they can answer your questions and you can fill in the information yourself. Note: it is not advisable to work on the same data-envelope simultaneously, agree who will work on the data-envelope in a particular period. 

 **Be sure to regularly save your work by pressing the Save button**

* Some fields in a data-envelope are compulsory. These are marked with a star in the editor. If these fields are not filled in, then the data-envelope will fail validation. Validation occurs when you press the Submit button. You can save an invalid envelope, but you can not successfully submit it. 

* For all other fields, the rule is to fill in as much as you reasonably can. Priority should be given to the information that is most important for your particular dataset. You may know the information yourself, you may find it in dataset or project documentation, or you may ask colleagues (if they have access to the editor then they can fill in the information directly). If data-envelopes already exist for similar datasets, then it can be helpful to look at these for guidance as to how to fill in your data-envelope - how to name organisations, what to include in text descriptions, which genre and topic keywords to use etc. In particular for data-envelopes from the same institution or team it makes them more readable if they are filled in consistently.

* When you have completed the data-envelope, ask a colleague to review it. If they have access to the editor, then they can review it there. Otherwise, you can download a copy from the table (in PDF, HTML or CDMI format) and send this to them for review. 

* Once the data-envelope is completed, click on Submit. The data-envelope will be validated. If any compulsory fields are not filled in, then error messages will appear. Otherwise, the data-envelope status will be set to 'publish'.

# Administrative information
At the top of the data-envelope there is some basic administrative information

* Institute - select your institute
* ID - this will be filled in automatically the first time you save the data-envelope
* Status - this is filled in automatically. It will be initialised to 'under construction' when you first save the envelope and updated when you submit it

# Level 1 Basic Information
This level describes the data-envelope itself and the dataset contact person.

## 1.1. Title of Data-Envelope<a id='level-1-title'></a>
A title for the data-envelope, NOT the dataset. Follow the format: Dataset Name Version-X Data-Envelope Version-Y. 

    Baptism Registers Amsterdam Version-1 Data-Envelope Version-1

The first version number refers to the version of the dataset being documented, the second version number refers to the version of the documentation itself. Typically the version number is an integer, and '1' is used for the first version of the dataset or the envelope. However it can be more appropriate to use other numbering systems. For example, if a dataset already existed for a long time prior to the data-envelope being created but didn't have a version number, then it may be more informative to use the current year. You should agree a numbering system with your team.

You can add the title in different languages if you think this is helpful to dataset users.

## 1.2 Contact Details<a id='level-1-contact'></a>
This should contain information about the contact person for the dataset.

* Name - The full name of the contact person
* ORCID ID - the [ORCID](http://orcid.org) identifier for the contact person
* Role in project - You can define one or more roles that the contact person played in the creation of the dataset. Leave empty if no roles are applicable.
* Email - an email address for the contact person. The recommendation is to use a general institutional address to avoid problems when people move to new institutions. E.g. data@myinstitution.org

Sometimes there is no specific contact person. In that case, instead of a name you can add a description, e.g. 'Helpdesk' or 'Data management department'

## 1.3 Data Envelope Dates<a id='level-1-dates'></a>
This contains the dates for the data-envelope

* Data-Envelope Creation Date - the date on which the data-envelope was created
* Data-Envelope Completion Date - the date on which the data-envelope was completed
* Data-Envelope Publication Date - the date on which the data-envelope was published

## 1.4 Author of Data-Envelope<a id='level-1-author'></a>
This should contain information about the primary author of the data-envelope itself.

* Name - the full name of the primary author
* ORCID ID - the [ORCID](http://orcid.org) identifier for the primary author
* Email - an email address for the primary author. The recommendation is to use a general institutional address to avoid problems when people move to new institutions. E.g. data@myinstitution.org

## 1.5 Feedback and elaboration<a id='level-1-feedback'></a>
Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful. For example, you could indicate to what extent the necessary information for the data-envelope was easily available: was this a current project with experts available to answer all the questions, or is it data from fifty years ago for which the description has been pieced together from old documentation sources? You can also indicate what information sources you used to fill in the data-envelope, if you wish. 

# Level 2 Basic Metadata
Level 2 describes the dataset at a conceptual level. It is the 'trailer' that allows users to assess if the dataset is relevant to them, and as such it should be concise (preferably max 200 words). This level describes the basic dataset metadata. This includes: what the dataset contains, what the temporal and geographical coverage are, how it can be accessed etc. This section conforms to the Data Catalog Vocabulary (DCAT) standard, ensuring compatibility with machine-readable formats.

## 2.1 Snapshot<a id='level-2-snapshot'></a>
This contains information about what is in the dataset.

There is some discussion as to what should be included in the temporal and geographical coverage. For example, for a collection of letters the geographical coverage could refer to the locations the letters were sent to/from, or the locations discussed in the letters. Try to think about what information is most useful for users of the dataset. 

* Dataset title - the title of the dataset
* Version - the version number of the dataset. Typically this is '1' for the first version of the dataset. An alternative option, particularly for datasets that have been in existence for some time already, could be to use the year. You can agree a numbering system with your team. This should be the same as the version number stated in the data-envelope title. 
* Description - Provide a free text account of the dataset or resource (limit 200 words). Include information about the content and topic of the data and what makes the dataset valuable. You may also briefly refer to how the data is available (download, portal etc.) but details about this should be entered at Level 3.
* Genre - One or more genres from a vocabulary that apply to the dataset. A genre categorises the dataset or the items in it. E.g. Books, Legislation, Videorecording
* Other Genre - Genres that apply to the dataset that are not included in the vocabulary
* Topic Classification - One or more topics from a vocabulary that apply to the dataset. A topic describes what the dataset is about. E.g. Archaelogy, History, Public Administration.
* Other Topic - Topics that apply to the dataset that are not included in the vocabulary
* Languages - One or more languages from a vocabulary that apply to the dataset. This refers to the natural language used for textual metadata (i.e., titles, descriptions, etc.) of a cataloged resource (i.e., dataset or service), in audio/video or the textual values of a dataset distribution.
* Other Language - Languages that apply to the dataset that are not included in the vocabulary, or for which you need to add a textual description (e.g. 'A small number of documents are in various other languages').
* Geographical coverage - This refers to the geographical area pertaining to the datasets. One or more geographical areas from a vocabulary that apply to the dataset (Note: currently no vocabulary is connected in the editor). 
* Other Geographical coverage - Geographical areas that apply to the dataset that are not included in the vocabulary

### Temporal coverage

This refers to the temporal coverage of the content of the dataset, NOT the dates on which the dataset was created (these should be entered in section 2.2). This could be the date range of the creation of the original items (e.g. for a collection of sixteenth century letters it could be the earliest and latest dates on which letters were sent) or it could be the period discussed in the dataset (e.g. interviews recorded discussing the Second World War in the Netherlands might cover the temporal range 1940-1944). Choose what is most relevant for users of the dataset to know. 

If the temporal coverage is too complicated to explain in terms of years, then you can describe it in the Additional Notes.

* Temporal coverage Start - the first year of the temporal scope
* Temporal coverage End - the last year of the temporal scope
* Year - in the case that the temporal scope cannot be captured in a range, this field allows you to specify the individual years that are relevant to the scope of the dataset. If the temporal scope is too complicated to describe in terms of years, then describe it in the Additional Notes.
* Additional Notes - Specify any additional information about the temporal scope of the dataset. This could include gaps in the coverage, or years that contain more data than others. 

## 2.2 Dates<a id='level-2-dates'></a>
These dates refer to the time span during which the dataset was created. For example, the start and end date of the project to collect and digitise the data. The date on which the dataset is published is also specified. Note: these dates could conincide with the temporal coverage, for example if the dataset contains tweets collected daily. But usually it is later; for example a dataset may contain interviews recorded this year that discuss the Second World War.

A dataset may have been worked on in several phases. If they are all part of the same project, then choose the earliest and latest dates to enter here, and if you wish you can explain in more detail in Section 2.7. If they are distinct projects - for example if your dataset is a digitised book of nineteenth century diaries that was published in the 1980s and digitised in 2023 - then choose the project that is most relevant to the dataset you are describing (in this case, the digitisation). 

* Date From - when work on the dataset started
* Date To - when work on the dataset was complete
* Date Published - when the dataset was published

## 2.3 Creators and Contributors<a id='level-2-contributor'></a>
In this section you can list the people and organisations who contributed to the creation of the dataset, for example by curating data, managing the project, providing funding etc. Try to use the same way of writing names across your team or institution. It is harder to find all datasets from a particular person or organisation if their name is written differently each time.

In the case of older datasets, the organisations involved may have changed their names. As a general rule, stick to the name the organisation used at the time of involvement. If you think it is helpful to the data-envelope reader, then you can add the current name in brackets. Where the organisation continues in the same role under its new name, you can use the new name and indicate that it was already involved under the old name(s). For example, the Institute for Dutch History (ING) merged with the Huygens Institute to become the Huygens Institute for History and Culture of the Netherlands. For a dataset originally published by the ING and now published by Huygens you could fill in 'Huygens Institute for History and Culture of the Netherlands and predecessors' for the publishing organisation. 

The names of organisations may be in a different language to the language you are using when filling in the data-envelope. In this case, consider including a translation of the organisation name to help the data-envelope reader understand what sort of organisation it is. 

### Publishing Organisation
This is the organisation responsible for publishing the data.

* Name - the name of the publishing organisation. Be consistent with how you fill in the name.
* ROR ID - the [ROR](http://ror.org) identifier for the organisation
* Type - the type of the publishing organisation. Choose 'Other' if none of the other types apply
* Other - if you chose 'Other' for the type, specify the type of the organisation here

### Creators
Creators are responsible for the creation of the dataset. There is no strict definition of the difference between a creator and a contributor, but generally a creator makes decisions about the dataset content, while a contributor assists in creating the dataset. You can include as many creators and contributors as you like.

* Name - full name of the creator
* ORCID ID -  the [ORCID](http://orcid.org) identifier for the creator
* Organisation - the name of the organisation the creator was affiliated to at the time at which the dataset was created. Be consistent with how you fill in the name.
* ROR ID - the [ROR](http://ror.org) identifier for the organisation
* Role - one or more roles that the creator played in the creation of the dataset. Leave empty if no roles are applicable.
* Email - an email address for the creator

### Contributors
Contributors aid in the creation of the dataset, for example by entering data, writing software to process the data, or providing advice from the community. There is no strict definition of the difference between a creator and a contributor. You can include as many creators and contributors as you like.

* Name - full name of the contributor
* Organisation  - the name of the organisation the contributor was affiliated to at the time at which they worked on the dataset
* Description contribution - a description of how the contributor contributed to the dataset

### Funding Source
Here you can fill in persons, organisations or other funding sources that funded the creation, collection, or curation of the dataset. 

* Name - Name of the person or organisation who gave the funding
* ROR ID - the [ROR](http://ror.org) identifier for the organisation
* Funding or grant summary - a short summary of person or organisation and grant that funded the creation, collection, or curation of the dataset. Include any reference numbers.
* Link - a link to any further information about the funding

## 2.4 Distribution<a id='level-2-distribution'></a>
This section specifies where you can get the dataset or further information about the dataset, information on available downloads and on how to cite the dataset

* Dataset Link - This is a link that identifies the dataset. For instance its DOI, Handle, or ARK
* Repository - One or more links to the dataset or to information about the dataset. If the dataset has its own dedicated website(s) or is hosted on sites such as github, zenodo, dataverse, marketplace, or its own portal, provide the url(s) here. Documentation and FAQ pages can also be linked.
* Download
  * Link - one or more download links for the dataset
  * File/folder type - the type that is downloaded. For example, .zip for an archive file.
  * File Size - the size of the downloaded content, in MB
* Citation - the text that should be used to cite the dataset

Examples of citation formats:

For a whole dataset:

    Dijkstra, G., Groskamp, N., Hoekstra, R., Koolen, M., Renkema, E., Sluijter, R., Smit, F., & Oddens, J. (2024). Entities recognised in the resolutions of the States General of the Dutch Republic (1576-1796) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.14577244 

For items within a dataset (in this example letters):

    A [name of correspondent] to B [name of correspondent], date [date of letter or  document], The Correspondence of William of Orange nr. [number of letter or document], date consulted. URL[number]. Example: [Willem van] Oranje to Filips van Hessen, 12-12-1560, The Correspondence of William of Orange nr. 5097, 8-2-2005. URL

## 2.5 Licenses and Accesses<a id='level-2-licence'></a>
This section tells you how you can access the dataset and under which licence(s) it may be used. Access may be direct or via a portal application. A dataset can have multiple access/licence combinations. For example, it may be browsable via an Open Access portal, while content may be downloadable via a Restricted Access portal with a licence permitting reuse.

A licence should not only be specified when access is restricted, but also when access is open. The licence determines what the user is allowed to do with the dataset. Not filling in a licence is ambiguous. In the absence of a licence, users could assume they can do anything they want, or they could assume they cannot do certain things that may actually be permitted. 

The Huygens default licence is given on [this page](https://www.huygens.knaw.nl/informatie/disclaimer-en-copyright/)

### Licensing Information

Choose a licence that suits how you want users to be able to use the material.  If no licence can be given (for example if users need to make special arrangements to use the dataset), then describe how the user can find out what they need to do in the Access section below.

Note: Huygens Institute has specified a default licence that should be assumed in the absence of other information about the licence, see [this information page](https://www.huygens.knaw.nl/en/informatie-2/disclaimer-and-copyright/) for more details. 

* Identifier - the identifier of the licence used. E.g. CC0 1.0 Universal 
* URL - the URL to the information about the licence. E.g. https://creativecommons.org/publicdomain/zero/1.0/. 

## Access

* Access Level - Select one of the access levels

### Access Open
If the level is 'open access', then you can enter more information about how the open access works

* Description - a description of how to access the data. Also provide any prerequisites for acceptable use, such as reading data usage policy.
* URL - A link to instructions and/or the access page
* Contact email -  email for users to reach out with any questions or concerns regarding data access

### Access Restricted
If the level is not open access, then you can enter more information about how access works and why it is restricted

* Description - description of the access restriction. Include an explanation of why access controls are in place. Also highlight any restrictions or limitations such as geographical restrictions, time-limited access, or requirements of fees, national regulation, etc. Also provide any conditions for acceptable use, such as reading data usage policy.
* URL - A link to instructions and/or page to request access
* Contact email -  email for users to reach out with any questions or concerns regarding data access
* Access prerequisites - a description of the prerequisites for access. E.g., users must be affiliated with a research organisation

## 2.6 Dataset Version and Maintenance<a id='level-2-version'></a>
### Version

* Current Version - the current version of the dataset. Fill in a number here. Typically this is '1' for the first version of the dataset. An alternative option, particularly for datasets that have been in existence for some time already, could be to use the year. You can agree a numbering system with your team. This should be the same as the version number in 2.1.
* Last Updated - the date on which the dataset was last updated
* Release Date - the date on which the latest version was released

### Maintenance
This section contains information about how the content of the dataset will be maintained. Is it complete, will it be updated, will reported errors be corrected etc.
It is not per se necessary to include information about technical updates to storage, servers, software etc. unless these will have a noticeable impact on users. For example, if the dataset will be unavailable for one day a month while updates are carried out, then this is a significant disruption to the user and is useful to mention. Or if technical updates will cease when a project finishes then this may increase the risk that the dataset becomes inaccessible.

* Maintenance status - an indication of the extent to which the dataset is maintained
* Maintenance Plan - a plan for how the dataset will be maintained
  * Updates - Information about criteria for updating the dataset. Include information on how errors are triaged or handled, and criteria for updating the dataset. For example, a dataset of parliamentary members might be updated after every election.
  * Feedback - Email/contact information for users to communicate errors in data and technical issues
 * Next planned Update
   * Version affected - the number of the version that will be updated
   * Date of next planned update - the date on which the dataset will be updated
   * Next Version - the number of the next version
  
  Examples of maintenance plans:

  Release of new data
  
      Reported errors in the index will be corrected. Access to cards will be unblocked either 1) after the death of the person in question is reliably reported, 2) 105 years have passed since their date of birth or 3) during periodic verifications of the data against the data held bij the CBG (Centraal Bureau voor Genealogie, Central Office of Genealogy). Otherwise the dataset is static and is not updated.

 Only improvements or corrections

      This dataset will not be further enlarged. Possibly the transcriptions will be updated with improved versions.

 No maintenance
 
      This dataset will not be further updated or enlarged.

  ## 2.7 Feedback and Elaboration<a id='level-2-feedback'></a>
  Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful 

  # Level 3 Data
  This level goes much deeper into the dataset. It should help the user use it in a correct and responsible manner. It describes how the dataset was created, and how it is structured. There is also the opportunity to describe important issues such as errors, biases, sensitivity and confidentiality. 

 Level 3 represents a Resource of the dataset. A Resource is something that a user can utilise to work with the dataset. A Resource can be a downloadable file, or a search portal in which the dataset can be browsed, or an endpoint for querying the data, etc. The entire level can be repeated. Each repetition represents a Resource within the dataset. Different Resources may be used, for example, to describe different files within the data. They can also be used to describe different variants that are available, for example an open version and a restricted version, if these differ significantly in how they are created or what they contain. However, you can combine multiple files or multiple versions within the same Resource. When deciding how many Resources to use to represent the dataset, consider how much of the information in Level 3 the Resources have in common, how easy it is to describe each Resource clearly and how easy it is for the user to understand what is available to them.  If you are in doubt about how many Resources to use, read the [guidelines](guidelines.md).

 Level 3 gives the opportunity to fill in a lot of detail, which may not be necessary for all datasets. Fill in as much as you think is useful to your users.

  ## 3.1 Data Resource Description<a id='level-3-data-resource-description'></a>
  This describes some basic information about the Resource, such as name, description, format and size. Depending on the dataset, some fields may be a repetition of information from Level 2, or it may be different. For example, if a dataset is split into different language files, then the Languages in Level 2 may be 'German, Dutch and French', while the language of the Resource representing the German section will just be 'German'. However, if all of the Resources were a mix of the three languages then both Level 2 and all Resources would have 'German, Dutch and French' for their Languages. 

  * Name - the name of the Resource. This should distinguish it from other Resources. For example, 'Wartime Radio - audio files', and 'Wartime Radio - transcripts'.
  * Description - a description of the particular Resource. This should describe what is in the Resource, if this is different to the whole dataset. It often contains information on how the Resource was created. For example, if a dataset contains a Resource that is a set of persons detected in letters, then the Resource Description could explain how Named Entity Recognition was used to detect the persons. The description also often contains information on how to use the Resource. See the [guidelines](guidelines.md) for how this description differs from the description on Level 2.
  * Path - the URL where the Resource can be found. E.g. https://zenodo.org/records/14848884
  * Format - one or more file extensions that are in the Resource, e.g. csv, json, xls
  * Size - the size of the Resource (if it is downloadable)
  * Date - the date on which the Resource was created
  * Language(s) - the language(s) used in the Resource. Note: this may be more specific than the languages for the whole dataset.
  * Encoding - the character encoding, if the Resource is a data file
  * Data Subjects
    * Subject(s) - A selection of the subjects of the data from a vocabulary
    * Other Data Subject(s) - if the vocabulary does not contain appropriate subjects, then they can be filled in here
* Data modality
    * Modality - one or more data modality (e.g. image, text) selected from a vocabulary. The option 'Multimodal' means that the dataset is inherently a combination of multiple types together. For example if a dataset contains a video with in-screen subtitles, then that video is a combination of the modalities of video and text, which can't be separated, and is therefore multimodal. For a dataset with videos and separate subtitle files, you can select both 'video data' and 'text data' as the modalities.
    * Other Modalitie(s) - if the vocabulary does not contain appropriate modalities, then they can be filled in here
* Descriptive statistics - this can be used to describe the Resource with statistics, e.g. how many persons, how many different countries, the distribution over time. It can also be used to link to a page where statistics are published. E.g. '72000 scans, 101 inventory numbers, 297 shipmaster names, 275 ship names, 6 different languages (uncertain)' or 'See the Amateurfilms page on data.beeldengeluid.nl (see links in Section 2.4) for various statistics' 

## 3.2 Data Fields<a id='level-3-data-fields'></a>
These describe the individual data fields in the Resource. For example, for a spreadsheet the column and/or row headers could be described. It is also possible to link to a schema that describes the Resource structure, instead of describing the individual data fields.

If the data fields are described in the Resource file itself or they are self-explanatory, then you can skip this section.

General or overarching information about the data structure can be included in the description in Section 3.1.

### External Schema
Click on the tickbox here if your dataset uses an external schema. The following fields will appear:

* External Schema Link - A link to the schema describing the dataset structure
* External Schema Note - Space for any additional information describing the schema, for example, how or why it is used, or if only a subset of the schema is used.

### Data Field
This section is used to describe each data field in the dataset. It should be repeated for each data field described, by clicking on the plus icon. 

Some datasets have large numbers of data fields. It is not always necessary to describe every data field. Give priority to the data fields that most users will find useful. 

If you link to an external schema, then it is not necessary to fill in the individual data fields. You may still do so however if you want to call special attention to particular data fields. 


Each data field can have the following information:

* Data Field name - label or identifier of the data field
* Data Field Type - The type of the field, for example common ones are string, integer, boolean.
* Description of the data field - a description of what the field represents, including any specific details about the data format or structure. E.g. 'Name of the ship. If a place of origin is known it is mentioned behind the ship name in brackets; ship names in more than one language are listed next to each other'
* Sensitivity - this indicates whether the data stored in this specific field is sensitive. Sensitive data might include personal information that could be harmful if exposed, such as social security numbers, personal addresses, or health information. This helps users to distinguish between sensitive and non-sensitive fields. Information about the sensitivity at the dataset level can be included in section 3.7.
* Notable Features - any important or unique attributes of the field that might be relevant for users or systems interacting with the data
* Used Vocabularies - if a field uses a taxonomy or vocabulary then this can be described here
  * Vocabulary - a summary of the linked open data scheme, controlled vocabulary, ontology or taxonomy used during the establishment of the dataset. E.g. 'GTAA - Person scheme'
  * Vocabulary link - a link to the taxonomy or relevant documentation that describes it. E.g. 'https://data.beeldengeluid.nl/datasets/gtaa'

## 3.3 Data Point Examples<a id='level-3-examples'></a>
### Typical Example

Here you can include an example of how the data typically appears in the Resource. You can copy and paste text or numerical data, or a row from tabular data, or you can describe the example (e.g. a recording of the 8pm broadcast of the daily news, recorded on 15th November 2004). If data points can be linked to, include the link so that users can examine it themselves.

* Description - a description of a typical example of a data point. E.g. 'Broadcast of an amusement program', or ''
* Link - a link to the data point

Examples

A descriptive description:

    a recording of the 8pm broadcast of the daily news, recorded on 15th November 2004

A copy of a data point:

    <indexRecord id="saaId24681019">
    <toegangsnummer>5001</toegangsnummer>
    <inventarisnummer>7</inventarisnummer>
    <datering>1643</datering>
    <kind><voornaam>Marija</voornaam></kind>
    <doopdatum>1635-01-25</doopdatum>
    <kerk>Oude Kerk</kerk>
    <godsdienst>Hervormd</godsdienst>
    <vader><voornaam>Joost</voornaam><tussenvoegsel>van den</tussenvoegsel><achternaam>Boogaert</achternaam></vader>
    <moeder><voornaam>Angnieta</voornaam><achternaam>Selijs</achternaam></moeder>
    <bronverwijzing>DTB 7, p.27</bronverwijzing>
    <urlScan>https://archief.amsterdam/inventarissen/inventaris/5001.nl.html#A28220000016.jpg</urlScan>
    </indexRecord>


### Atypical Example

Here you can include an example of known oddities or outliers in the Resource.

* Description - a description of an atypical example of a data point
* Link - a link to the data point, if possible

## 3.4 Errors, Noise and Redundancies<a id='level-3-errors'></a>
Here any errors, noise, gaps or redundancies in the Resource can be described. For example, if all data from a particular country is missing for the second half of the temporal scope, or if some dates are uncertain. Do not include biases in the data here, these should be mentioned in Section 3.7.

Example for missing data:

    The transcripts cover the vast majority of these scans, the exceptions being:

    the initial pages of filza (folder) 02 are not transcribed, the transcripts start at page 71;
    the entire filza 9b (marked as 9-bis) is not transcribed.

    The pages with missing scans are:

    filza 9, pages 120r and 120v;
    filza 12, pages 278r and 278v.
    There are no transcripts for these pages.

## 3.5 External Resources<a id='level-3-external'></a>
The dataset may link to external resources. For example, to pages on Wikidata describing persons, or to images stored in an image bank, or to documents in a digital archive. 

* Resources - this states if the dataset contains links to external resources, yes or no
* External Resources Description - this specifies what external resources are linked to, and how and why the dataset relies on them. 
* External Resources Links - this provides links to the external resources (at the level of the source, not an individual resource. For example, Wikidata, not the individual persons in Wikidata)

E.g.:
    Concepts in the GTAA thesaurus https://data.beeldengeluid.nl/datasets/gtaa

## 3.6 Annotation and Labelling<a id='level-3-annotation'></a>
The original data in the dataset may have been enriched by annotating or labelling it with extra information. This may be done by humans or machines. For example, experts may have labelled letters with the persons mentioned in the letters, or an algorithm may have detected persons in the letters. These annotations can be described in this section.

### Annotation Characteristics
This section can be repeated for each type of annotation performed.

* Annotation workforce type - the type of humans, or machines, that performed the annotation, selected from a vocabulary. E.g. 'Human Annotations (Expert, Employees)'
* Others - if the workforce type was not in the vocabulary, it can be filled in here
* Description - a description of the annotation that was performed. E.g. 'Experts transcribed the scanned letters'
* Total Annotations - the total number of annotations
* Total Tokens - the total number of tokens that were used in the annotations
* Avg Tokens Annotations - the average number of tokens per annotation
* Metric - 

## 3.7 Social Impact, Sensitivity and Biases<a id='level-3-social'></a>

### Safety Consideration
Here you can answer, with yes or no, the question 'Does the resource contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety?'. If the answer is yes, then you can specify how and why. E.g. 'The diary entries reflect the views of the time' or 'Descriptions may contain offensive terms'

### Confidentiality
Here you can answer, with yes or no, the question 'Is the dataset confidential?'. If the answer is yes, then you can specify what measures were taken to avoid disclosure of personal information. 

### Biases

Known Biases in the Resource - Identify any known biases present in this dataset, such as stereotyping, underrepresentation, overrepresentation, or misrepresentation of certain social groups. Briefly describe the nature and, if possible, the extent of these biases to help users make informed decisions and mitigate potential harms.

Steps taken to Mitigate/Reduce Biases - Describe the steps taken to reduce or mitigate biases in the dataset.

E.g. 'This is the correspondence of a member of the royal family, so it does not offer a representative view of society at the time.'

### Sensitive Attributes

* Sensitive Human Attributes - Specify if the dataset contain data that might be considered sensitive in any way (e.g., data that reveals race, sexual orientation, age, ethnicity, disability status, political orientation, religious beliefs, union memberships; location; financial or health data; biometric or genetic data; criminal history). You can choose from a list of sensitive attributes or choose 'Others'
* Specify - If you selected 'Others', then you can specify them further here. 
* Unintentionally Collected Attributes - any human attributes that were not explicitly collected as a part of the dataset creation process but were accidentally/unavoidably included or can be inferred using additional methods

For older datasets, it may be the case that they contain sensitive human attributes, but that the people involved are long dead. In this case, choose 'Others' and then add an explanatory text under 'Specify', e.g. 'The data contains sensitive human attributes but all persons are no longer living'. This is preferable to filling in 'None' for the sensitive human attributes, as in that case a dataset user may then see sensitive attributes in the data and become concerned that the data-envelope is incorrect.

### Ethical Review

* Review - an indication, yes or no, if an ethical review was carried out
* Description - if an ethical review was carried out, enter a brief description of the ethical review (e.g. who carried it out and when, any reference number or other identifier). 
* Outcomes - the outcomes of the review and how they influenced the dataset creation. E.g. 'The publication was deemed lawful. An advert was placed making people aware of the plans to publish the residential registration cards and allowing them to object to their card being made available, within 6 weeks of the advert being placed.'
* Link - link to any further information about the ethical review
* Ethical Review Contact - a person who may be contacted in relation to questions on ethical review
  * Name - full name of the person
  * Affiliation - organisation that the person works for
  * Email - their email address

## 3.8 Data Provenance<a id='level-3-prov'></a>
The dataset may have used one or more sources in its creation. For example, a set of digital scans of letters is produced by scanning the original paper source of the letters. 

Note that this is different to 3.5 External Resources. Sources in Section 3.8 were used as inputs to create the dataset. Sources in Section 3.5 are referred to within the dataset to enrich it. For example, if an archive of paper letters is digitised and the scans are made available as a digital dataset, then the original paper archive would be referenced in 3.8. If the digital scans are linked to Wikidata biographies of the persons discussed, then Wikidata would be included in 3.5 as an External Resource. 

Note that this section does not refer to Data Provenance in terms of the chain of previous owners of a dataset.

For each source used, the following information may be filled in:

* Name - the name of the source
* URL - a URL of the source
* Description - a brief description of the source and why it was used. For example, "this archive contained the original paper letters that were digitally scanned to create the letters dataset"
* Creator Name(s) - names of individual creators of the source 
* Creator Organisation(s) - names of affiliated organisations or creating organisations
* Year of publication - the year in which the source was published
* Language(s) - the language(s) of the original source
* Temporal scope - the temporal scope of the source
* Geographical scope -  the geographical scope of the source
* Notable features - any notable features and known biases and issues with the source
* Datasheet/data-envelope - a link to a datasheet/data-envelope on the source 
* Data Selection - how data was selected from the source to be used in the current dataset. For example "all documents of the type 'letter' were selected"


## 3.9 Digitisation<a id='level-3-digitisation'></a>
Describe the pipeline used for digitisation. If applicable, describe in what way digitisation presents another layer of selection of the whole of a collection available in a cultural heritage institution; otherwise state that all available items were digitised. If applicable, provide selection criteria and metrics that demonstrate how this additional layer of selection has influenced the transformation of the original collection or dataset into the current dataset. 

Example:
    All residential registration cards were digitally scanned. Most were scanned with automatic feed. A number of thicker cards were manually scanned. Image optimisation was applied to the           scanned images, using a light and dark profile, determined by the pixel values of the scan. As the digital scans were intended to replace the paper originals, many checks were performed on       the scans. For details, see the 'Overbrenging Amsterdamse woningkaarten 1954-1989' report linked in Section 2.4 

## 3.10 Feedback and Elaboration<a id='level-3-feedback'></a>
Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful 

# 4 Uses<a id='level-4-uses'></a>
This level describes the uses for which the dataset was designed, what it has been used for and what are suitable uses of the dataset according to the dataset provider. It also lists unsuitable uses.

* Purposes - one or more purposes of the dataset can be selected from a vocabulary. If no relevant purpose is included, you can select 'Other'
* Other - if other was selected then the purpose can be specified here
* Domain(s) of Application - the domains for which the dataset was designed can be specified using a vocabulary
* Motivating Factor(s) and Problem space(s) - What motivated the creation of this dataset? Did the creators already have a specific use in mind? Provide a description of the specific problem space that this dataset intends to address. E.g. 'The diaries were published to aid historical research. The books containing the diary entries were digitised as part of work to make the entire RGP (Rijks Geschiedkundige Publicatien) series belonging to the Huygens Institute digitally available. '

The motivating factors are very important as these will shape many decisions that have a big effect on the dataset. For example, an archive could digitally scan documents with the intention of creating digital copies and discarding the paper originals, with the intention of making the documents searchable, or with the intention of testing a new scanning tool. In the first case then the scans should be a digital copy of high quality. In the second case a lower quality is acceptable as the user only needs to be able to discover keywords in the scan. In the third case the documents themselves are not the focus of the dataset so the dataset of digital scans may not be at all representative of the dataset of paper documents, for example it may be that only robust documents that fit the scanner format were scanned.

## 4.1 Uses<a id='level-4-1-uses'></a>
There may be multiple types of use possible for the dataset, e.g. both research and production, so this section can be repeated per use.

* Dataset Use - the type of use of the dataset can be selected from a vocabulary. E.g. 'Safe for research use'
* Explain for special cases chosen above - If a special use has been selected, then this can be explained here.
* Links to Related Items
  * Publications - URL(s) or descriptions of publication(s) introducing or describing the dataset
  * Related datasets - dataset(s) that use this dataset
  * Model trained by dataset - model(s) that were trained on this dataset
* Suitable use cases - one or more cases for which the dataset is regarded as suitable by the dataset creator. These can be existing or proposed uses. Links can be included where appropriate, for example to a web application that uses the dataset. Additional notes can be filled in 
* Unsuitable use cases - one or more cases for which the dataset is regarded as unsuitable by the dataset creator. It is useful to include the reason. This may be due to legal or ethical reasons, to quality or bias issues, policies of the dataset creator etc. Additional notes can be filled in.

Example of a suitable case:

    Researching or writing about game history or the game industry

Example of an unsuitable case:

    Searching for word frequencies or word use, due to OCR errors.

## 4.2 Use with Other Data<a id='level-4-2-uses'></a>
Datasets that are safe to use on their own may not be suitable to use with other data. For example, combining sets of data about anonymised persons may allow the persons to be identified.

It is often difficult to judge the safety of use with other data. If in doubt, select the 'Unknown' option. You can then leave the rest of the section empty.

* Safety Level - select a level from a vocabulary. If no level is appropriate, choose 'Other'
* Other - if 'Other' was chosen then this can be specified
*  Known safe dataset(s) or data type(s) - a list of the known datasets (provide link) or data types and corresponding transformations that are safe to join or aggregate this dataset with
*  Known unsafe dataset(s) or data type(s) - a list of the known datasets (provide link) or data types and corresponding transformations that are unsafe to join or aggregate this dataset with

## 4.3 Use in ML or AI systems<a id='level-4-ai'></a>
Datasets may or may not be suitable for use in ML or AI systems. This may be due to legal or ethical reasons, to quality or bias issues, policies of the dataset creator etc. In this section you can indicate if usage for ML/AI is allowed and offer guidelines for good usage.

It is often difficult to judge the suitability of data for ML/AI. If in doubt, select the 'Unknown' option. You can then leave the rest of the section empty.

* Dataset Uses - select a level from a vocabulary. If no use is appropriate, choose 'Other'
* Other dataset use - if 'Other' was chosen then this can be specified
* Notable Feature(s) - any notable feature distributions or relationships between individual instances made explicit
* Known correlations -  any known correlations with the indicated features in this dataset
* Usage Guidelines - summary or link to usage guidelines or policies that users should be aware of in using this dataset for ML purposes
* Data splits - Provide a description of any recommended data splits (e.g., training, development/validation, testing), explaining the rationale behind them

## 4.4 Sampling<a id='level-4-sampling'></a>
Datasets may or may not be suitable to be sampled. 

It is often difficult to judge the suitability of data for sampling. If in doubt, select the 'Unknown' option. You can then leave the rest of the section empty.

* Safety Level - select a level from a vocabulary. If no level is appropriate, choose 'Other'
* Other - if 'Other' was chosen then this can be specified
* Acceptable Sampling Methods - all applicable methods to sample this dataset, chosen from a vocabulary. If a method is missing from the vocabulary, choose 'Other' 
* Other - if 'Other' was chosen for acceptable sampling methods then this can be specified here
* Best Practice(s) - advice on best practices for sampling can be entered here. 
* Risk(s) and Mitigation(s)- known or residual risks associated with sampling methods when applied to the dataset and how they can be mitigated.

## 4.5 Feedback and Elaboration<a id='level-4-feedback'></a>
Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful

# Level 5 Human Perspective
All datasets are influenced by the choices of the human beings who create them, whether this is by the selection of the data, the construction of a data model, the choice of a software algorithm etc. These choices are often made against a background of a particular research question, a particular use, the experience and interests of the creators, and their social, ethnic, cultural and gender backgrounds. 

In dataset documentation, embracing this human perspective is vital for various reasons. Firstly, it illuminates the biases and assumptions that may influence data collection and analysis. Secondly, it provides transparency, allowing users to understand the context in which the dataset was created and to consider how this context may affect their use of the data. Thirdly, it promotes inclusivity by recognising the diverse standpoints of dataset creators and subjects, encouraging a multiplicity of perspectives in data interpretation. 

The human perspective section is related to the bias section, but it has an important difference. Biases in Section 3 are already detected and known in the dataset. The choices made due to a human perspective may result in a dataset that is well suited to the creator's context but that has a serious bias when approached from a different domain and perspective. For example, think of an AI trained on product reviews in America by marketeers that is then applied to sentiment detection in television programmes in the Netherlands by academic researchers. Knowledge of the human perspective can help in identifying the match with different domains and uses, and in asking critical questions about the suitability of a dataset for a particular purpose. 

The backgrounds of contributors can also affect the dataset. For example, if non-Dutch contributors transcribe Dutch place names, then there may be more errors than if native Dutch contributors performed the transcription. At the same time, a non-Dutch historical expert may be more successful in the transcription of historical documents than a Dutch layperson.

Avoid speculations when writing this section and stick to facts. For example, state that Dutch place names were transcribed by non-Dutch contributors. Do not add 'so there were probably more errors' unless this has been measured to be the case. 

## 5.1 Human Annotators<a id='level-5-annotator'></a>
Human annotators - people who enriched the original data with extra information such as labels - have a large influence on the results of the annotation process. For this reason, it is important to know information about the annotators that may have influenced the results. For example, native Dutch speakers may have different results when annotating documents with Dutch placenames than native English speakers. Information about the annotation instructions is also important here, as the instructions can help in standardising responses over annotators, reducing their own influence on the results. 

This section focuses on **who** created the annotations, not on **what** is in the annotations. A description of what was annotated can be entered in Section 3.6.

For creators and contributors, you can fill in relevant information in Section 5.2.

* Annotator description - This contains a short description of each annotator group. E.g. 'Dutch History Experts', 'Crowdsourced laypersons'.
* Annotation Type - this is filled in for each different type of annotation performed. 
  * Task type - a summary of the task type. Include any links. Ideally connect to some existing taxonomy: survey, video annotation, text annotation, image annotation, etc
  * Number of unique annotators
  * Average number of Annotations per Annotator
  * Expertise of annotators - for example, 'archival and historical knowledge and reading and understanding historical Dutch' or 'None'
  * Description of annotators - e.g. 'The annotators were all experts working in archives or in historical research.' or 'Employees of contractor in India, non-Dutch speaking' 
  * Compensation - how they annotators were compensated for their effort. Indicate here whether they were crowdsourced or not, and if not, what compensation they received. For example, 'compensated as per the Dutch CAO'.
  * Language distribution of annotators - what were the languages spoken by the annotators?
  * Num Language Distrib - how many annotators spoke each language?
  * Age distribution of annotators - what was the age range of the annotators?
  * Number of each age group - how many annotators were in each age group?
  * Geographical distribution of annotators - where the annotators reside. For example, 100% reside in the Netherlands.
  * Gender distribution of annotators - For example, 60% identify as women, 40% as men.
  * Socio-economic distribution of annotator. For example, 40% identify as lower middle class, 60% as middle class.
  * Summary of annotation instructions - what instructions the annotators were given in how to carry out the annotation task.  Include links, say to the annotation instructions, readme. E.g. 'See https://suriano.huygens.knaw.nl/about/ for the transcription rules'
  * Annotation platform(s) - which platform(s) were used to create the annotations. Include links 
  * Additional Notes - Any other comments. For example: 'During the annotation process all annotators were trained to read and understand the original texts by the archival expert and were invited to compare the HTR texts with the scans of the original. This way of working proved instrumental in overcoming limitations of HTR quality'.

  ## 5.2 Creators and Contributors<a id='level-5-contributor'></a>
  ### Description of potential positionality impact factors
  This section can include any aspects that could have impact on the work in terms of positionality of the creators and contributors, e.g. particular domain of expertise, gender, age, etc. As it can be hard to judge what may have an impact, one option is to give a short bio for each creator/contributor. Be careful to respect the privacy of contributors.

  E.g. 'The creators and contributors were student assistants and researchers employed at the Dutch universities of Amsterdam and Leiden'

  ## 5.3 Feedback and Elaboration<a id='level-5-feedback'></a>
  Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful
