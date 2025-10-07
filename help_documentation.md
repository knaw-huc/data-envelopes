# Help documentation for fields
This page contains help documentation, including examples, for the fields in a data-envelope as implemented in the Huygens Data-Envelope editor.

# Basic workflow
The editor opens showing a list of all data-envelopes in a table. 

You create a data-envelope by clicking the plus icon in the top of the table. 

Fill in as much of the information in the data-envelope as you can, referring to the help information below. You may know the information yourself, or you may need to look it up in existing dataset documentation, such as the Resource page. For some fields, you may need to ask colleagues for assistance. They can fill in the data-envelope themselves if they have a log-in, or they can answer your questions and you can fill in the information yourself. Note: it is not advisable to work on the same data-envelope simultaneously, agree who will work on the data-envelope in a particular period. 

 **Be sure to regularly save your work by pressing the Save button**

Some fields in a data-envelope are compulsory. These are marked with a star in the editor. If these fields are not filled in, then the data-envelope will fail validation. Validation occurs when you press the Submit button. You can save an invalid envelope, but you can not successfully submit it. 

For all other fields, the rule is to fill in as much as you reasonably can. Priority should be given to the information that is most important for your particular dataset.

When you have completed the data-envelope, ask a colleague to review it. If they have access to the editor, then they can review it there. Otherwise, you can download a copy from the table (in PDF, HTML or CDMI format) and send this to them for review. 

Once the data-envelope is completed, click on Submit. If any compulsory fields are not filled in, then error messages will appear

# Administrative information
At the top of the data-envelope there is some basic administrative information

* Institute - select your institute
* ID - this will be filled in automatically the first time you save the data-envelope
* Status - this will be initialised to 'under construction' when you first save the envelope

# Level 1 Basic Information
This level describes the data-envelope itself and the dataset contact person.
## 1.1. Title of Data-Envelope
A title for the data-envelope, NOT the dataset. Follow the format: Dataset Name Version-X Data-Envelope Version-Y. E.g. Baptism Registers Amsterdam Version-1 Data-Envelope Version-1.
The first version number refers to the version of the dataset being documented, the second version number refers to the version of the documentation itself. Typically the version number is '1' for the first version of the dataset or the envelope. You can agree a numbering system with your team.

## 1.2 Contact Details
This should contain information about the contact person for the dataset.

