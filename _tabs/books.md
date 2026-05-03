---
title: Books
icon: fas fa-book-open
order: 5
---

<style>
  .books-search {
    position: relative;
    margin-bottom: 1.5rem;
  }
  .books-search svg {
    position: absolute;
    left: 0.75rem;
    top: 50%;
    transform: translateY(-50%);
    width: 14px;
    height: 14px;
    opacity: 0.4;
    pointer-events: none;
  }
  #book-search {
    width: 100%;
    padding: 0.5rem 0.75rem 0.5rem 2.25rem;
    background: var(--card-bg, #1a1a1a);
    border: 1px solid var(--card-border-color, #2e2e2e);
    border-radius: 6px;
    color: inherit;
    font-size: 0.875rem;
    font-family: inherit;
    outline: none;
    transition: border-color 0.15s;
  }
  #book-search::placeholder { opacity: 0.4; }
  #book-search:focus { border-color: rgba(167,139,250,0.55); }

  .book-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(148px, 1fr));
    gap: 1rem;
  }

  .book-card {
    display: flex;
    flex-direction: column;
    border: 1px solid var(--card-border-color, #2e2e2e);
    border-radius: 8px;
    overflow: hidden;
    background: var(--card-bg, #161616);
    transition: border-color 0.15s, transform 0.15s;
  }
  .book-card:hover {
    border-color: rgba(167,139,250,0.45);
    transform: translateY(-2px);
  }

  .book-cover-wrap {
    width: 100%;
    aspect-ratio: 2 / 3;
    overflow: hidden;
    background: #111;
    flex-shrink: 0;
  }
  .book-cover-wrap img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  .book-info {
    padding: 0.65rem 0.65rem 0.6rem;
    display: flex;
    flex-direction: column;
    flex: 1;
    gap: 0.2rem;
  }
  .book-title {
    font-size: 0.78rem;
    font-weight: 600;
    line-height: 1.35;
    color: var(--heading-color, #e5e5e5);
  }
  .book-author {
    font-size: 0.7rem;
    opacity: 0.5;
    line-height: 1.3;
    flex: 1;
  }
  .book-dl {
    display: inline-flex;
    align-items: center;
    gap: 0.3rem;
    font-size: 0.7rem;
    font-weight: 500;
    color: #a78bfa;
    text-decoration: none;
    margin-top: 0.5rem;
    padding: 0.2rem 0.55rem;
    border: 1px solid var(--card-border-color, #2e2e2e);
    border-radius: 4px;
    align-self: flex-start;
    transition: background 0.15s, border-color 0.15s;
  }
  .book-dl:hover {
    background: rgba(167,139,250,0.1);
    border-color: rgba(167,139,250,0.4);
    color: #a78bfa;
    text-decoration: none;
  }
  .book-dl svg {
    width: 11px;
    height: 11px;
    flex-shrink: 0;
  }
</style>

<div class="books-search">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
  <input id="book-search" type="search" placeholder="Filter by title or author…" autocomplete="off">
</div>

<div class="book-grid" id="book-grid">

  <div class="book-card" data-name="liber aleph book of wisdom or folly aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/aleph/cover.png" alt="Liber Aleph cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Liber Aleph — The Book of Wisdom or Folly</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/aleph.epub" download="aleph.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="confessions of aleister crowley aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/confessions/cover.png" alt="Confessions cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">The Confessions of Aleister Crowley</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/confessions.epub" download="confessions.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="little essays towards truth aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/little-essays-towards-truth/cover.jpg" alt="Little Essays Towards Truth cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Little Essays Towards Truth</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/essays-truth.epub" download="essays-truth.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="commentaries to liber al vel legis aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/l220comments/cover.jpg" alt="Commentaries to Liber AL cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Commentaries to Liber AL vel Legis</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/l220comments.epub" download="l220comments.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="lia dsi das wahre buch vom quellenden urgrund richard wilhelm">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/ld/cover.jpg" alt="Liä Dsi cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Liä Dsi — Das wahre Buch vom Quellenden Urgrund</div>
      <div class="book-author">Richard Wilhelm</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/ld.epub" download="ld.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="liber al vel legis book of the law aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/l220/cover.jpg" alt="Liber AL vel Legis cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Liber AL vel Legis — The Book of the Law</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/liber220.epub" download="liber220.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="liber cccxxxiii book of lies aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/liber333/cover.png" alt="The Book of Lies cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Liber CCCXXXIII — The Book of Lies</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/liber333.epub" download="liber333.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="liber 418 vision and the voice aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/l418/cover.png" alt="Liber 418 cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Liber 418 — The Vision &amp; The Voice</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/liber418.epub" download="liber418.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="magick in theory and practice aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/magick/cover.jpg" alt="Magick in Theory and Practice cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Magick in Theory and Practice</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/magick.epub" download="magick.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="magick without tears aleister crowley">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/mwt/cover.jpg" alt="Magick Without Tears cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Magick Without Tears</div>
      <div class="book-author">Aleister Crowley</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/mwt.epub" download="mwt.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

  <div class="book-card" data-name="tao te king richard wilhelm">
    <div class="book-cover-wrap">
      <img src="https://raw.githubusercontent.com/qrzn23/min/main/wip/ttk/cover.jpg" alt="Tao Te King cover" loading="lazy">
    </div>
    <div class="book-info">
      <div class="book-title">Tao Te King</div>
      <div class="book-author">Richard Wilhelm</div>
      <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/ttk.epub" download="ttk.epub">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        ePub
      </a>
    </div>
  </div>

</div>

<script>
  const input = document.getElementById('book-search');
  if (input) {
    input.addEventListener('input', () => {
      const q = input.value.toLowerCase();
      document.querySelectorAll('#book-grid .book-card').forEach(card => {
        card.style.display = card.dataset.name.includes(q) ? '' : 'none';
      });
    });
  }
</script>
