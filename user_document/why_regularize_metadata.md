# Why Regularize Metadata?

Consider these 4 possible entries for a location metadata field:
>Banda, Bongase, Africa <br/>
banda; bongase; africa <br/>
Banda;Bongase;Africa <br/>
Banda | Bongase | Africa <br/>

Many humans would look at these 4 lines and say that they convey the same information: there are 3 places—Banda, Bongase, and Africa.

A computer, however, doesn't read the same way. For our purposes, computers are picky and need to be told explicitly what to look for. This means that something as simple as capitalization, a typo, or a missing space after a semicolon can throw them off. To prevent this, metadata must be regularized and consistent so that machines can parse the information correctly.

For example, let's say that I, a programmer, want to write a script (a piece of code) that separates the different locations listed above so that I can filter search results by location (see [facet fields](facet_fields.md)). If I have the same 4 examples as above and someone searches for "Banda," Spotlight should return all of the results that include "Banda"—regardless of the other locations in the same field.

To do that, I have to isolate each place name individually. This would be *much* easier if I used *only* semicolons, commas, or pipes ( | ) to separate place names rather than used all three arbitrarily. Even something like a space after a semicolon can make the difference between a place called "Bongase" and one called " Bongase" (with a space). A computer would interpret "Bongase" and " Bongase" as two distinct places. Consequently, someone who wants to filter search results in "Bongase" might miss results labelled " Bongase."

There are simple rules and workarounds programmers can use to accomodate these little hiccups. But, in general, regularizing metadata is a good practice that makes that data more machine-readable and searchable.

<< Previous: [User Document](README.md)  |
[Table of Contents](../README.md#table-of-contents)  |
Next: [Facet Fields](facet-fields.md) >>
