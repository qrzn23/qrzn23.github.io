---
title: Books
icon: fas fa-book-open
order: 5
---

<style>
  .books-search {
    position: relative;
    margin-bottom: 1rem;
  }
  .books-search svg {
    position: absolute;
    left: 0.75rem;
    top: 50%;
    transform: translateY(-50%);
    width: 14px;
    height: 14px;
    opacity: 0.45;
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
  #book-search::placeholder { opacity: 0.45; }
  #book-search:focus { border-color: rgba(167,139,250,0.55); }

  .book-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  .book-list li {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
    padding: 0.6rem 0.5rem;
    border-bottom: 1px solid var(--card-border-color, #2e2e2e);
  }
  .book-list li:last-child { border-bottom: none; }
  .book-list .book-name {
    font-size: 0.875rem;
    min-width: 0;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .book-list .book-dl {
    display: inline-flex;
    align-items: center;
    gap: 0.35rem;
    font-size: 0.78rem;
    font-weight: 500;
    color: #a78bfa;
    text-decoration: none;
    flex-shrink: 0;
    padding: 0.2rem 0.6rem;
    border: 1px solid var(--card-border-color, #2e2e2e);
    border-radius: 4px;
    transition: background 0.15s, border-color 0.15s;
  }
  .book-list .book-dl:hover {
    background: rgba(167,139,250,0.1);
    border-color: rgba(167,139,250,0.4);
  }
  .book-list .book-dl svg {
    width: 12px;
    height: 12px;
    flex-shrink: 0;
  }
</style>

<div class="books-search">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
  <input id="book-search" type="search" placeholder="Filter books…" autocomplete="off">
</div>

<ul class="book-list" id="book-list">
  <li data-name="aleph">
    <span class="book-name">aleph</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/aleph.epub" download="aleph.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="confessions">
    <span class="book-name">confessions</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/confessions.epub" download="confessions.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="essays-truth">
    <span class="book-name">essays-truth</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/essays-truth.epub" download="essays-truth.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="l220comments">
    <span class="book-name">l220comments</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/l220comments.epub" download="l220comments.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="ld">
    <span class="book-name">ld</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/ld.epub" download="ld.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="liber220">
    <span class="book-name">liber220</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/liber220.epub" download="liber220.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="liber333">
    <span class="book-name">liber333</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/liber333.epub" download="liber333.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="liber418">
    <span class="book-name">liber418</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/liber418.epub" download="liber418.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="magick">
    <span class="book-name">magick</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/magick.epub" download="magick.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="mwt">
    <span class="book-name">mwt</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/mwt.epub" download="mwt.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
  <li data-name="ttk">
    <span class="book-name">ttk</span>
    <a class="book-dl" href="https://raw.githubusercontent.com/qrzn23/min/main/books/ttk.epub" download="ttk.epub">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
      ePub
    </a>
  </li>
</ul>

<script>
  const input = document.getElementById('book-search');
  if (input) {
    input.addEventListener('input', () => {
      const q = input.value.toLowerCase();
      document.querySelectorAll('#book-list li').forEach(li => {
        li.style.display = li.dataset.name.includes(q) ? '' : 'none';
      });
    });
  }
</script>
