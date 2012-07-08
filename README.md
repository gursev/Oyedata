Oyedata
=======

Oyedata is a new tool to perform black-box OData security testing and help secure OData deployments. I wrote Oyedata from a penetration testing perspective and its the major features are summarized below:
 1. Intuitive GUI based tool written in C#.
 2. Ability to create attack templates from local and remote Service Documents and Service Metadata Documents.
 3. Support for XML and JSON data formats.
 4. Ability to export attack templates in JSON and XML formats that can be fed to custom Fuzzing code.
 5. Ability to engage the OData services for manual testing.
 6. Data generator for EDMSimpleType test data generation.
 7. Ability to generate “Read URIs” for Entities, Entity Properties and Entity Property Values.
 8. Ability to generate attack templates for Creation of new Entries, updating existing Entries, Service Operation invocation, Entry deletion etc…
 9. Ability to identify Keys, Nullable and Non-Nullable Properties and indicate the same in the attack templates.
 10. Web proxy, HTTP and HTTPS support and Error logging.

The files are:

* **Oyedata User Guide Oyedata for OData Assessments.pdf** - Oyedata user guide.
* **setup.exe** and **OyedataSetup.msi** - Oyedata setup files.

System Requirements:
* Microsoft .Net 4.0

For additional informaton please visit: http://gursevkalra.blogspot.com/2012/06/oyedata-for-odata-security-testing.html