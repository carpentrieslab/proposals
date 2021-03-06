# Editor Guide

## Editor Checklist

### Accessibility

(Note to Editor: [the WAVE Web Accessibility Evaluation Tool][wave]
(also available as a browser extension) may be useful when completing these checks.)

- [ ] All figures are also described in image alternative text or elsewhere in the lesson body.
- [ ] The lesson uses appropriate heading levels:
    - [ ] h2 is used for sections within a page.
    - [ ] no “jumps” are present between heading levels e.g. h2->h4.
    - [ ] no  page contains more than one h1 element i.e. none of the source files include first-level headings.
- [ ] The contrast ratio of text in all figures is at least 4.5:1.

### Content

- [ ] The lesson teaches data and/or computational skills that could promote efficient, open, and reproducible research.
- [ ] All exercises have solutions.
- [ ] Opportunities for formative assessments are included and distributed throughout the lesson sufficiently to track learner progress. (We aim for at least one formative assessment every 10-15 minutes.)
- [ ] Any data sets used in the lesson are published under a permissive open license i.e. CC0 or equivalent.

### Design

- [ ] Learning objectives are defined for the lesson and every episode.
- [ ] The target audience of the lesson is identified specifically and in sufficient detail.

### Repository

The lesson repository includes:
    - [ ] a CC-BY or CC0 license.
    - [ ] a CODE_OF_CONDUCT.md file that links to The Carpentries Code of Conduct.
    - [ ] a list of lesson maintainers.
    - [ ] tabs to display Issues and Pull Requests for the project.

### Structure

- [ ] Estimated times are included in every episode for teaching and completing exercises.
- [ ] Episodes lengths are appropriate for the management of cognitive load throughout the lesson.

### Supporting information

The lesson includes:
    - [ ] a list of required prior skills and/or knowledge.
    - [ ] setup and installation instructions.
    - [ ] a glossary of key terms or links out to definitions in an external glossary e.g. [Glosario][glosario].

[glosario]: https://carpentries.github.io/glosario/
[wave]: https://wave.webaim.org/


## Issue Labels

Issue labels should be used by Editors to track the progress of each review.
There should be only one of these labels on each review issue:
when the Editor adds a new label,
they should remove the label for the preceding stage of the review process.
(These issue labels are taken from the set
[used by ROpenSci in their software package review system][ropensci-editor-guide].)

- `1/editor-checks`:
  the Editor is working through initial checks on the lesson,
  described in the [Editor checklist](#editor-checklist) below.
- `2/seeking-reviewers`:
  the points in [the Editor checklist](#editor-checklist) have been addressed satisfactorily,
  and the Editor is now looking for Reviewers for the lesson.
- `3/reviewer(s)-assigned`:
  the Editor has assigned at least one Reviewer to the lesson.
- `4/review(s)-in-awaiting-changes`:
  review(s) have been posted to the issue thread and are waiting to be addressed by
  the author(s)
- `5/awaiting-reviewer(s)-response`:
  author(s) has responded to and/or attempted to address to reviewer comments
  and the issue is waiting for reviewers to respond.
- `6/approved`:
  all Reviewer comments have been addressed satisfactorily
  and the lesson is approved for inclusion in The Carpentries Lab.

  [ropensci-editor-guide]: https://devguide.ropensci.org/editorguide.html
