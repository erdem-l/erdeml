---
# Leave the homepage title empty to use the site title
title: "Erdem Lamazhapov"
date: 2022-10-24
description: "Erdem Lamazhapov, PhD Research Fellow at the Fridtjof Nansen Institute and University of Oslo. Research on China's Arctic policy, Sino-Russian relations and Arctic geopolitics: publications, commentary, talks and media."
type: landing

design:
  spacing: "4rem"

sections:
  # Photo, name, affiliation and links on the left; biography (from content/authors/admin/_index.md) on the right.
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf

  - block: collection
    id: selected
    content:
      title: Selected publications
      count: 0
      filters:
        folders:
          - publication
        featured_only: true
      archive:
        enable: true
        text: All publications
        link: publication/
    design:
      view: el-citation
---
