---
title: Papers
description: See a list of publications from the OpenGov Lab.
template: narrow.html
---

<div markdown="0">
<script src="https://cdn.jsdelivr.net/gh/pcooksey/bibtex-js@1.0.0/src/bibtex_js.min.js" type="text/javascript"></script>
<bibtex src="/publications.bib"></bibtex>
</div>

<style>
  bibtex { display: none; }

  .publication-list {
    margin-top: 2rem;
  }

  .year-section {
    margin-bottom: 3rem;
  }

  .year-header {
    font-size: 1.5rem;
    font-weight: 600;
    margin-bottom: 1rem;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid var(--md-primary-fg-color);
  }

  .publication-item {
    margin-bottom: 2rem;
    padding-left: 1rem;
    border-left: 3px solid var(--md-accent-fg-color);
    padding-bottom: 1rem;
  }

  .publication-title {
    font-size: 1.1rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
    line-height: 1.4;
  }

  .publication-title a {
    color: var(--md-typeset-a-color);
    text-decoration: none;
  }

  .publication-title a:hover {
    text-decoration: underline;
  }

  .publication-authors {
    color: var(--md-default-fg-color--light);
    margin-bottom: 0.3rem;
  }

  .publication-venue {
    font-style: italic;
    color: var(--md-default-fg-color--lighter);
    margin-bottom: 0.5rem;
  }

  .publication-links {
    margin-top: 0.5rem;
  }

  .publication-links a {
    display: inline-block;
    margin-right: 1rem;
    font-size: 0.9rem;
    color: var(--md-accent-fg-color);
    text-decoration: none;
    padding: 0.2rem 0.5rem;
    border: 1px solid var(--md-accent-fg-color);
    border-radius: 3px;
    transition: all 0.2s;
  }

  .publication-links a:hover {
    background-color: var(--md-accent-fg-color);
    color: white;
  }

  .bibtex-display {
    background-color: var(--md-code-bg-color);
    padding: 1rem;
    border-radius: 5px;
    margin-top: 0.5rem;
    overflow-x: auto;
  }

  .bibtex-display pre {
    margin: 0;
    font-size: 0.85rem;
  }

  #bibtex_errors {
    color: var(--md-warning-fg-color);
    margin-top: 1rem;
  }
</style>

<div class="publication-list">

  <!-- Group publications by year -->
  <div class="bibtex_structure">
    <div class="group year" extra="DESC number">
      <div class="year-section">
        <h2 class="year-header"><span class="year"></span></h2>
        <div class="templates"></div>
      </div>
    </div>
  </div>

  <!-- Publication template -->
  <div id="bibtex_display">
    <div class="bibtex_template" style="display: none;">
      <div class="publication-item">
        <div class="publication-title">
          <span class="if title">
            <span class="if doi">
              <a class="bibtexVar" href="https://doi.org/+DOI+" extra="DOI">
                <span class="title"></span>
              </a>
            </span>
            <span class="if !doi">
              <span class="title"></span>
            </span>
          </span>
        </div>

        <div class="publication-authors">
          <span class="if author">
            <span class="author"></span>
          </span>
        </div>

        <div class="publication-venue">
          <span class="if journal">
            <span class="journal"></span><span class="if volume">, Vol. <span class="volume"></span></span><span class="if number">(<span class="number"></span>)</span><span class="if pages">, pp. <span class="pages"></span></span>
          </span>
          <span class="if booktitle">
            <span class="booktitle"></span><span class="if address">, <span class="address"></span></span>
          </span>
          <span class="if publisher">
            <span class="if !journal"><span class="if !booktitle"><span class="publisher"></span></span></span>
          </span>
        </div>

        <div class="publication-links">
          <span class="if doi">
            <a class="bibtexVar" href="https://doi.org/+DOI+" extra="DOI" target="_blank">DOI</a>
          </span>
          <a class="bibtexVar" href="#bib+BIBTEXKEY+" onclick="document.getElementById('bib+BIBTEXKEY+').style.display = document.getElementById('bib+BIBTEXKEY+').style.display === 'none' ? 'block' : 'none'; return false;" extra="BIBTEXKEY">BibTeX</a>
        </div>

        <div class="bibtexVar bibtex-display" id="bib+BIBTEXKEY+" style="display: none;" extra="BIBTEXKEY">
          <pre><span class="bibtexraw"></span></pre>
        </div>
      </div>
    </div>
  </div>

  <div id="bibtex_errors"></div>

</div>
