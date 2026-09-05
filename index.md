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


# Fall 2026

This seminar meets on Fridays 3:00-4:00 PM in Blocker 302.

The organizers are [Trevor Karn](https://trevorkarn.github.io/) and [Galen Dorpalen-Barry](https://galen.dorpalen-barry.org/).

| Date              | Speaker | Title | Other                           |
|-------------------|---------|-------|---------------------------------|
| August 28, 2026   |         |       | No seminar                      |
| September 4, 2026 |         |       | No seminar                      |
| September 11, 2026|         |       | No seminar                      |
| September 18, 2026|         |       | No seminar                      |
| September 25, 2026|[Frank Sottile](https://franksottile.github.io/) (TAMU)| A Littlewood-Richardson Rule for $$2$$-Grassmannian Permutations      | <button type="button" class="abstract-link" onclick="showAbstract('sottile')">View Abstract</button>                               |
| October 2, 2026   |         |       |                                 |
| October 9, 2026   |[Catherine Yan](https://people.tamu.edu/~huafei-yan/) (TAMU)       |       |                                 |
| October 16, 2026  |[Charlie Maglund](https://charlie.magland.org/) (UW)         |       |                                 |
| October 23, 2026  |         |       |                                 |
| October 30, 2026  |         |       | No seminar, [SIAM TX-LA Regional Meeting](https://sites.google.com/view/siam-txla-2026)                                |
| November 6, 2026  |         |       |                                 |
| November 13, 2026 |         |       |                                 |
| November 20, 2026 |         |       |                                 |
| November 27, 2026 |         |       | No seminar, Thanksgiving.       |
| December 4, 2026  |         |       | No seminar, reading day/finals. |

# Past Semesters
- [Spring 2026](2026_1.md)
- [Fall 2025](2025_2.md)


# Related Links
- [Texas A&M Geometry Seminar](https://tamu-seminar.github.io/geometry/) 
- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/algebra-combinatorics/index.html)
- [Departmental website of the algebra and combinatorics group](https://artsci.tamu.edu/mathematics/research/algebra-combinatorics/index.html#Algebra%20and%20Combinatorics) (not current!)


<!-- abstracts -->

<div id="sottile" style="display:none;" aria-hidden="true">
<p>Giving  a  manifestly positive  formula  for  the structure  constants
arising  from  the  multiplication  of two  Schubert  classes  in  the
cohomology  of a  flag manifold  is  a long-standing  open problem  in
algebraic combinatorics.   This has  only seen limited  progress. Most
results have restrictions on both classes that are multiplied, and the
only formula with a restriction on  only one is the Pieri-type formula
that is 30 years old.

In  this  talk,  I  will  describe  formulas,  in  both  ordinary  and
equivariant  cohomology,   for  the   coefficients  that   arise  when
multiplying a Schubert class by one pulled back from a Grassmannian of
$2$-planes.   This  uses  geometric   constructions  including  a  novel
description of certain positroid varieties.  The cohomological formula
identifies  each   coefficient  as   particular  Littlewood-Richardson
coefficient on a Grassmannian of $k$-planes, for some $k$, not necessarily
equal to $2$.

This is joint work with Changzheng Li and Mingzhi Yang.</p>
</div>

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
