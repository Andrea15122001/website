---
title: ""
type: blank
url: "/contact/"
---

<div style="max-width: 800px; margin: 60px auto; padding: 0 1rem;">

<h1>Contact</h1>

<p>I am happy to hear from you, whether it is about research, potential collaborations, or just to connect. Use the form below and I will get back to you as soon as I can.</p>

<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field" action="/contact/success/">

  <input type="hidden" name="form-name" value="contact" />
  <input type="hidden" name="_replyto" value="andreazamo39@gmail.com" />
  <p style="display:none;"><label>Don't fill this out: <input name="bot-field"></label></p>

  <div style="margin-bottom: 1.2rem;">
    <label style="display:block; font-weight:700; margin-bottom:0.4rem;">Name</label>
    <input type="text" name="name" required
      style="width:100%; padding:0.75rem 1rem; border:1px solid #ddd; border-radius:8px; font-size:1rem; box-sizing:border-box;">
  </div>

  <div style="margin-bottom: 1.2rem;">
    <label style="display:block; font-weight:700; margin-bottom:0.4rem;">Email</label>
    <input type="email" name="email" required
      style="width:100%; padding:0.75rem 1rem; border:1px solid #ddd; border-radius:8px; font-size:1rem; box-sizing:border-box;">
  </div>

  <div style="margin-bottom: 1.5rem;">
    <label style="display:block; font-weight:700; margin-bottom:0.4rem;">Message</label>
    <textarea name="message" rows="6" required
      style="width:100%; padding:0.75rem 1rem; border:1px solid #ddd; border-radius:8px; font-size:1rem; box-sizing:border-box; resize:vertical;"></textarea>
  </div>

  <button type="submit"
    style="padding:0.75rem 2rem; background-color:#003A8F; color:#fff; border:none; border-radius:8px; font-size:1rem; font-weight:700; cursor:pointer;">
    Send
  </button>

</form>
</div>

<!-- Start: fix navbar -->
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
  applyFix();
  window.addEventListener('load', applyFix);
  try {
    const mo = new MutationObserver(() => applyFix());
    mo.observe(document.body, { childList: true, subtree: true, attributes: true });
  } catch(e){}
})();
</script>
<!-- End: fix navbar -->
