---
title: Latest News
date: "2026-01-01"
lastmod: "2026-02-15"
type: landing

sitemap:
  priority: 0.6
  changefreq: weekly

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="news-hero-content">
          <div class="news-hero-label">Stay Updated</div>
          <h1 class="news-hero-title">
            Latest <em>News</em>
          </h1>
          <div class="news-hero-divider"></div>
          <p class="news-hero-desc">
            Announcements, publications, conference presentations, and updates from the Electric & Acoustic Hearing Lab.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "80px", "20px"]
      css_class: "news-page news-hero"

  # -----------------------------------------------------------------------------
  # 2. NEWS LIST
  # -----------------------------------------------------------------------------
  - block: collection
    content:
      title: ""
      subtitle: ""
      text: ""
      filters:
        folders:
          - post
        featured_only: false
      archive:
        enable: true
        text: "See all news"
      count: 10
    design:
      view: compact
      columns: "1"
      spacing:
        padding: ["60px", "20px", "100px", "20px"]
      css_class: "news-page news-list-section"
---