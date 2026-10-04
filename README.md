# oooyc.github.io

Source of https://oooyc.github.io, the homepage of Chao Ouyang.

- `index.html`: the whole page, plain HTML and CSS with no build step. GitHub Pages serves it from the root of `main`.
- `cv.pdf`: public copy of the CV without the phone number. It is built in the `phd-application` repo by
  `bash cv/build.sh` as `cv/output/chao_ouyang_cv_public.pdf`; copy it here after every CV change.
- `papers/`: paper PDFs linked from the page. Only versions that may be shared publicly go here
  (for CacheMAS, the de-anonymized camera-ready).
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

Content rules set by the candidate on 2026-10-04: publications carry no `[C.1]`/`[J.1]` style labels, and papers still
in submission (the ARR orchestrator paper) stay off this page. The CV keeps both.
