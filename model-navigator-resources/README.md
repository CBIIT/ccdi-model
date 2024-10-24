### The Graph-Based Data Model

Many CRDC data models are graph-based, where nodes are functionally equivalent to the tables of a traditional relational database, and the properties within each node effectively represent what would be columns or fields in the corresponding table, with relationships stored at the level of individual records. This approach allows CRDC to support a large number of different study and data types including cross-sectional studies aimed at answering questions concerning basic cancer biology and the mechanisms by which malignancies develop, and longitudinal clinical trials assessing therapeutic interventions. Accordingly, although no single study is likely to propagate data into every node, let alone every property within every node, the data model has sufficient inherent flexibility to accommodate any given type of cancer study.

### Node Categories

All nodes are assigned to one of several categories, with each category representing a family of inter-related nodes which collectively define the various higher-level entities within the data model. For example, the **Case** category defines a small group of nodes which fully characterize participants (also referred to as cases or subjects) and the **Study** category contains the nodes which collectively define the various aspects of studies.  Not all data models will have the same collection of node categories.



<!-- PAGE BREAK -->

### Facet-Based Filtering

The facet-based filtering options presented within the left-hand sidebar of the Data Model Navigator allow users to filter the display of nodes based upon their designations for Category, Assignment and Class; based upon nodes containing required versus preferred versus optional properties; and based upon nodes containing properties that are displayed within the application’s user interface (UI). Using this array of filtering criteria, users can quickly partition the data model into smaller sets of nodes and thereby identify nodes of particular interest. Note that filtering criteria can be applied to both the Graph View and the Table View, and that filter selections are maintained when switching back and forth between viewing modes.

### Graph View

In Graph View mode, the Data Model Navigator provides users with an interactive, graphical rendering of the data model, which can be filtered as described above, in order to identify the nodes and therefore properties of most relevance or interest. Selecting a node of interest invokes a Properties Dialogue box which indicates the node’s Assignment and Class designations and quantifies the number of properties within the node that are Required, Preferred and Optional. A detailed tabular view of the node can be invoked by selecting the “Open Properties” option displayed within the Properties Dialogue box.

### Table View

In Table View mode, the Data Model Navigator displays detailed tabular views of each node, which fully-define the properties within them, inclusive of the applicable controlled vocabularies of acceptable terms for enumerated properties. The tabular views also clearly identify which properties are Required versus those that are Preferred or Optional; the acceptable data type for each property; which properties are displayed within the application’s UI; and the labels via which such properties are displayed. Note that many properties displayed within the UI are renamed with labels which are more intuitive than the property names themselves, and that some properties are displayed via more than one label. As described below, comprehensive documentation of the data model’s nodes and property requirements can be downloaded in PDF format via the Table View, alongside node-specific data loading templates into which data submitters can insert the relevant data values and thereby create loading-ready data files.

### Required, Preferred and Optional Properties

Each property is assigned one of three requirement levels - Required, Preferred, or Optional.

- **Required** properties are largely self-explanatory, i.e. data destined for a node which contains required properties must include values for all such properties, and values must be compliant with the acceptable values for properties which are both required and enumerated. Controlled vocabularies for such properties typically include terms such as “Not Applicable”, “Not Determined” and “Unknown” to accommodate situations where data values aren’t relevant or weren’t collected, either by design or otherwise.
- **Preferred** properties represent properties for which data values are not required, but which add significant insight and detail, have been populated to a significant degree thus far, and for which data is typically available when requested during study on-boarding.
- **Optional** properties are precisely that and null values are allowed.

<!-- PAGE BREAK -->

### Key Properties

Many nodes contain a single property visually identified as a Key Property by a **blue key icon** displayed next to the name of the appropriate property. In addition to several nodes that require one in support of data updates, all nodes which act as parents of child nodes will likewise have a single property within them identified as a Key Property. During data loading, **_child records_** are associated with their correct **_parents_** by virtue of data loading files which contain the appropriate values for the property identified as their parents’ Key Property. For example, files via which sample records are loaded will contain a column into which values of “Case ID” must be inserted, such that samples can be associated with the appropriate case from which they were derived, with “Case ID” being designated as the Key Property within the **Case** node. Key Properties are therefore functionally equivalent to foreign keys in traditional relational databases.

### PDF Documentation

Detailed documentation of the data model’s nodes and property requirements can be downloaded as PDF exports, either in the form of a comprehensive data dictionary inclusive of all nodes, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a node-by-node basis. Used alongside the corresponding data loading templates described below, these node-specific PDF exports function as user guides for data preparation and submission. See the associated [Data Submission Guidelines](https://datacommons.cancer.gov)

### Data Loading Templates

In support of data submission, data loading templates can be downloaded, either in the form of a zip file containing copies of all available templates, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a node-by-node basis. Templates include columns into which the data values required to associate child records with their parents can be inserted. Notably, each template will include a **mapping column** for each potential parent, but although \*all child records must be mapped to **at least one parent\***, submitters are not required to provide a mapping value for each and every potential parent, _only the_ **_most appropriate parent(s)_**. Guided by the corresponding node-specific PDF exports described above, data submitters can insert the relevant data values into these data loading templates, and thereby create loading-ready data files that can be handed off to the CRDC Data Team.

### Controlled Vocabularies

In the interests of data quality and consistency, CRDC data models makes extensive use of Common Data Elements (CDEs), enumerated properties and controlled vocabularies of acceptable terms. All such controlled vocabularies can be viewed via Table View mode, and value sets are included in full in the appropriate PDF exports. In addition to the acceptable terms available through teh Data Model Viewer, CDEs can be access via NCI's [caDSR website](https://cadsr.cancer.gov/onedata/Home.jsp) or [caDSR APIs](https://cadsrapi.cancer.gov/NCIAPI/1.0/index.html).  Furthermore, in support of data submitters pre-validating their templated data, all controlled vocabularies can be exported in machine readable JSON and TSV formats, either in the form of a zip file containing copies of controlled vocabularies for all enumerated properties, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a property-by-property basis. As more studies are added to the CRDC, many of these controlled vocabularies will continue to evolve, and will be updated by the CRDC Data Team during study on-boarding, in order to accommodate additional terms not yet encountered.