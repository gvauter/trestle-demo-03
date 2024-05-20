---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: pe-08
x-trestle-set-params:
  # You may set values for parameters in the assembled Profile by adding
  #
  # profile-values:
  #   - value 1
  #   - value 2
  #
  # below a section of values:
  # The values list refers to the values in the catalog, and the profile-values represent values
  # in SetParameters of the Profile.
  #
  pe-8_prm_1:
    profile-values:
    values:
  pe-8_prm_2:
    profile-values:
    values:
sort-id: pe-08
x-trestle-add-props:
  # Add or modify control properties here
  # Properties may be at the control or part level
  # Add control level properties like this:
  #   - name: ac1_new_prop
  #     value: new property value
  #
  # Add properties to a statement part like this, where "b." is the label of the target statement part
  #   - name: ac1_new_prop
  #     value: new property value
  #     smt-part: b.
  #
  - name: CORE
    value: 'true'
    ns: https://fedramp.gov/ns/oscal
    smt-part: pe-8
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: pe-8.a_obj.1
  - name: method
    value: EXAMINE
    smt-part: pe-8.a_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: pe-8.a_obj.2
  - name: method
    value: INTERVIEW
    smt-part: pe-8.a_obj.2
  - name: method
    value: TEST
    smt-part: pe-8.a_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: pe-8.b_obj.1
  - name: method
    value: EXAMINE
    smt-part: pe-8.b_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: pe-8.b_obj.2
  - name: method
    value: INTERVIEW
    smt-part: pe-8.b_obj.2
  - name: method
    value: TEST
    smt-part: pe-8.b_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: a.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: b.
---

# pe-8 - \[Physical and Environmental Protection\] Visitor Access Records

## Control Statement

The organization:

- \[a.\] Maintains visitor access records to the facility where the information system resides for {{ insert: param, pe-8_prm_1 }}; and

- \[b.\] Reviews visitor access records {{ insert: param, pe-8_prm_2 }}.

## Control Objective

Determine if the organization:

- \[PE-8(a)\]

  - \[PE-8(a)[1]\] defines the time period to maintain visitor access records to the facility where the information system resides;
  - \[PE-8(a)[2]\] maintains visitor access records to the facility where the information system resides for the organization-defined time period;

- \[PE-8(b)\]

  - \[PE-8(b)[1]\] defines the frequency to review visitor access records; and
  - \[PE-8(b)[2]\] reviews visitor access records with the organization-defined frequency.

## Control guidance

Visitor access records include, for example, names and organizations of persons visiting, visitor signatures, forms of identification, dates of access, entry and departure times, purposes of visits, and names and organizations of persons visited. Visitor access records are not required for publicly accessible areas.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The added parts in the profile for this control are below.  You may edit them and/or add new ones. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://ibm.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->