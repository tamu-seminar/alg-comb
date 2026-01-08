---
layout: default
---

<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    },
    svg: { fontCache: 'global' }
  };
</script>

<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js" async></script>


# Spring 2026

This seminar meets on Fridays 3:00-4:00 PM in Blocker 302.

The organizers are [Chun-Hung Liu](https://people.tamu.edu/~chliu/), [Trevor Karn](https://trevorkarn.github.io/), and [Galen Dorpalen-Barry](https://galen.dorpalen-barry.org/).

| Date              | Speaker | Title | Other |
|-------------------|---------|-------|-------|
| January 16, 2026  |         |       |       |
| January 23, 2026  |         |       |       |
| January 30, 2026  | [Luca Di Cerbo](https://people.clas.ufl.edu/ldicerbo/) (UF)     |  Curvature, Macroscopic Dimensions, and Symmetric Product of Curves     | TBA      |
| February 6, 2026  |         |       |       |
| February 13, 2026 |         |       |       |
| February 20, 2026 | [Christin Bibby](https://www.math.lsu.edu/~bibby/) (LSU)    |   TBA    |   TBA    |
| February 27, 2026 |         |       |       |
| March 6, 2026     |         |       |       |
| March 13, 2026    |No seminar|Spring|Break  |
| March 20, 2026    |         |       |       |
| March 27, 2026    |         |       |       |
| April 3, 2026     |No seminar|Reading|Day   |
| April 10, 2026    |         |       |       |
| April 17, 2026    |         |       |       |
| April 24, 2026    |         |       |       |
| April 25-26, 2026    |         |  [Combinatexas](https://sites.google.com/view/combinatexas-2026/home)     |       |



# Past Semesters
- [Fall 2025](2025_2.md)


# Related Links

- [Combinatexas](https://sites.google.com/view/combinatexas-2026/home)
- [Texas A&M Geometry Seminar](https://tamu-seminar.github.io/geometry/) 
- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/algebra-combinatorics/index.html) (not working as of Aug 13, 2025)
- [Departmental website of the algebra and combinatorics group](https://artsci.tamu.edu/mathematics/research/algebra-combinatorics/index.html#Algebra%20and%20Combinatorics) (very out of date of Aug 13, 2025)













<!-- Abstract content -->



<!-- Code that makes the pop-up windows -->

<style>
/* Modal background */
#abstract-modal-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.5);
  display: none;
  z-index: 1000;
}

/* Modal box */
#abstract-modal {
  background: white;
  width: 80%;
  max-width: 700px;
  margin: 5% auto;
  padding: 20px;
  border-radius: 8px;
  position: relative;
  overflow-y: auto;
  max-height: 90vh;
  font-family: Arial, sans-serif;
}

/* Close button */
#abstract-modal-close {
  position: absolute;
  top: 10px;
  right: 15px;
  font-size: 20px;
  cursor: pointer;
}
</style>

<div id="abstract-modal-overlay"
     role="dialog"
     aria-modal="true"
     aria-labelledby="abstract-modal-title"
     style="display:none;"
     onclick="closeAbstractModal(event)">
  <div id="abstract-modal" onclick="event.stopPropagation()">
    <button id="abstract-modal-close"
            aria-label="Close abstract modal"
            onclick="closeAbstractModal()">&times;</button>
    <h2 id="abstract-modal-title">Abstract</h2>
    <div id="abstract-modal-content" tabindex="0"></div>
  </div>
</div>

<script>
function showAbstract(id) {
  const content = document.getElementById(id).innerHTML;
  document.getElementById('abstract-modal-content').innerHTML = content;

  const overlay = document.getElementById('abstract-modal-overlay');
  overlay.style.display = 'block';

  // Move focus into the modal
  document.getElementById('abstract-modal').focus();

  // Add Esc key support
  document.addEventListener('keydown', escCloseHandler);
}

function closeAbstractModal(event) {
  if (!event || event.target.id === 'abstract-modal-overlay' || event.target.id === 'abstract-modal-close') {
    document.getElementById('abstract-modal-overlay').style.display = 'none';

    // Remove Esc key support
    document.removeEventListener('keydown', escCloseHandler);
  }
}

function escCloseHandler(e) {
  if (e.key === 'Escape') {
    closeAbstractModal();
  }
}
</script>
