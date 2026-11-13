# Institution validation

A page to classify by hand a sample of 500 research organisations. For each
institution the validator chooses an organisational type (university, research
institute, hospital, company, government agency, other) and an ownership
(public, private, hybrid).

Open `index.html`, or the published page, and work through the list. Progress is
saved in the browser, so the page can be closed and reopened on the same
computer. The button "Download results (CSV)" writes a file with one row per
institution; that file is what should be sent back by email. A downloaded file
can be loaded again with "Load a saved results file", for instance to continue
on another computer.

Files:

- `index.html`: the page, with no external dependencies
- `campione.js`: the sample (name, country, city, founding year, parent
  organisation, website, Wikipedia page and, when there is one, the
  introduction of the Wikipedia article)

The Wikipedia excerpts are reproduced under the CC BY-SA 4.0 licence; each one
is shown with a link to the article it comes from.
