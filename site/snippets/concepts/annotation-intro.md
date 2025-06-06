<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright Contributors to the ODPi Egeria project. -->

An *annotation* describes one or more related properties about a [digital resource](/concepts/digital-resource). Some annotations refer to the entire digital resource and others refer to a data field within the digital resource.   The annotations that describe a single data field are called *data field annotations*.

![Structure of survey reports](/frameworks/saf/survey-report-structure.svg)

The annotation types defined in the [Survey Action Framework (SAF)](/frameworks/saf/overview) are as follows:

* [Classification Annotation](/features/discovery-and-stewardship/overview/#classification-discovery) - Captures a recommendation of which classifications to attach to this asset.  It can be made at the asset or data field level.
* [Data Class Annotation](/features/discovery-and-stewardship/overview/#data-class-discovery) - Captures a recommendation of which data class this data field closely represents.
* [Resource Profile Annotation](/features/discovery-and-stewardship/overview/#resource-profiling) - Capture the characteristics of the data values stored in a specific data field in a data source.
* [Resource Profile Log Annotation](/features/discovery-and-stewardship/overview/#resource-profiling) - Capture the named of the log files where profile characteristics of the data values stored in a specific data field.  This is used when the profile results are too large to store in open metadata.
* [Resource Measurement Annotation](/features/discovery-and-stewardship/overview/#capturing-measurements) - collect arbitrary properties about a digital resource.
* [Resource Physical Status Annotation](/features/discovery-and-stewardship/overview/#capturing-measurements) - documents the physical characteristics of a data source asset.
* [Fingerprint Annotation](/features/discovery-and-stewardship/overview/#data-profiling) - Capture the characteristics of the data values stored in a specific data field or the whole digital resource and express it as a single value.
* [Request for Action Annotation](/features/discovery-and-stewardship/overview/#requesting-stewardship-action) - used to trigger governance and stewardship actions.
* [Relationship Advice Annotation](/features/discovery-and-stewardship/overview/#relationship-discovery) - document a recommended relationship that should be established with the asset.
* [Quality Annotation](/features/discovery-and-stewardship/overview/#calculating-quality-scores) - document calculated quality scores on different dimensions.
* [Schema Analysis Annotation](/features/discovery-and-stewardship/overview/#schema-extraction) - document the structure of the data (schema) inside the asset.
* [Semantic Annotation](/features/discovery-and-stewardship/overview/#semantic-discovery) - documents suggested meanings for this data based on the values and name of the field.

??? education "Open Metadata Types for Annotations"

    The open metadata types for annotations are describe in [Area 6](/types/6).

    The main entity type is called [Annotation](/types/6/0610-Annotations).  It is extended by *DataFieldAnnotation* to distinguish annotations that refer, primarily to a data field. Other more specialist annotations extend these two basic annotation types.

