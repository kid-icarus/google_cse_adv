Google CSE Advanced module
--------------------------

Created by Dynamite Heads http://www.dynamiteheads.com
Module development sponsored by Brightcove, Inc. - http://www.brightcove.com

Installation instructions
-------------------------

1) Download module from http://drupal.org/project/google_cse_adv
2) Extract to sites/all/modules or sites/[sitename]/modules
3) Enable module at admin/build/modules
4) Visit Admin -> Settings -> Google CSE Adv at admin/settings/google_cse_adv and set your CX key
5) Optionally visit Admin -> Settings -> Search settings and set a "Number of
   items to index per cron run" to 0 to disable core module indexing.

 
Notes
-----

Total number of search results fetched from Google CSE can be a bit
different on each request - for example during a paging.
See http://www.google.com/cse/docs/resultsxml.html and M result tag
which says: "The <M> tag identifies the estimated total number of results
for the search. Note: This estimate may not be accurate."
