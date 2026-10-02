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
assets/img/prabhat-mittal.png   ← portrait
assets/docs/Prabhat-Mittal-CV.pdf
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
* The CV PDF is a copy of the DU profile file; replace `assets/docs/Prabhat-Mittal-CV.pdf` when it is updated.
