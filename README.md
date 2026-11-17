# kos

Test repository for Khala organizations: the 24/7 master (a Khalinux box) pushes
the result of each approved task to a new branch `khala/work/<item>/e<epoch>`.
It never pushes to `main` and never force-pushes; people merge results by PR.
