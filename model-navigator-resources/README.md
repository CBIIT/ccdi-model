### The Graph-Based Data Model

Many CRDC data models are graph-based, where nodes are functionally equivalent to the tables of a traditional relational database, and the properties within each node effectively represent what would be columns or fields in the corresponding table. A graph-based model also defines the relationships between individual records explicitly. This approach allows CRDC to support a large number of different study and data types including cross-sectional studies aimed at answering questions concerning basic cancer biology and the mechanisms by which malignancies develop, and longitudinal clinical trials assessing therapeutic interventions. Accordingly, although no single study is likely to propagate data into every node, let alone every property within every node, the data model has sufficient inherent flexibility to accommodate any given type of cancer study.

### Node Categories

All data nodes are assigned to one of several categories, with each category representing a family of inter-related nodes which collectively define the higher-level entities or node categories within the data model. For example, the **Participant** category defines a group of nodes which fully characterize participants (also referred to as cases or subjects) and the **Study** category contains the nodes which collectively define the various aspects of studies.  Not all data models will have the same collection of node categories.



<!-- PAGE BREAK -->

### Facet-Based Filtering

The facet-based filtering options presented within the left-hand sidebar of the Data Model Navigator allow users to filter the display of node types based upon their designations for Category. Users can partition the data model into smaller sets of node categories and thereby identify nodes of particular interest. Note that filtering criteria can be applied to both the Graph View and the Table View, and that filter selections are maintained when switching back and forth between viewing modes.

### Graph View

In Graph View mode, the Data Model Navigator provides users with an interactive, graphical rendering of the data model in order to identify the node categories and  properties of most relevance or interest. Selecting a node category of interest invokes a Properties Dialogue box which indicates the node category’s properties that are required and optional. A detailed tabular view of the node category can be invoked by selecting the “Open Properties” option displayed within the Properties Dialogue box.

### Table View

In Table View mode, the Data Model Navigator displays a detailed tabular view of each node category and the properties within them, inclusive of the controlled vocabularies of acceptable terms for enumerated properties. The tabular views also clearly identify which properties are required versus those that are optional; the acceptable data type for each property; which properties are displayed within the application’s UI; and the labels via which such properties are displayed. Note that many properties displayed within the UI are renamed with labels which are more intuitive than the property names themselves, and that some properties are displayed via more than one label. As described below, comprehensive documentation of the data model’s node categories, property and relationship requirements can be downloaded in a CCDI metadata template.

### Required and Optional Properties

- **Required** properties are data destined for a node which contains properties that must include values for all such properties, and the values must be compliant with the acceptable values for properties which are both required and enumerated. Controlled vocabularies for such properties typically include terms such as “Not Applicable”, “Not Determined” and “Unknown” to accommodate situations where data values aren’t relevant or weren’t collected, either by design or otherwise. Required numeric properties where information is unknown or missing can be completed with the reserved value -999.
- **Optional** properties are precisely that and null values are allowed.

<!-- PAGE BREAK -->

### Key Properties

Many node categories contain a single property visually identified as a Key Property by a **blue key icon** displayed next to the name of the appropriate property. In addition to several nodes that require one in support of data updates, all nodes which act as parents of child nodes will likewise have a single property within them identified as a Key Property. During data loading, **_child records_** are associated with their correct **_parents_** by virtue of data loading files which contain the appropriate values for the property identified as their parents’ Key property. For example, the sample node category tab in the workbook by which sample records are described contains a column into which values of “Participant ID” must be inserted, such that samples can be associated with the appropriate participant from which they were derived, with “Participant ID” being designated as the Key property within the **Participant** node. Key properties are functionally equivalent to foreign keys in relational databases.

### Metadata Template

In support of explaining data submission, the CCDI metadata template can be downloaded. 
The template has tabs for each of the node categories in the CCDI model. Not all tabs must be completed for a data submission. Please contact the CCDI curators for assistance.  In each tab, the value in each row of the first column is reserved to name the node-category.  The tabs include a column for the Key property of a node category. There is one or more columns to link a child data element to their parent. If more than one column is provided, only one of the columns should be used. (For example, if a file is linked to a sample, only the sample ID should be completed and not the participant ID). The required and optional properties to describe a data record should be completed. For columns with enumerated values, a pick list is available by clicking in the first row below the header row. The full set of model properties are defined in the Dictionary tab.  The enumerated values for properties with controlled vocabulary are described in the Terms and Value Sets tab. 


### Controlled Vocabularies

In the interests of data quality, interoperability and consistency, NCI CRDC data models make extensive use of NCI Common Data Elements (CDEs) and their Permissible Values of acceptable terms. All such controlled vocabularies can be viewed via the Terms and Value Sets tab and Table View mode. In addition to the acceptable terms available through the Data Model Viewer, CDEs can be access via NCI's [caDSR website](https://cadsr.cancer.gov/onedata/Home.jsp) or [caDSR APIs](https://cadsrapi.cancer.gov/NCIAPI/1.0/index.html).  Furthermore, in support of data submitters pre-validating their templated data, all controlled vocabularies can be exported in machine readable JSON and TSV formats, either in the form of a zip file containing copies of controlled vocabularies for all enumerated properties, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a property-by-property basis. As more studies are added to the CRDC, many of these controlled vocabularies will continue to evolve, and will be updated by the CRDC Data Team during study on-boarding, in order to accommodate additional terms not yet encountered.


### PDF Documentation

Detailed documentation of the data model’s nodes and property requirements can be downloaded as PDF exports, either in the form of a comprehensive data dictionary inclusive of all nodes, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a node-by-node basis. Used alongside the corresponding data loading templates described below, these node-specific PDF exports function as user guides for data preparation and submission. See the associated [Data Submission Guidelines](https://datacommons.cancer.gov)