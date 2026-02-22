---
title: "Research"
type: "page"
---
<style>
/* FORCE override per la sola pagina Research - mettere inline nella page (ultimo CSS caricato) */

/* contenitore largo solo per research */
body.page-research .article-container {
  max-width: 900px !important;
}

/* layout entry: testo + immagine */
body.page-research .article-container .research-page .pub-entry{
  display: flex !important;
  align-items: flex-start !important;
  justify-content: space-between !important;
  gap: 24px !important;
}

/* colonna testo - testo un filo più piccolo, mantengo proporzioni */
body.page-research .article-container .research-page .pub-text{
  flex: 1 1 auto !important;
  min-width: 0 !important;
  font-size: 0.92rem !important;    /* testo un po' più piccolo */
  line-height: 1.45 !important;
}

/* titoli / abstract / autori - proporzioni */
body.page-research .article-container .research-page .pub-title a{
  font-size: 1.32em !important;
}
body.page-research .article-container .research-page .pub-abstract{
  font-size: 1.00em !important;
}
body.page-research .article-container .research-page .pub-authors{
  font-size: 1.00em !important;
}

/* IMMAGINI: molto più piccole (meno della metà) */
body.page-research .article-container .research-page .pub-image{
  flex: 0 0 80px !important;   /* larghezza colonna immagine - cambia 80 -> 70/90 a piacere */
  width: 80px !important;
  margin-top: 0 !important;
}
body.page-research .article-container .research-page .pub-image img{
  width: 80px !important;      /* dimensione immagine */
  max-width: 80px !important;
  height: auto !important;
  display: block !important;
  margin: 0 !important;
  object-fit: cover !important;
  border-radius: 8px !important;
}

/* spazio tra h2 (titoletti quali "Publications", "Working Papers") e contenuto sotto */
body.page-research .article-style h2{
  margin-top: 3.2rem !important;
  margin-bottom: 1.5rem !important;
}

/* spazio tra entry */
body.page-research .article-container .research-page .pub-sep{
  margin: 1.5rem 0 !important;
}

/* mobile: impila verticalmente e ingrandisci immagine leggermente */
@media (max-width: 768px){
  body.page-research .article-container .research-page .pub-entry{
    flex-direction: column !important;
    gap: 12px !important;
  }
  body.page-research .article-container .research-page .pub-image{
    width: 90px !important;
    flex: 0 0 90px !important;
  }
  body.page-research .article-container .research-page .pub-image img{
    width: 90px !important;
    max-width: 90px !important;
  }
}
</style>
<div class="research-page research-wide">

This section presents my research publications, linked to their full texts. Additional information can be accessed by clicking on each publication. Below, you will also find my working papers, conference presentations, and invited talks.

## Publications

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="https://harmonious-kulfi-eaaf70.netlify.app/publications/influencer-marketing-unlocked-understanding-the-value-chains-driving-the-creator-economy/" target="_blank" rel="noopener">
Influencer Marketing Unlocked: Understanding the Value Chains Driving the Creator Economy
</a>
</div>

<div class="pub-abstract">
As influencer marketing evolves into a dominant force in the marketing landscape, it necessitates a deeper theoretical exploration to understand its strategic implementations and impacts. This article examines the dynamics of influencer marketing within the growing creator economy, emphasizing the interactions among...
</div>

<div class="pub-authors">
Maximilian Beichert, Barak Libai, Ana Babic Rosario, Bas Donkers, Michael Haenlein, Reto Hofstetter, P.K. Kannan, Ralf van der Lans, Andreas Lanz, Alice Li, Dina Mayzlin, Eitan Muller, Daniel Shapira, Jeremy Yang, Lingling Zhang
</div>

<a class="pub-pdf" href="https://link.springer.com/article/10.1007/s11747-024-01073-2" target="_blank" rel="noopener">PDF</a>
</div>

<div class="pub-image">
<img src="../uploads/featured3_1.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="https://harmonious-kulfi-eaaf70.netlify.app/publications/the_surprising_roi_of_small_online_influencers/" target="_blank" rel="noopener">
The Surprising ROI of Small Online Influencers
</a>
</div>

<div class="pub-abstract">
For social media marketing, many companies gravitate to big-name endorsers. But there are good reasons to get “nano influencers” into the mix.
</div>

<div class="pub-authors">
Maximilian Beichert, Andreas Bayerl, Jacob Goldenberg, Andreas Lanz, Xiaoxi Zhang, Xian Gu, P.K. Kannan
</div>

<a class="pub-pdf" href="https://sloanreview.mit.edu/article/the-surprising-roi-of-small-online-influencers/" target="_blank" rel="noopener">PDF</a>
</div>

<div class="pub-image">
<img src="../uploads/featured2_1.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="https://harmonious-kulfi-eaaf70.netlify.app/publications/revenue-generation-through-influencer-marketing/" target="_blank" rel="noopener">
Revenue Generation Through Influencer Marketing
</a>
</div>

<div class="pub-abstract">
Direct-to-consumer firms increasingly believe that influencer marketing is an effective option for seeding. However, the current managerially relevant question for direct-to-consumer firms of whether to target low- or high-followership influencers to generate immediate revenue is still unresolved. In this article, the...
</div>

<div class="pub-authors">
Maximilian Beichert, Andreas Bayerl, Jacob Goldenberg, Andreas Lanz
</div>

<a class="pub-pdf" href="https://journals.sagepub.com/doi/10.1177/00222429231217471" target="_blank" rel="noopener">PDF</a>
</div>

<div class="pub-image">
<img src="../uploads/featured1_1.jpg" alt="">
</div>
</div>



