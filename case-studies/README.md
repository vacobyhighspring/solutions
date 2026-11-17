# Case Study Library

Live page: https://vacobyhighspring.github.io/solutions/case-studies/

## Sharing one case study
- **Link:** open a case study and tap **Copy link**. Links look like `.../case-studies/#case-29`.
- **Standalone file:** tap **Download HTML**. You get a single file showing only that case study, which you can email or upload anywhere.

## What's in it
- 27 case studies from the original Northeast library.
- Technology case studies pulled from vaco.com and highspring.com, each with a "Source" line linking to the original page.

## Adding a case study
Send Claude the details (a PDF, a slide, a link or plain notes). It needs: title, client description (no client name unless it's already public), industry, services, challenge, solution, impact, and any numbers. Claude adds it to the `CASES` list in `index.html`, tests it and publishes it.

## Monthly refresh
A scheduled task checks the vaco.com and highspring.com case study libraries each month. Any new technology case study is added and published.
