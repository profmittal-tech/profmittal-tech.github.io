# profmittal-tech.github.io

Academic profile website of Prof. Prabhat Mittal, Satyawati College (Evening), University of Delhi.
Published at <https://profmittal-tech.github.io/>.

## Structure

```
index.html                      ← home: profile, invitations, highlights, contact
publications.html               ← selected books, articles and chapters
collaborate.html                ← invitation for research collaboration
csr-consultancy.html            ← CSR project consultancy + past projects
statistical-consultancy.html    ← statistical consultancy services
assets/css/style.css            ← shared styles (blue theme)
assets/img/prabhat-mittal.jpg   ← portrait (same photo as the call-for-chapters site)
assets/img/community-engagement-book-cover.jpg
assets/docs/Prabhat-Mittal-Complete-Profile.pdf ← full profile PDF (replace with your own upload)
.nojekyll
```

## Relationship with the call-for-book-chapters site

The Call for Book Chapters site lives in its own repository, `call-for-book-chapters`, and is
served at <https://profmittal-tech.github.io/call-for-book-chapters/>. This profile site only
links to it; nothing in that repository is changed by this one.

## Publishing

1. Create a public repository named exactly `profmittal-tech.github.io`.
2. Push these files to the `main` branch.
3. Settings → Pages → Source: *Deploy from a branch*, Branch `main`, folder `/ (root)`.
4. The site goes live at <https://profmittal-tech.github.io/>.

## Updating content

* Publications, projects and services are plain HTML lists — edit the relevant file directly.
* One PDF is offered for download: the **complete profile**. Replace
  `assets/docs/Prabhat-Mittal-Complete-Profile.pdf` with the LaTeX-built CV whenever it is updated; keep the
  filename and every link on the site keeps working. The Profile write-up on the home page serves as the short CV.
* Scopus metrics appear in the Profile section of `index.html` and at the top of `publications.html`. They are
  plain numbers in the HTML — search for `Scopus Research Metrics`, copy the current figures from
  <https://qtanalytics.in/scopus-search/author/12782839900> and update the "as on" date.
