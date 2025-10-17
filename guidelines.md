  # Guidelines
  There are no hard and fast rules for applying data-envelopes. How you structure and fill in information about your datasets will depend to a large extent on the type of data you have and the     sort of users. Keep in mind that the aim of a data-envelope is to inform your user so that they can correctly use the dataset. The data-envelop should present the necessary information as        clearly and succinctly as possible.
  Below are some guidelines that can help you when making decisions. The Data-Envelope format is in development and its use in practice is being thoroughly tested. As a result, these guidelines    will evolve.
  
  ## Why do I create a data-envelope?
  You create a data-envelope when it is important that information about the dataset is available in a structured way. Possible scenarios are:

  * The dataset is published for reuse
  * The dataset will be reused internally
  * The dataset is used for a software application and you want to give application users transparency about how the application works
  * Information about the dataset is scattered over many sources and you want to have it in one place
  * Information about the dataset is largely in the heads of human experts who may leave your organisation
  * You want to make it easier to produce lots of different formats of the description
  * You want to include the dataset in a centralised search portal

  Creating data-envelopes takes time and effort. For this reason, it is sensible to prioritise those datasets for which a data-envelope has the most impact.
  
  ## For what do I create a data-envelope?
  Data-Envelopes are intended to describe datasets. But what is a dataset? This is a very hard question to answer. A practical approach is to think about your users. What is a unit of data that is useful to them? This could be a huge database or a single file listing persons.

  ## My data is not available online. Do I still need a data-envelope?
  It can still be useful to use a data-envelope to describe datasets even if they are not available online. This can have the following benefits:

  * People know that the dataset exists and how to request offline access
  * People know that the dataset exists and for what reasons it cannot be used (e.g confidentiality)
  * People know that the dataset exists but that something is required to be done before it is available online (e.g. digitisation)
  * People get in touch with you to show their interest in the dataset - this can be very valuable when lobbying for funding
  
  ## When do I create a data-envelope?
  Ideally, you start to create a data-envelope as soon as you start to think about creating a dataset. That way information is recorded as soon as it is available, and is not forgotten or lost. However, many datasets already exist. Actions taken on the dataset (such as digitisation, publication, use in a project, inclusion in a data catalogue etc.) can be a trigger to create a data-envelope. When creating data-envelopes retrospectively, you can set up a schedule to gradually create the data-envelopes in order of priority of the datasets.

  ## Who creates a data-envelope?
  The experts who know about the dataset. This can be one person but frequently it is multiple persons. One may know how it was curated, another how it was digitised, another what the legal situation is. It is important to also include someone - preferably as the final editor - who has an affinity with the potential users of the dataset, as they can put the information in a form that is most useful to the user.
  
  ## What is a Resource for? (Level 3 Data)
  A dataset is a conceptual thing. You can describe a dataset that doesn't exist yet, or that doesn't exist anymore. A Resource is something that exists and that a user can use to work with the actual data. For example a downloadable file, a portal via which the user can explore the dataset, an API or endpoint that provides programmatic access.

  ## Do I need a Resource at all?
  Yes! The Resource contains essential information about errors, sensitivity and bias of the dataset. However, if your data is simple then there are many fields in Level 3 that you can leave empty, such as the data fields and data point examples. 
  
  ## When do I use multiple Resources?
  Use multiple resources when there are different ways that the user can work with the data and they differ substantially. This depends on the type of your data and on what your users want to do with it/are allowed to do with it. Your main aim is to give clear information to the user. If it is clearer to split things into multiple Resources then do so, if it is clearer to describe them all together in one Resource, then do that.

  One simple rule of thumb: If you have one Resource and your Resource description is getting very long or confusing, and you are putting lots of multiple values in the fields (e.g. many different formats, many different languages), then you should think about using multiple Resources. If you have multiple Resources and you are copy-pasting most of the information between them or referring frequently to other Resources, then consider combining them in one Resource. Problems with structuring the data in Resources may be a hint that your data is not suitably structured for users. For example, if your data is split into multiple files with separate download links but your separate Resources keep referring to each other, then it may be easier for the user if you combine the data into one zip file and describe it in one Resource. 

  Cases in which you might use a single resource:
  * You have data available as PDF or JPEG. It is otherwise created in an identical way
  * Your dataset is divided into sections, but they are all downloaded in one go in a zip file.
  * Your data is split into several different files but all are required to be able to work with the data properly
  * You have data that is accessible in an open access portal and a restricted access portal. The restricted access portal offers access to a few additional metadata fields. Otherwise the underlying data and how it was created is the same
  * Your dataset contains videos described with metadata. You can search for videos and when you click on a video you can read the metadata. The metadata and the videos cannot be downloaded separately from each other.
  * The dataset is only available via a portal, which contains its own detailed instructions about how to use the different parts of the data within the portal.


  Cases in which you might use multiple resources:
  * You have data available as PDF or image. The PDFs are only available for a subset of the data due to technical issues and the images were subjected to many cleaning steps before the PDF was created
  * You have data available in three different languages and users are mainly only interested in downloading one language. Or the data is split into persons, organisations and locations, and users are mainly interested in one of these.
  * Different parts of the data were created in very different ways, and as a result have different biases, errors etc.
  * Part of the data is sensitive and part is not
  * You have data that is partly available as open access and partly available as restricted access. For example a set of videos and metadata where the metadata is open access and downloadable, while the videos are restricted access and can only be viewed in a portal.
  * Your dataset is divided into files, each of which has its own download link.
  * Your dataset contains videos described with metadata. The metadata for the entire dataset can be downloaded separately.
  * Your dataset has different parts that allow users to perform different tasks. For example, a baptism register dataset could have a search index of record metadata that can be used for search or for metadata analysis, and a website that allows the individual baptism records to be browsed and downloaded.
  * Your dataset is available in two very different formats. For example, a dataset that makes metadata available both in its original custom format and transformed to a Linked Data format in a common vocabulary.
  * The dataset aggregates distinctly different sources. For example, a dataset of marriage registers that offers both church and civil registers.
    
  ## When do I use multiple data-envelopes?
  The focus of data-envelopes is on findable and reusable datasets. A data-envelope should be able to clearly describe the dataset, so that users can find it and understand it. The useful granularity for data-envelopes depends on the type of your data and on what your users want to do with it/are allowed to do with it. Your main aim is to give clear information to the user.

  One simple rule of thumb: If your data-envelope contains very complicated and length descriptions and very disparate values for characteristics such as the temporal and geographical coverage, then you should consider splitting it into multiple data-envelopes. If you have multiple data-envelopes and you are copy-pasting most of the information between them, then consider combining them in one data-envelope.

  Cases in which you might use a single data-envelope:
  * The dataset is coherent and stand-alone, all parts of it are needed together
  * Intermediate forms of the dataset are not available to (most) users but affect the form that is available. E.g. a collection of letters exists as the original letters themselves in a depot, their digital scans in an eDepot, and via an online portal. Only the portal is widely accessible. In that case, it may be useful to describe all three forms in one data-envelope, as users cannot directly access the original letters or digital scans, but the information about the letters and scans is important to their use of the data in the portal

  Cases in which you might use multiple data-envelopes:
  * Intermediate forms of the dataset are available and usable. E.g. a collection of letters is available as digital scans which can be used for training AI models, and in a portal for use by researchers.
  * Different parts of the data have very different characteristics and histories. For example it would be logical to separate baptism records from minutes of church meetings.
  * Subsets of the data are usable in their own right and have different characteristics and histories. For example, a collection of public broadcaster TV is useful, but it can also be valuable to describe the subset of news broadcasts separately, as much more specific information is available and it is a more coherent set that may be used for specific purposes.

 Note that data-envelopes can refer to data-envelopes of datasets that are used in the current dataset. See the section on nested data-envelopes.
 
  ## What are nested data-envelopes?
  Section 3.8 allows you to refer to existing datasets that were used in the creation of the dataset being described. For example, for a dataset of OCR texts of letters may have used the dataset of scans of those letters. There is a field in Section 3.8 that allows you to refer to the data-envelope for the dataset used. This is referred to as 'nesting'. For example, a dataset of TV news broadcasts could refer to the dataset of public broadcaster TV from which the news broadcasts were selected, and can reference its data-envelope.
  
  ## What is the difference between the Description in Level 2 and the Description in Level 3?
  Broadly, Level 2 describes the dataset as a concept. It is also the 'trailer' for the dataset, that helps users quickly decide if the dataset is relevant for them. Consequently, it should be as concise as possible. The description in Level 2 should include what is in the dataset, what topics it covers and why it is valuable. It may also briefly mention what means are available to use it (is it available to download, via a portal etc.) but details about this should be described in Level 3.
  
  Level 3 typically contains the more detailed information that assists researchers in correct, responsible use of the dataset via one or more Resources (downloadable files, portals etc). The description therefore dives into more detail than Level 2 and may be longer. It sketches how the Resource was created, how it is structured, and how the Resource in question can be used to work with the data. 

  If you have multiple Resources, then some of the information about how they were created may be the same. It is then more suited to the Dataset level, and can be included in Level 2 to avoid duplication in the Resources (which causes problems if the information needs to be updated/corrected).

  ## Do I have to put all the information about my dataset in the data-envelope?
  No! The data-envelope should be kept as concise as possible to make it easier for users to read it quickly. It must contain the key elements they need to assess whether the dataset is relevant and usable. It is not there to tell the whole story of a dataset, or as a detailed instruction manual. It is the central place for information about the dataset so it should refer to more detailed information that is available, for example publications, blogs, manuals. Think of the analogy of an information leaflet for medicine. This contains the key information that you need to know, and will alert you to potential problems so that you can then go and find out more information, for example talk to your GP.
  
