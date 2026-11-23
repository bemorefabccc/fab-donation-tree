# FAB Donation Tree

The live FAB Donation Tree for Bemorefab Children's Cancer Charity (registered charity 1209136).

- `index.html` is the whole tree page. Netlify shows it, and the Bemorefab website shows it on the homepage and the FAB Donation Tree page.
- When a business buys a bauble, Claude adds it to the master copy in the "Donation Tree / Tree kit (for Claude)" folder, runs `make_site.py`, and replaces `index.html` here. Netlify updates the tree within a minute or so, and the website shows the new tree by itself.
- Please don't edit `index.html` by hand.
