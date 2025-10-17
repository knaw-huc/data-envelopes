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
  A dataset is a conceptual thing. You can describe a dataset that doesn't exist yet, or that doesn't exist anymore. A Resource is something that exists and that a user can use to work with the data. For example a downloadable copy of the dataset, a portal via which the user can explore the dataset, an API or endpoint that provides programmatic access.

  ## Do I need a Resource at all?
  Yes! The Resource contains essential information about errors, sensitivity and bias of the dataset. However, if your data is simple then there are many fields in Level 3 that you can leave empty, such as the data fields and data point examples.
  
  ## When do I use multiple Resources?
  Use multiple resources when there are different ways that the user can work with the data and they differ substantially. This depends on the type of your data and on what your users want to do with it/are allowed to do with it. Your main aim is to give clear information to the user. If it is clearer to split things into multiple Resources then do so, if it is clearer to describe them all together in one Resource, then do that.

  One simple rule of thumb: If you have one Resource and your Resource description is getting very long or confusing, and you are putting lots of multiple values in the fields (e.g. many different formats, many different languages), then you should think about using multiple Resources. If you have multiple Resources and you are copy-pasting most of the information between them, then consider combining them in one Resource.

  Cases in which you might use a single resource:
  * You have data available as PDF or JPEG. It is otherwise created in an identical way
  * Your dataset is divided into sections, but they are all downloaded in one go in a zip file.
  * Your data is split into several different files but all are required to be able to work with the data properly
  * You have data that is accessible in an open access portal and a restricted access portal. The restricted access portal offers access to a few additional metadata fields. Otherwise the underlying data and how it was created is the same
  * Your dataset contains videos described with metadata. You can search for videos and when you click on a video you can read the metadata. The metadata and the videos cannot be downloaded separately from each other.
  * The dataset is only available via a portal, which contains its own detailed instructions about how to use the different parts of the data within the portal.


  Cases in which you might use multiple resources:
  * You have data available as PDF or image. The PDFs are only available for a subset of the data due to technical issues and the images were subjected to many cleaning steps before the PDF was created
  * You have data available in three different languages and users are mainly only interested in downloading one language. 
  * You have data that is accessible in an open access portal and a restricted access portal. The open access portal has only a selection of the items available in the restricted access portal, and much less metadata. The data from the open access portal can be downloaded, the data in the restricted access portal may not be.
  * Your dataset is divided into sections, each of which has its own download link.
  * Your dataset is divided into sections that they are all downloaded in one go in a zip file, but each section has a lot of important information.
  * Your dataset contains videos described with metadata. The metadata for the entire dataset can be downloaded separately.
    
  ## When do I use multiple data-envelopes?

  ## What is the difference between the Description in Level 2 and the Description in Level 3?
  
