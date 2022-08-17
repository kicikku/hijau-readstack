---
name: add-link-readstack
about: Add reading link for Hijau Docs Readstack
title: ''
labels: ''
assignees: ''

---

name: Reading link for Hijau Docs
description: Show off your Eleventy site on the Eleventy documentation
title: "[Hijau Reading Link] New reading!"
labels: hijau-reading-link
body:
  - type: markdown
    attributes:
      value: |
        Only the site URL is required. All other fields are optional.
  - type: input
    id: url
    attributes:
      label: Reading URL
      description: Reading link. _[parser:url]_
      placeholder: e.g. https://hijau.xyz/docs/how-redd-works
    validations:
      required: true
  - type: textarea
    id: summary
    attributes:
      label: "Description of the article"
      description: "The glimpse of the reading."
      placeholder: e.g. @zachleat, @pdehaan
    validations:
      required: false
  - type: input
    id: source
    attributes:
      label: Source reading
      description: "Optional: Source Media"
      placeholder: e.g. Bloomberg green
    validations:
      required: false
  - type: input
    id: label
    attributes:
      label: Article Label
      description: "Optional: Just glipmse"
      placeholder:emission
    validations:
      required: false
