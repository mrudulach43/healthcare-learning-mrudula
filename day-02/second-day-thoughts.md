# Day 2 – Understanding Healthcare Interoperability Standards

Today, I spent time understanding the history of HL7 and exploring different healthcare interoperability standards.

## What I Learned

- HL7 v2 is used to exchange healthcare messages such as patient admissions, discharges, and laboratory results.
- CDA defines the structure of clinical documents using XML.
- CCD provides a summary of a patient's clinical information.
- C-CDA provides standardized templates and rules for clinical documents.
- FHIR represents healthcare information as individual resources that can be accessed through APIs.

I also explored a sample C-CDA document to understand its structure, including headers, template IDs, clinical sections, and structured entries.

## My Understanding

C-CDA follows a document-based approach where patient information, including diagnoses, medications, allergies and laboratory results, is organized into a structured XML clinical document.

FHIR follows a resource-based approach where different types of clinical information are represented as individual resources that can be accessed through APIs.

Both standards can coexist within healthcare integration workflows. For example, a hospital can use C-CDA to exchange clinical summaries with external healthcare providers while using FHIR APIs to provide granular access to patient information for mobile applications and other integrated systems. An integration engine can also transform C-CDA clinical information into FHIR resources when required.
