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
  # CUSTOM STYLES
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Source+Sans+3:wght@300;400;500;600&display=swap');
        
        :root {
          --eahl-navy: #0a1628;
          --eahl-navy-light: #162544;
          --eahl-cream: #faf8f5;
          --eahl-accent: #4a90a4;
          --eahl-coral: #e07a5f;
          --eahl-sage: #6b8f71;
          --eahl-text: #374151;
          --eahl-text-light: #6b7280;
          --eahl-border: #e5e7eb;
        }
        
        .news-page h1, .news-page h2, .news-page h3 {
          font-family: 'Playfair Display', Georgia, serif !important;
        }
        
        .news-page p, .news-page span, .news-page a, .news-page li {
          font-family: 'Source Sans 3', -apple-system, sans-serif !important;
        }
        
        /* ===== HERO ===== */
        .news-hero {
          background: linear-gradient(180deg, #ffffff 0%, var(--eahl-cream) 100%) !important;
        }
        
        .news-hero-content {
          max-width: 800px;
          margin: 0 auto;
          text-align: center;
          padding: 0 24px;
        }
        
        .news-hero-label {
          display: inline-flex;
          align-items: center;
          gap: 12px;
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.2em;
          text-transform: uppercase;
          color: var(--eahl-accent);
          margin-bottom: 24px;
        }
        
        .news-hero-label::before,
        .news-hero-label::after {
          content: '';
          width: 32px;
          height: 1px;
          background: var(--eahl-accent);
          opacity: 0.5;
        }
        
        .news-hero-title {
          font-size: clamp(2.5rem, 5.5vw, 4rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.1 !important;
          margin-bottom: 24px !important;
          letter-spacing: -0.02em;
        }
        
        .news-hero-title em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .news-hero-divider {
          width: 64px;
          height: 3px;
          background: var(--eahl-coral);
          margin: 0 auto 28px auto;
          border-radius: 2px;
        }
        
        .news-hero-desc {
          font-size: 1.15rem;
          color: var(--eahl-text-light);
          line-height: 1.75;
          max-width: 600px;
          margin: 0 auto;
        }
        
        /* ===== NEWS LIST SECTION ===== */
        .news-list-section {
          background: var(--eahl-cream) !important;
        }
        
        /* ===== OVERRIDE HUGO NEWS/POST STYLES ===== */
        .news-page article,
        .news-page .card {
          background: #ffffff !important;
          border: 1px solid var(--eahl-border) !important;
          border-radius: 16px !important;
          overflow: hidden !important;
          transition: all 0.3s ease !important;
          margin-bottom: 24px !important;
        }
        
        .news-page article:hover,
        .news-page .card:hover {
          transform: translateY(-4px) !important;
          box-shadow: 0 16px 32px rgba(10, 22, 40, 0.08) !important;
          border-color: transparent !important;
        }
        
        .news-page .card-body {
          padding: 28px !important;
        }
        
        .news-page .article-title,
        .news-page .card-title {
          font-family: 'Playfair Display', Georgia, serif !important;
          font-size: 1.25rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.4 !important;
          margin-bottom: 12px !important;
        }
        
        .news-page .article-title a,
        .news-page .card-title a {
          color: var(--eahl-navy) !important;
          text-decoration: none !important;
          transition: color 0.2s ease !important;
        }
        
        .news-page .article-title a:hover,
        .news-page .card-title a:hover {
          color: var(--eahl-accent) !important;
        }
        
        .news-page .article-metadata,
        .news-page .card-text {
          font-family: 'Source Sans 3', sans-serif !important;
          font-size: 0.95rem !important;
          color: var(--eahl-text-light) !important;
        }
        
        .news-page .article-date,
        .news-page time {
          font-size: 0.85rem !important;
          color: var(--eahl-text-light) !important;
          font-weight: 500 !important;
        }
        
        .news-page .badge {
          font-family: 'Source Sans 3', sans-serif !important;
          font-size: 0.75rem !important;
          font-weight: 600 !important;
          background: rgba(74, 144, 164, 0.1) !important;
          color: var(--eahl-accent) !important;
          border: 1px solid rgba(74, 144, 164, 0.2) !important;
          padding: 4px 12px !important;
          border-radius: 100px !important;
        }
        
        .news-page .btn-outline-primary {
          color: var(--eahl-accent) !important;
          border-color: var(--eahl-accent) !important;
          border-radius: 100px !important;
          padding: 8px 20px !important;
          font-weight: 500 !important;
        }
        
        .news-page .btn-outline-primary:hover {
          background: var(--eahl-accent) !important;
          color: #fff !important;
        }
        
        /* Section title styling */
        .news-page section h2 {
          font-family: 'Playfair Display', Georgia, serif !important;
          font-size: clamp(1.5rem, 3vw, 1.8rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          letter-spacing: -0.02em !important;
          margin-bottom: 32px !important;
        }
        
        /* Featured image styling */
        .news-page .card-img-top,
        .news-page .featured-image {
          border-radius: 12px 12px 0 0 !important;
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
          .news-hero-content { padding: 0 20px; }
        }
        </style>
    design:
      columns: "1"
      spacing:
        padding: ["0", "0", "0", "0"]

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