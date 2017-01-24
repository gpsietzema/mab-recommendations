# [DRAFT] **Context-aware search**
_This recommendation is a DRAFT for consideration of the MODX Advisory Board._

**Editor:** Gauke Pieter Sietzema  
**First published draft:** To be determined

## Versions
- Oct 24, 2016 - Initial draft
- Nov 17, 2016 - Moved to Github and changed to Markdown + added “Future improvements”

## Goal of Recommendation
The goal of Context-aware search is a better internal search-engine for MODX through the uberbar. Multi-context installations are hard to search through in the current uberbar.

## Relevant Recommendations
n/a

## Recommendation
Make context-aware search in the uberbar better. Websites containing products and/or other resources which have the same name in every context/language are impossible to search right now (MODX current at time of writing: 2.5.1).

**Example**
	A website selling an "Apple iPad Air 2" will have the same page title in all contexts of a 3-context website with English/German/Dutch. There is no way to distinguish an English from a German version this way.

To fix this, we need to mention a recognisable key in the search results, which enables power users to find the correct resource. An example (which could use some design/better UX):

![Uberbar example](http://gawk.es/mab/images/context-aware-search-uberbar-20161107.png)

In the example above, the cultureKey context setting is used, but experience has learned us that the cultureKey is not always the best option. Therefore it should be customizable by a System Setting: "search_prefix", which in turn can contain settings like "[[+context_name]]" or your own Context Setting.

Another improvement for the search, which really helps power users: make the number of search results in the uberbar customizable through a System Setting, e.g. "search_resources_limit", "search_elements_limit", "search_users_limit", etc.

When the number of results exceed the limit above, a button should appear to the regular search result page, with a caption like "View all 3216 results". This also speeds up the uberbar search, because it sets a maximum to the number of results in the uberbar, which keeps the processing time low.

The regular search page could be simplified and extended to also search in elements. A possible solution would be adding a dropdown for choosing between Resources and Elements, and make the other form fields (longtitle, description etc.) dependant on this selection.

**Future improvements**
- Add extra filters: createdby:user-name, is:deleted, is:published
- 