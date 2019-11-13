# Vault to Spotlight

This manual describes the process of migrating data from Vault to Spotlight. Vault is our software repository for storing and preserving digital objects in our collections. [Spotlight](https://exhibits.library.uvic.ca/) is our digital exhibit platform, where we curate, highlight, and create a narrative for specific groups of objects.

For our purposes, we will focus on uploading and exporting data in batches via CSVs, although both Vault and Spotlight support uploading items individually.

If you're looking for Vault-specific information, see the [Vault Wiki](https://github.com/UVicLibrary/Vault/wiki). If you want to report a problem with Spotlight, please do so on the [Issues page](https://github.com/UVicLibrary/Spotlight2_custom/issues).

## Table of Contents

### Exporting from Vault and Preload
* [Goal: Working towards a Spotlight CSV]()
* [Mapping Document]()
* [Metadata Concerns]()
  * [Why You Should Regularize Metadata]()
  * [How Solr Indexes Metadata]()
  * [Facet Fields]()
  * [The Location Field and Google Maps Block]()
* [Visibility Settings in Vault]()

### Loading into Spotlight
* [Preserving Special Characters]()
* [Non-image Items]()
  * [Videos]()
  * [PDFs]()
* [Pre-flight Checklist]()

### Samples and Other Resources
* [Samples]()
* [Glossary](#glossary)

## Glossary

**CSV** stands for comma-separated values. CSVs (i.e. files ending in .csv) function like spreadsheets. Machines can read and manipulate CSVs much faster than you could in Excel for example, but this also means they are very picky about formatting, encoding, etc.
