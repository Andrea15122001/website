---

title: "Working Papers" 
url: "/working-papers/" 

--- 
This section presents my working papers and ongoing research projects.

<div style="margin-top:60px;">
  <h1>Conferences and Invited Presentations</h1>
</div>

<div>
  • Copenhagen Business School; Lisbon; Washington, D.C.; Chicago; Columbia Business School, WU Vienna, 2025  
</div>

<div>
  • Bocconi University; HEC Paris; TU Munich, 2024  
</div>

<div>
  • Columbia Business School; Seattle; INSEAD; ZEW Mannheim; University of Miami; University of Lausanne; SDU Odense; Nashville, 2023  
</div>

<div>
  • Copenhagen Business School; Georgia State University; Jagdish Sheth School of Management (virtual); University of Chicago (virtual); Corvinus University of Budapest, 2022  
</div>

<div>
  • University of Rochester (virtual); ESIC Business & Marketing School (virtual); Technion Israel Institute of Technology (virtual), 2021  
</div>




<!-- Start: fix navbar (inserted manually) -->
<script>
(function() {
  function applyFix() {
    const el = document.querySelector('.page-header.header--fixed');
    if (!el) return false;

    ['headroom','headroom--pinned','headroom--top','headroom--bottom','headroom--not-bottom','headroom--not-top'].forEach(c => {
      if (el.classList.contains(c)) el.classList.remove(c);
    });

    el.style.setProperty('position', 'fixed', 'important');
    el.style.setProperty('top', '0', 'important');
    el.style.setProperty('left', '0', 'important');
    el.style.setProperty('width', '100%', 'important');
    el.style.setProperty('z-index', '99999', 'important');
    el.style.setProperty('transform', 'none', 'important');

    const nav = document.getElementById('navbar-main') || el.querySelector('nav, #navbar-main');
    if (nav) {
      nav.style.setProperty('position', 'relative', 'important');
      nav.style.setProperty('z-index', '99999', 'important');
    }

    return true;
  }

  // esegui subito e anche al load (ridondanza utile)
  applyFix();
  window.addEventListener('load', applyFix);
  try {
    const mo = new MutationObserver(() => applyFix());
    mo.observe(document.body, { childList: true, subtree: true, attributes: true });
  } catch(e){}
})();
</script>
<!-- End: fix navbar -->




