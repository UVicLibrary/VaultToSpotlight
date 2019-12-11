# Vault to Spotlight

This manual describes the process of migrating data from Vault to Spotlight. [Vault](https://vault.library.uvic.ca) is our software repository for storing and preserving digital artifacts in our collections. [Spotlight](https://exhibits.library.uvic.ca/) is our digital exhibit platform, where we curate, highlight, and create a narrative for specific groups of objects.

For our purposes, we will focus on uploading and exporting data in batches via [CSVs](#csv), although both Vault and Spotlight support uploading items individually.

If you're looking for Vault-specific information, see the [Vault Wiki](https://github.com/UVicLibrary/Vault/wiki). If you want to report a problem with Spotlight, please do so on the [Issues page](https://github.com/UVicLibrary/Spotlight2_custom/issues).

## Table of Contents

### For General Users
* [Goal: Working Towards a Spotlight CSV]()
* [Metadata Concerns]()
  * [Why Regularize Metadata?]()
  * [How Solr Indexes Metadata]()
  * [Facet Fields]()
  * [The Coordinates Field and Google Maps Block]()
* [Mapping Document](mapping_document/README.md)
* [Visibility Settings]()
* [Pre-flight Checklist]()

### For Developers
* [Exporting from Vault]()
* [Visibility Settings (in Vault)]()
* [Preserving Special Characters]()
* [Web Storage]()
* Non-image Items]()
  * [Videos]()
  * [PDFs]()
* [Compound Objects]()

### Other Resources
* [Samples]()
* [Glossary](glossary/README.md#glossary)
* [Troubleshooting]()
