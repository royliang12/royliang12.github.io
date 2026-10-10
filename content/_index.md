---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-10-09
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # To show a "Download CV" button: put your PDF at static/uploads/resume.pdf,
      # then remove the leading "# " from the 3 lines below.
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md # Options: xs, sm, md, lg (default), xl
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: research
    content:
      title: '📚 Research'
      subtitle: ''
      text: |-
        ### The Impact of ESG Ratings on Firms' Cost of Capital and Risk

        NSTC Undergraduate Student Research Project, Jul 2023 – Feb 2024 (project no. 112-2813-C-141-003-H), rated A. Advisor: Prof. Li-Chuan Chou.

        Using TEJ's TESG ratings and about 10,700 firm-year observations of non-financial firms listed on the TWSE and TPEx (2015–2021), I estimate fixed-effects panel regressions, selected by Hausman tests, of cost of debt, cost of equity, and risk (the three-year standard deviation of ROA) on ESG ratings and on rating upgrades and downgrades, with year and industry effects and separate estimates for electronics and non-electronics firms.

        Main findings: higher ESG ratings are not significantly associated with the cost of debt, but are significantly associated with a lower cost of equity and lower risk. In the short run, rating upgrades coincide with a higher cost of debt. The patterns are stronger among non-electronics firms.

        A related working paper, *ESG Ratings, Capital Costs, and Corporate Risk: Evidence from Taiwan*, co-authored with 第一作者 and 第二作者, is in preparation.
    design:
      columns: '1'
---
