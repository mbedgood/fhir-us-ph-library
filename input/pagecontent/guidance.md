### US Core

The US Public Health Profiles Library will be instituted in close conjunction with US Core and have an analogous process for implementation, moderation, review, and approval. The intent is to re-use US Core profiles wherever possible and only add profiles that are needed for common public health needs. The library will evolve over time and may be supported by an adjunct profiles registry that includes developing and informational profiles for public health use.

### Conformance

#### Conformance Verbs

The conformance verbs - **SHALL**, **SHOULD**, **MAY** - used in this guide are defined in [FHIR Conformance Rules].

#### US Public Health Profiles Library Conformance Artifacts

The [artifacts] page lists the US Public Health Profiles. Profile [StructureDefinitions] define the *minimum* elements, extensions, vocabularies and value sets which SHALL be present when using the profile.

The Profile elements consist of both *Mandatory* and *Must Support* elements.  *Mandatory* elements are elements with an minimum cardinality of 1 (min=1). The base [FHIR Must Support] guidance requires specifications to define exactly the support expected for profile elements labeled *Must Support*.  As many profiles in the US Public Health Library are based on US Core profiles and this library is dependent on and will be instituted in close conjunction to US Core, the [US Core Must Support Sections](http://hl7.org/fhir/us/core/STU4/conformance-expectations.html#presentation-of-must-support-and-mandatory-elements-in-the-formal-profile-views) illustrate how these elements are displayed and defines the rules for interpreting profile elements and subelements labeled *Mandatory* and *Must Support* for requesters and responders.

### Principles and Criteria of Library Inclusion and Use

#### Profile Reuse and Determination Principles

1. New profiles, that are not based on US Core, will only be included in the US Public Health Profiles Library when there is a clear public health need. As things now stand, all non-US Core profiles are approved by the Cross-Group Projects and the US Realm Steering Committee
2. Similarly, new public health FHIR US Realm implementation guides will not create new profiles that are not based on either the US Public Health Library or US Core without the approval of the Public Health Working Group and notification of US Realm Steering Committee
3. The Public Health Work Group, the FHIR Management Group, and FHIR QA Tooling (TBD) will enforce the principles above and criteria below

#### Profile Inclusion Criteria 

A Proposed Content or Architecture Profile Must Meet One or More of the Following Criteria for Inclusion in US Public Health Library

1. The profile concept is operational in three or more public health conditions / use cases
2. The profile concept is captured in operational use in an existing EHR or public health system
3. When there is not operational implementation experience (as above), a new profile can be included if it has been used in at least two Connectathons and three or more public health conditions / use cases require it
4. The profile supports a nationwide solution based on proposed US regulations or multiple states’ laws, policies, rulemaking, or well-established practices. 

A variance process modeled after the [US Core Variance process](https://confluence.hl7.org/display/CGP/US+Core+Variance+Request+Process) will be instituted. The process will strive for the automated identification of non-USCore, non-US Public Health Profiles Library profiles and their processing with the Public Health Work Group and US Realm.

#### Related Responsibilities of the Public Health Working Group

* Determine initial and subsequent population of profiles in the US Public Health Profiles Library
* Review and approve variant profiles
* Be the steward for the library content