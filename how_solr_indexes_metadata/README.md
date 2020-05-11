# How Solr Indexes Metadata

When you create or update an item in Spotlight, an indexing software called [Solr](../glossary/README.md#solr) is reponsible for changing and saving the metadata. When a user searches Spotlight for an item or items, Solr retrieves the metadata that accompanies them.

## What does metadata look like in Solr?

We communicate with Solr using [JSON](https://www.w3schools.com/whatis/whatis_json.asp). Here is an example item in Spotlight:


Here is the same record in the Solr administration dashboard:



<< Previous: [Why Regularize Metadata?](../why_regularize_metadata) |
[Table of Contents](../README.md#table-of-contents)  |
Next: [Facet Fields](../facet_fields) >>