## Working Papers

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="#" onclick="return false;">The Influencer Lifetime Value</a>
</div>

<div class="pub-authors">
Maximilian Beichert, Caio Vieira, Peter Ebbes, Andreas Lanz
</div>
</div>

<div class="pub-image">
<img src="/uploads/tilv.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="#" onclick="return false;">The Gender Pay Gap in Influencer Marketing</a>
</div>

<div class="pub-authors">
Maximilian Beichert, Victoria Meil, Oded Netzer
</div>
</div>

<div class="pub-image">
<img src="/uploads/tgpg.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="#" onclick="return false;">Influencer Sharenting</a>
</div>

<div class="pub-authors">
Maximilian Beichert, Lucia Malaer, Andrea Giuffredi-Kaehr, Jacob Goldenberg
</div>
</div>

<div class="pub-image">
<img src="/uploads/is.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="#" onclick="return false;">Influencer Selection Using a Multi-Task Learning Model</a>
</div>

<div class="pub-authors">
Maximilian Beichert, Magie Cheng, Shunyuan Zhang, Xitong Li
</div>
</div>

<div class="pub-image">
<img src="/uploads/i-s.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="#" onclick="return false;">Influencer Marketing and Customer Touchpoints</a>
</div>

<div class="pub-authors">
Maximilian Beichert, Xiaoxi Zhang, Xian Gu
</div>
</div>

<div class="pub-image">
<img src="/uploads/imc.jpg" alt="">
</div>
</div>

<hr class="pub-sep">

<div class="pub-entry">
<div class="pub-text">
<div class="pub-title">
<a href="#" onclick="return false;">Influence That Lasts: Indirect Sales from Influencer Marketing Campagns</a>
</div>

<div class="pub-authors">
Maximilian Beichert, Guangqi Dong, Xian Gu
</div>
</div>

<div class="pub-image">
<img src="/uploads/itli.jpg" alt="">
</div>
</div>

<hr class="pub-sep">


## Conferences and Invited Presentations

- Copenhagen Business School; Lisbon; Washington, D.C.; Chicago; Columbia Business School, WU Vienna, 2025
- Bocconi University; HEC Paris; TU Munich, 2024
- Columbia Business School; Seattle; INSEAD; ZEW Mannheim; University of Miami; University of Lausanne; SDU Odense; Nashville, 2023
- Copenhagen Business School; Georgia State University; Jagdish Sheth School of Management (virtual); University of Chicago (virtual); Corvinus University of Budapest, 2022
- University of Rochester (virtual); ESIC Business & Marketing School (virtual); Technion Israel Institute of Technology (virtual), 2021


<!-- ###############################
     FIX IMMEDIATO: forza stili via JS
     Inserisci questo blocco IN FONDO a content/research.md
     ############################### -->
<script>
document.addEventListener("DOMContentLoaded", function () {
  // 1) rendi le immagini molto più piccole (colonna + immagine)
  document.querySelectorAll('.pub-image').forEach(function(imgCol){
    imgCol.style.flex = '0 0 80px';
    imgCol.style.width = '80px';
    imgCol.style.marginTop = '0';
  });
  document.querySelectorAll('.pub-image img').forEach(function(img){
    img.style.width = '80px';
    img.style.maxWidth = '80px';
    img.style.height = 'auto';
    img.style.display = 'block';
    img.style.margin = '0';
    img.style.objectFit = 'cover';
    img.style.borderRadius = '8px';
  });

  // 2) testo: riduci leggermente la dimensione e mantieni proporzioni
  document.querySelectorAll('.pub-text').forEach(function(text){
    text.style.fontSize = '0.92rem';
    text.style.lineHeight = '1.45';
  });
  document.querySelectorAll('.pub-title a').forEach(function(a){
    // Titoli proporzionalmente più grandi
    a.style.fontSize = '1.32em';
  });
  document.querySelectorAll('.pub-abstract, .pub-authors').forEach(function(el){
    el.style.fontSize = '1.00em';
  });

  // 3) spazio tra H2 (titoletti) e contenuto successivo
  document.querySelectorAll('.article-style h2, .article-container h2').forEach(function(h2){
    h2.style.marginTop = '3.2rem';
    h2.style.marginBottom = '1.5rem';
  });

  // 4) spazio tra entries
  document.querySelectorAll('.pub-sep').forEach(function(hr){
    hr.style.margin = '1.5rem 0';
  });

  // 5) mobile: impila verticalmente (se vuoi forzare anche su mobile)
  function applyMobile() {
    if (window.innerWidth <= 768) {
      document.querySelectorAll('.pub-entry').forEach(function(entry){
        entry.style.flexDirection = 'column';
        entry.style.gap = '12px';
      });
      document.querySelectorAll('.pub-image').forEach(function(imgCol){
        imgCol.style.width = '90px';
        imgCol.style.flex = '0 0 90px';
      });
      document.querySelectorAll('.pub-image img').forEach(function(img){
        img.style.width = '90px';
        img.style.maxWidth = '90px';
      });
    } else {
      // restore desktop values (in case of resize)
      document.querySelectorAll('.pub-entry').forEach(function(entry){
        entry.style.flexDirection = '';
        entry.style.gap = '';
      });
      document.querySelectorAll('.pub-image').forEach(function(imgCol){
        imgCol.style.width = '80px';
        imgCol.style.flex = '0 0 80px';
      });
      document.querySelectorAll('.pub-image img').forEach(function(img){
        img.style.width = '80px';
        img.style.maxWidth = '80px';
      });
    }
  }

  applyMobile();
  window.addEventListener('resize', applyMobile);
});
</script>
</div>