* Name - The full name of the contact person
* ORCID ID - If available, the [ORCID](http://orcid.org) identifier for the contact person
* Role in project - You can define one or more roles that the contact person played in the creation of the dataset. Leave empty if no roles are applicable.
* Email - an email address for the contact person. The recommendation is to use a general institutional address to avoid problems when people move to new institutions. E.g. data@myinstitution.org

## 1.3 Data Envelope Dates
This contains the dates for the data-envelope

* Data-Envelope Creation Date - the date on which the data-envelope was created
* Data-Envelope Completion Date - the date on which the data-envelope was completed
* Data-Envelope Publication Date - the date on which the data-envelope was published

## 1.4 Author of Data-Envelope
This should contain information about the primary author of the data-envelope itself.

* Name - the full name of the primary author
* ORCID ID - If available, the [ORCID](http://orcid.org) identifier for the primary author
* Email - an email address for the primary author. The recommendation is to use a general institutional address to avoid problems when people move to new institutions. E.g. data@myinstitution.org

## 1.5 Feedback and elaboration
Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful. For example, you can indicate to what extent the necessary information for the data-envelope was easily available: was this a current project with experts available to answer all the questions, or is it data from fifty years ago for which the description has been pieced together from old documentation sources? You can also indicate what information sources you used to fill in the data-envelope, if you wish. 

# Level 2 Basic Metadata
This level describes the basic dataset metadata. This includes: what the dataset contains, what the temporal and geographical coverage are, how it can be accessed etc. This section conforms to the Data Catalog Vocabulary (DCAT) standard, ensuring compatibility with machine-readable formats.

## 2.1 Snapshot
This contains information about what is in the dataset.

There is some discussion as to what should be included in the temporal and geographical coverage. For example, for a collection of letters the geographical coverage could refer to the locations the letters were sent to/from, or the locations discussed in the letters. Try to think about what information is most useful for users of the dataset. 

* Dataset title - the title of the dataset
* Version - the version number of the dataset. Typically this is '1' for the first version of the dataset. You can agree a numbering system with your team. This should be the same as the version number stated in the data-envelope title.
* Description - Provide a free text account of the dataset or resource (limit 200 words). Include information about the content and topic of the data and what makes the dataset useful.
* Genre - One or more genres from a vocabulary that apply to the dataset
* Other Genre - Genres that apply to the dataset that are not included in the vocabulary
* Topic Classification - One or more topics from a vocabulary that apply to the dataset
* Other Topic - Topics that apply to the dataset that are not included in the vocabulary
* Languages - One or more languages from a vocabulary that apply to the dataset. This refers to the natural language used for textual metadata (i.e., titles, descriptions, etc.) of a cataloged resource (i.e., dataset or service), in audio/video or the textual values of a dataset distribution.
* Other Language - Languages that apply to the dataset that are not included in the vocabulary
* Geographical coverage - This refers to the geographical area pertaining to the datasets. One or more geographical areas from a vocabulary that apply to the dataset
* Other Geographical coverage - Geographical areas that apply to the dataset that are not included in the vocabulary

### Temporal coverage

This refers to the temporal coverage of the content of the dataset, not the dates on which the dataset was created (these should be entered in section 2.2). This could be the date range of the creation of the original items (e.g. for a collection of sixteenth century letters it could be the earliest and latest dates on which letters were sent) or it could be the period discussed in the dataset (e.g. interviews recorded discussing the Second World War in the Netherlands might cover the temporal range 1940-1944). Choose what is most relevant for users of the dataset to know.

* Temporal coverage Start - the first year of the temporal scope
* Temporal coverage End - the last year of the temporal scope
* Year - in the case that the temporal scope cannot be captured in a range, this field allows you to specify the individual years that are relevant to the scope of the dataset
* Additional Notes - Specify any additional information about the temporal scope of the dataset. This could include gaps in the coverage, or years that contain more data.

## 2.2 Dates
These dates refer to the time span during which the dataset was created. For example, the start and end date of the project to collect and digitise the data. The date on which the dataset is published is also specified.

* Date From - when work on the dataset started
* Date To - when work on the dataset was complete
* Date Published - when the dataset was published

## 2.3 Creators and Contributors
In this section you can list the people who contributed to the creation of the dataset, for example by curating data, managing the project, providing functing etc. 

### Publishing Organisation
This is the organisation responsible for publishing the data.

* Name - the name of the publishing organisation. Be consistent with how you fill in the name.
* ROR ID - if available, the [ROR](http://ror.org) identifier for the organisation
* Type - the type of the publishing organisation. Choose 'Other' if none of the other types apply
* Other - if you chose 'Other' for the type, specify the type of the organisation here

### Creators
Creators are responsible for the creation of the dataset. There is no strict definition of the difference between a creator and a contributor, but generally a creator makes decisions about the dataset content, while a contributor assists in creating the dataset. You can include as many creators and contributors as you like.

* Name - full name of the creator
* ORCID ID -  If available, the [ORCID](http://orcid.org) identifier for the creator
* Organisation - the name of the organisation the creator was affiliated to at the time at which the dataset was created. Be consistent with how you fill in the name.
* ROR ID - if available, the [ROR](http://ror.org) identifier for the organisation
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
* ROR ID - if available, the [ROR](http://ror.org) identifier for the organisation
* Funding or grant summary - a short summary of person or organisation and grant that funded the creation, collection, or curation of the dataset. Include any reference numbers.
* Link - a link to any further information about the funding

## 2.4 Distribution
This section specifies where you can get the dataset or further information about the dataset, information on available downloads and on how to cite the dataset

* Dataset Link - This is a link that identifies the dataset. For instance its DOI, Handle, or ARK
* Repository - One or more links to information about the dataset. If the dataset has its own dedicated website(s) or is hosted on sites such as github, zenodo, dataverse, marketplace, provide the url(s) here. Documentation and FAQ pages can also be linked.
* Download
  * Link - one or more download links for the dataset
  * File/folder type - the type that is downloaded. For example, .zip for an archive file.
  * File Size - the size of the downloaded content, in MB
* Citation - the text that should be used to cite the dataset

## 2.5 Licenses and Accesses
This section tells you how you can access the dataset and under which licence(s) it may be used. Access may be direct or via a portal application. A dataset can have multiple access/licence combinations. For example, it may be browsable via an Open Access portal, while content may be downloadable via a Restricted Access portal with a licence permitting reuse.

A licence should not only be specified when access is restricted, but also when access is open. The licence determines what the user is allowed to do with the dataset. No license is ambiguous. In the absence of a licence, users could assume they can do anything they want, or they could assume they cannot do certain things that may actually be permitted. 

### Licensing Information

Choose a licence that suits how you want users to be able to use the material.  If no licence can be given (for example if users need to make special arrangements to use the dataset), then describe how the user can find out what they need to do in the Access section below.

Note: Huygens Institute has specified a default licence that should be assumed in the absence of other information about the licence, see [this information page](https://www.huygens.knaw.nl/en/informatie-2/disclaimer-and-copyright/) for more details. 

* Identifier - the identifier of the licence used. E.g. CC0 1.0 Universal 
* URL - the URL to the information about the licence. E.g. https://creativecommons.org/publicdomain/zero/1.0/. 

## Access

* Access Level - A selected access level

### Access Open
If the level is 'open access', then you can enter more information about how the open access works

* Description - a description of how to access the data. Also provide any prerequisites for acceptable use, such as reading data usage policy.
* URL - A link to instructions and/or the access page
* Contact email -  email for users to reach out with any questions or concerns regarding data access

### Access Restricted
If the level is not open access, then you can enter more information about how access works

* Description - description of the access restriction. Include an explanation of why access controls are in place. Also highlight any restrictions or limitations such as geographical restrictions, time-limited access, or requirements of fees, national regulation, etc. Also provide any conditions for acceptable use, such as reading data usage policy.
* URL - A link to instructions and/or page to request access
* Contact email -  email for users to reach out with any questions or concerns regarding data access
* Access prerequisites - a description of the prerequisites for access E.g., users must be affiliated with a research organisation

## 2.6 Dataset Version and Maintenance
### Version

* Current Version - the current version of the dataset. Fill in a number here. Typically this is '1' for the first version of the dataset. You can agree a numbering system with your team. This should be the same as the version number in 2.1.
* Last Updated - the date on which the dataset was last updated
* Release Date - the date on which the latest version was released

### Maintenance
This section contains information about how the content of the dataset will be maintained. Is it complete, will it be updated, will reported errors be corrected? etc.
It is not per se necessary to include information about technical updates to storage, servers, software etc. unless these will have a noticeable impact on users. For example, if the dataset will be unavailable for one day a month while updates are carried out, then this is a significant disruption to the user. 
* Maintenance status - an indication of the extent to which the dataset is maintained
* Maintenance Plan - a plan for how the dataset will be maintained
  * Updates - Information about criteria for updating the dataset. Include information on how errors are triaged or handled, and criteria for updating the dataset. For example, a dataset of parliamentary members might be updated after every election.
  * Feedback - Email/contact information for users to communicate errors in data and technical issues
 * Next planned Update
   * Version affected - the number of the version that will be updated
   * Date of next planned update - the date on which the dataset will be updated
   * Next Version - the number of the next version

  ## 2.7 Feedback and Elaboration
  Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful 

  # Level 3 Data
  This level goes much deeper into the dataset. It describes how the dataset was created, and how it is structured. There is also the opportunity to describe issues such as errors, biases, sensitivity and confidentiality. 

 Level 3 represents a Data Resource of the dataset. A Resource is something that a user can utilise to work with the dataset. A Resource can be a downloadable file, or a search portal in which the dataset can be browsed, or an endpoint for querying the data, etc. The entire level can be repeated. Each repetition represents a Resource within the dataset. Different Resources may be used, for example, to describe different files within the data. They can also be used to describe different variants that are available, for example an open version and a restricted version, if these differ significantly in how they are created or what they contain. However, you can combine multiple files or multiple versions within the same Resource. When deciding how many Resources to use to represent the dataset, consider how much of the information in Level 3 the Resources have in common, how easy it is to describe each Resource clearly and how easy it is for the user to understand what is available to them. 

  ## 3.1 Data Resource Description
  This describes some basic information about the Resource, such as name, description, format and size. Depending on the dataset, some information may be a repetition of information from Level 2, or it may be different. For example, if a dataset is split into different language files, then the Languages in Level 2 may be 'German, Dutch and French', while the language of the Resource representing the German section will just be 'German'. However, if the all of the Resources were a mix of the three languages then both Level 2 and all Resources would have 'German, Dutch and French' for their Languages. 

  * Name - the name of the Resource. This should distinguish it from other Resources. For example, 'Wartime Radio - audio files', and 'Wartime Radio - transcripts'.
  * Description - a description of the particular Resource. This should describe what is in the Resource, if this is different to the whole dataset. It often contains information on how the Resource was created. For example, if a dataset contains a Resource that is a set of persons detected in letters, then the Resource Description could explain how Named Entity Recognition was used to detect the persons. The description also often contains information on how to use the Resource. 
  * Path - the URL where the Resource can be found
  * Format - one or more file extensions that are in the Resource, e.g. csv, json, xls
  * Size - the size of the Resource (if it is downloadable)
  * Date - the date on which the Resource was created
  * Language(s) - the language(s) used in the Resource. Note: this may be more specific than the languages for the whole dataset.
  * Encoding - the character encoding, if the Resource is a data file
  * Data Subjects
    * Subject(s) - A selection of the subjects of the data from a vocabulary
    * Other Data Subject(s) - if the vocabulary does not contain appropriate subjects, then they can be filled in here
* Data modality
    * Modality - one or more data modality (e.g. image, text) selected from a vocabulary. The option 'Multimodal' means that the dataset is inherently a combination of multiple types together. For example if a dataset contains a video with in-screen subtitles, then that video is a combination of the modes of video and text, which can't be separated, and is therefore multimodal. For a dataset with videos and separate subtitle files, you can select both 'video data' and 'text data' as the modalities.
    * Other Modalitie(s) - if the vocabulary does not contain appropriate modalities, then they can be filled in here
* Descriptive statistics - this can be used to describe the Resource with statistics, e.g. how many persons, how many different countries, the distribution over time. It can also be used to link to a page where statistics are published.

## 3.2 Data Fields
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
* Description of the data field - a description of what the field represents, including any specific details about the data format or structure. If the field involves complex data like span indices, explain whether these indices are based on characters or words, and whether they are contiguous (continuous without breaks) or not. 
* Sensitivity - this indicates whether the data stored in this specific field is sensitive. Sensitive data might include personal information that could be harmful if exposed, such as social security numbers, personal addresses, or health information. This helps users to distinguish between sensitive and non-sensitive fields. More detailed information about the sensitivity at the dataset level can be included in section 3.7.
* Notable Features - any important or unique attributes of the field that might be relevant for users or systems interacting with the data
* Used Vocabularies - if a field uses a taxonomy or vocabulary then this can be described here
  * Vocabulary - a summary of the linked open data scheme, controlled vocabulary, ontology or taxonomy used during the establishment of the dataset
  * Vocabulary link - a link to the taxonomy or relevant documentation that describes it

## 3.3 Data Point Examples
### Typical Example

Here you can include an example of how the data typically appears in the Resource. You can copy and paste text or numerical data, or a row from tabular data, or you can describe the example (e.g. a recording of the 8pm broadcast of the daily news, recorded on 15th November 2004). If data points can be linked to, include the link so that users can examine it themselves.

* Description - a description of a typical example of a data point
* Link - a link to the data point

### Atypical Example

Here you can include an example of known oddities or outliers in the Resource.

* Description - a description of an atypical example of a data point
* Link - a link to the data point, if possible

## 3.4 Errors, Noise and Redundancies
Here any errors, noise, gaps or redundancies in the Resource can be described. For example, if all data from a particular country is missing for the second half of the temporal scope, or if some dates are uncertain. Do not include biases in the data here, these should be mentioned in Section 3.7.

## 3.5 External Resources
The dataset may link to external resources. For example, to pages on Wikidata describing persons, or to images stored in an image bank, or to documents in a digital archive. 

* Resources - this states if the dataset contains links to external resources, yes or no
* External Resources Description - this specifies what external resources are linked to, and how and why the dataset relies on them. 
* External Resources Links - this provides links to the external resources (at the level of the source, not an individual resource. For example, Wikidata, not the individual persons in Wikidata)

## 3.6 Annotation and Labelling
The original data in the dataset may have been enriched by annotating or labelling it with extra information. This may be done by humans or machines. For example, experts may have labelled letters with the persons mentioned in the letters, or an algorithm may have detected persons in the letters. These annotations can be described in this section.

### Annotation Characteristics
This section can be repeated for each type of annotation performed.

* Annotation workforce type - the type of humans, or machines, that performed the annotation, from a vocabulary
* Others - if the workforce type was not in the vocabulary, it can be filled in here
* Description - a description of the annotation that was performed
* Total Annotations - the total number of annotations
* Total Tokens - the total number of tokens that were used in the annotations
* Avg Tokens Annotations - the average number of tokens per annotation
* Metric - 

## 3.7 Social Impact, Sensitivity and Biases

### Safety Consideration
Here you can answer, with yes or no, the question 'Does the resource contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety?'. If the answer is yes, then you can specify how and why. For example, a dataset from colonial times may contain offensive language and stereotypes.

### Confidentiality
Here you can answer, with yes or no, the question 'Is the dataset confidential?'. If the answer is yes, then you can specify what measures were taken to avoid disclosure of personal information. 

### Biases

Known Biases in the Resource - Identify any known biases present in this dataset, such as stereotyping, underrepresentation, overrepresentation, or misrepresentation of certain social groups. Briefly describe the nature and, if possible, the extent of these biases to help users make informed decisions and mitigate potential harms.

Steps taken to Mitigate/Reduce Biases - Describe the steps taken to reduce or mitigate biases in the dataset.

### Sensitive Attributes

* Sensitive Human Attributes - Specify if the dataset contain data that might be considered sensitive in any way (e.g., data that reveals race, sexual orientation, age, ethnicity, disability status, political orientation, religious beliefs, union memberships; location; financial or health data; biometric or genetic data; criminal history). You can choose from a list of sensitive attributes or choose 'Others'
* Specify - If you selected 'Others', then you can specify them further here. 
* Unintentionally Collected Attributes - any human attributes that were not explicitly collected as a part of the dataset creation process but were accidentally/unavoidably included or can be inferred using additional methods

### Ethical Review

* Review - an indication, yes or no, if an ethical review was carried out
* Description - if an ethical review was carried out, enter a brief description of the ethical review (e.g. who carried it out and when, any reference number or other identifier)
* Outcomes - the outcomes of the review and how they influenced the dataset creation
* Link - link to any further information about the ethical review
* Ethical Review Contact - a person who may be contacted in relation to questions on ethical review
  * Name - full name of the person
  * Affiliation - organisation that the person works for
  * Email - their email address

## 3.8 Data Provenance
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


## 3.9 Digitisation
Describe the pipeline used for digitisation. If applicable, describe in what way digitisation presents another layer of selection of the whole of a collection available in a cultural heritage institution; state if this is not the case. If applicable, provide selection criteria and metrics that demonstrate how this additional layer of selection has influenced the transformation of the original collection or dataset into the current dataset. For example "thin letters were scanned using an automatic feed, while thicker letters were manually scanned. Letters with a large format did not fit into the scanner, so they are not included in this dataset."

## 3.10 Feedback and Elaboration
Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful 

# 4 Uses
This level describes the uses for which the dataset was designed, what it has been used for and what are allowable uses of the dataset. It also lists unsuitable uses.

* Purposes - one or more purposes of the dataset can be selected from a vocabulary. If no relevant purpose is included, you can select 'Other'
* Other - if other was selected then the purpose can be specified here
* Domain(s) of Application - the domains for which the dataset was designed can be specified using a vocabulary
* Motivating Factor(s) and Problem space(s) - What motivated the creation of this dataset? Did the creators already have a specific use in mind? Provide a description of the specific problem space that this dataset intends to address

## 4.1 Uses
* Dataset Use - one or more types of use of the dataset can be selected from a vocabulary.
* Explain for special cases chosen above - If a special use has been selected, then this can be explained here.
* Links to Related Items
  * Publications - URL(s) or descriptions of publication(s) introducing or describing the dataset
  * Related datasets - dataset(s) that use this dataset
  * Model trained by dataset - model(s) that were trained on this dataset
* Suitable use cases - one or more cases for which the dataset is suitable. These can be existing or proposed uses. Links can be included where appropriate, for example to a web application that uses the dataset. Additional notes can be filled in 
* Unsuitable use cases - one or more cases for which the dataset is unsuitable. This may be due to legal or ethical reasons, to quality or bias issues, choices made by the dataset owner etc. Additional notes can be filled in 

## 4.2 Use with Other Data
Datasets that are safe to use on their own may not be suitable to use with other data. For example, combining sets of data about anonymised persons may allow the persons to be identified.

It is often difficult to judge the safety of use with other data. If in doubt, select the 'Unknown' option. You can then leave the rest of the section empty.

* Safety Level - select a level from a vocabulary. If no level is appropriate, choose 'Other'
* Other - if 'Other' was chosen then this can be specified
*  Known safe dataset(s) or data type(s) - a list of the known datasets (provide link) or data types and corresponding transformations that are safe to join or aggregate this dataset with
*  Known unsafe dataset(s) or data type(s) - a list of the known datasets (provide link) or data types and corresponding transformations that are unsafe to join or aggregate this dataset with

## 4.3 Use in ML or AI systems
Datasets may or may not be suitable for use in ML or AI systems. This may be due to legal or ethical reasons, to quality or bias issues, choices made by the dataset owner etc. In this section you can indicate if usage for ML/AI is allowed and offer guidelines for good usage.

It is often difficult to judge the suitability of data for ML/AI. If in doubt, select the 'Unknown' option. You can then leave the rest of the section empty.

* Dataset Uses - select a level from a vocabulary. If no use is appropriate, choose 'Other'
* Other dataset use - if 'Other' was chosen then this can be specified
* Notable Feature(s) - any notable feature distributions or relationships between individual instances made explicit
* Known correlations -  any known correlations with the indicated features in this dataset
* Usage Guidelines - summary or link to usage guidelines or policies that users should be aware of in using this dataset for ML purposes
* Data splits - Provide a description of any recommended data splits (e.g., training, development/validation, testing), explaining the rationale behind them

## 4.4 Sampling
Datasets may or may not be suitable to be sampled. 

It is often difficult to judge the suitability of data for sampling. If in doubt, select the 'Unknown' option. You can then leave the rest of the section empty.

* Safety Level - select a level from a vocabulary. If no level is appropriate, choose 'Other'
* Other - if 'Other' was chosen then this can be specified
* Acceptable Sampling Methods - all applicable methods to sample this dataset, chosen from a vocabulary. If a method is missing from the vocabulary, choose 'Other' 
* Other - if 'Other' was chosen for acceptable sampling methods then this can be specified here
* Best Practice(s) - advice on best practices for sampling can be entered here. 
* Risk(s) and Mitigation(s)- known or residual risks associated with sampling methods when applied to the dataset and how they can be mitigated.

## 4.5 Feedback and Elaboration
Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful

# Level 5 Human Perspective
All datasets are influenced by the choices of the human beings who create them, whether this is by the selection of the data, the construction of a data model, the choice of a software algorithm etc. These choices are often made against a background of a particular research question, a particular use, the experience and interests of the creators, and their social, ethnic, cultural and gender backgrounds. 

In dataset documentation, embracing this human perspective is vital for various reasons. Firstly, it illuminates the biases and assumptions that may influence data collection and analysis. Secondly, it provides transparency, allowing users to understand the context in which the dataset was created and to consider how this context may affect their use of the data. Thirdly, it promotes inclusivity by recognising the diverse standpoints of dataset creators and subjects, encouraging a multiplicity of perspectives in data interpretation. 

The human perspective section is related to the bias section, but it has an important difference. Biases in Section 3 are already detected and known in the dataset. The choices made due to a human perspective may result in a dataset that is well suited to the creator's context but that has a serious bias when approached from a different domain and perspective. For example, think of an AI trained on product reviews in America by marketeers that is then applied to sentiment detection in television programmes in the Netherlands by academic researchers. Knowledge of the human perspective can help in identifying the match with different domains and uses, and in asking critical questions about the suitability of a dataset for a particular purpose. 

The backgrounds of contributors can also affect the dataset. For example, if non-Dutch contributors transcribe Dutch place names, then there may be more errors than if native Dutch contributors performed the transcription. At the same time, a non-Dutch historical expert may be more successful in the transcription of historical documents than a Dutch layperson.

## 5.1 Human Annotators
Human annotators - people who enriched the original data with extra information such as labels - have a large influence on the results of the annotation process. For this reason, it is important to know information about the annotators that may have influenced the results. For example, native Dutch speakers will have different results when annotating documents with Dutch placenames than native English speakers. Information about the annotation instructions is also important here, as the instructions can help in standardising responses over annotators, reducing their own influence on the results. 

This section focuses on **who** created the annotations, not on **what** is in the annotations. A description of what was annotated can be entered in Section 3.6.

For creators and contributors, you can fill in relevant information in Section 5.2.

* Annotator description - This contains a short description of each annotator group. E.g. 'Dutch History Experts', 'Crowdsourced laypersons'.
* Annotation Type - this is filled in for each different type of annotation performed. 
  * Task type - a summary of the task type. Include links if available. Ideally connect to some existing taxonomy: survey, video annotation, text annotation, image annotation, etc
  * Number of unique annotators
  * Average number of Annotations per Annotator
  * Expertise of annotators - for example, archival and historical knowledge and reading and understanding historical Dutch
  * Description of annotators
  * Compensation - how they annotators were compensated for their effort. Indicate here whether they were crowdsourced or not, and if not, what compensation they received. For example, 'compensated as per the Dutch CAO'.
  * Language distribution of annotators - what were the languages spoken by the annotators?
  * Num Language Distrib - how many annotators spoke each language?
  * Age distribution of annotators - what was the age range of the annotators?
  * Number of each age group - how many annotators were in each age group?
  * Geographical distribution of annotators - where the annotators reside. For example, 100% reside in the Netherlands.
  * Gender distribution of annotators - For example, 60% identify as women, 40% as men.
  * Socio-economic distribution of annotator. For example, 40% identify as lower middle class, 60% as middle class.
  * Summary of annotation instructions - what instructions the annotators were given in how to carry out the annotation task.  Include links, say to the annotation instructions, readme.
  * Annotation platform(s) - which platform(s) were used to create the annotations. Include links 
  * Additional Notes - Any other comments. For example: 'During the annotation process all annotators were trained to read and understand the original texts by the archival expert and were invited to compare the HTR texts with the scans of the original. This way of working proved instrumental in overcoming limitations of HTR quality'.

  ## 5.2 Creators and Contributors
  ### Description of potential positionality impact factors
  This section can include any aspects that could have impact on the work in terms of positionality of the creators and contributors, e.g. particular domain of expertise, gender, age, etc. As it can be hard to judge what may have an impact, one option is to give a short bio for each creator/contributor. Be careful of privacy aspects.

  ## 5.3 Feedback and Elaboration
  Please use this space to provide any feedback on this section and to share any other insights or information you think would be useful