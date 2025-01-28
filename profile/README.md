# Leiden University Medical Center: PathAI organization
This organization aims to promote collaboration and sharing of code across all digital pathology projects conducted at the Leiden University Medical Center.
The overall goal is to standardize digital pathology workflows (QC, slide processing) and downstream tasks (MIL, segmentation, GNNs) which will make the 
process less error-prone, more resource-efficient and greatly accelerate the speed at which research projects can be conducted. The code inside the organization will be only
accessible by LUMC researchers invited by one of the moderators. Of course, some repositories are more suitable for public use, such as the [PathBench-MIL](https://github.com/Sbrussee/PathBench-MIL) framework.

Below are some of the goals of the repositories inside the organization, aimed to accelerate and standardize our digital pathology research:

### Modular digital pathology pipelines
The goal is to provide small-scale repositories which fulfill the needs of certain parts of the common PathAI workflow (e.g. QC, tissue detection, slide processing, normalization, cell segmentation).
Often these modules will take the form as forks from an existing repository, optionally modified for our use cases. We will also provide examples of an overall pipeline script which calls these modules.
All of these repositories will have their own environment to mitigate package conflicts and each of them should be callable as modules from an overall pipeline workflow. The overall goal of this approach
is to reduce the time required for these common steps and allow researchers to spend more time on their project-specifics and data engineering/management.

### Helpful scripts for data management
In our department, we are moving towards increasing data standardization and ensuring FAIR-standards for our digital pathology datasets + annotations. Scripts that aid in this effort (annotation file creation, data type conversion, metadata
creation, SlideScore interoperability), can be shared inside this organization to aid in the standardization process. 

### Annotation pipelines
In our effort for standardization, we provide some repositories or workflows which can be used for generating annotations (e.g. QuPath, ASAP, NuClick, etc.) and how these annotations can be effectively translated into useable data for
model training. 

### Visualization and clinical implementation
For eventual translation from our research efforts to clinical implementation and into clinical research projects, effective slide visualization with AI-overlays and integration with (soon-to-be-used) slide visualization software is required.
Scripts for this purpose can also be shared inside this organization.

### Collaboration and knowledge sharing
Last but not least, we want to emphasize how this organization can be used to aid (starting) digital pathology researchers in their efforts, by using the discussion functionality of the organization. This will help to retain knowledge of
more senior researchers and will help starting researchers accumulate digital pathology knowledge. We can also point to existing resources for this.


