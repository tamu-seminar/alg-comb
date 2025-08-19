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


# Fall 2025

This seminar meets on Fridays 3:00-4:00 PM in Blocker 302.

The organizers are [Chun-Hung Liu](https://people.tamu.edu/~chliu/) and [Galen Dorpalen-Barry](https://galen.dorpalen-barry.org/).


| Date         | Speaker | Title |  Other |
|--------------|---------|-------|-------|
| August 29, 2025   | [Gregory Berkolaiko](https://people.tamu.edu/~gberkolaiko/)        |  Oscillation of graph eigenfunctions and its applications     |  <span class="abstract-link" onclick="showAbstract('abs-berkolaiko')">View Abstract</span> |
| September 5, 2025 |         |       |   No seminar (promotion talks)    |
| September 12, 2025|         |       |   No seminar (promotion talks)    |
| September 19, 2025| [Frank Sottile](https://franksottile.github.io/) | $(n-1)!$ formulas for double Schubert polynomials |   <span class="abstract-link" onclick="showAbstract('abs-sottile')">View Abstract</span>     |
| September 26, 2025|         |       |       |
| October 3, 2025   |         |       |       |
| October 10, 2025  |         |       |       |
| October 17, 2025  | [Christin Bibby](https://www.math.lsu.edu/~bibby/)        |  TBA     |       |
| October 24, 2025  |         |       |       |
| October 31, 2025  |         |       |       |
| November 7, 2025  |         |       |       |
| November 14, 2025 |         |       |       |
| November 21, 2025 |         |       |       |
| November 28, 2025 |         |       |  No seminar (Thanksgiving)     |
| December 5, 2025  |         |       |       |



# Related Links

- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/algebra-combinatorics/index.html) (not working as of Aug 13, 2025)
- [Departmental website of the algebra and combinatorics group](https://artsci.tamu.edu/mathematics/research/algebra-combinatorics/index.html#Algebra%20and%20Combinatorics) (very out of date of Aug 13, 2025)













<!-- Abstract content -->

<div id="abs-berkolaiko" style="display:none;">
  <p>We discuss a formula that expresses the number of sign changes of the
$k$-th eigenvector of a graph operator as the sum of the "Sturm
contribution" $k-1$ and a "cycle contribution" which takes the form of
the Morse index (number of negative eigenvalues) of a weighted cycle
intersection form associated with the graph.</p>

  <p>This result has many interesting connections. First, it allows one to
  derive a simple formula for the Hessian of the dispersion relation of
  a particular class of crystals (periodic lattices), namely maximal
  abelian covers of finite graphs. Second, it can be used to
  efficiently determine stability of a stationary solution on a coupled
  oscillator network, such as the non-uniform Kuramoto model for the
  synchronization of a network of electrical oscillators. Finally, the
  determinant of the weighted cycle intersection form is the first
  Symanzik polynomial of the graph (closely related to the Kirchhoff
  polynomial), hinting at connections to both Feynman amplitudes and
  matroids.</p>

  <p>Based on joint work with Jared Bronski and Mark Goresky.</p>
</div>

<div id="abs-sottile" style="display:none;">
<p>Double Schubert polynomials are a family of polynomials in two sets of variables which represent classes in equivariant cohomology in the flag manifold.   They are indexed by permutations in the symmetric group.  They have many known formulas, including one in terms of pipe dreams by Bergeron and Billey and another in terms of bumpless pipe dreams by Lam, Lee, and Shimizono.</p>

<p>Today, I will describe $(n-1)!$ different formulas for double Schubert polynomials expressed in terms of certain chains in the Bruhat order.  Two of them are the previously mentions pipe dream formulas.  While the results are combinatorial, the methods are geometric.  One ingredient is a specialisation formula from work with Adeyemo from 2017 and another is a Pieri-type formula from work with Li, Ravikumar, and Yang from 2019.  The formula (and proof) generalizes a similar result for ordinary Schubert polynomials from 2002 in work with Bergeron.</p>

<p>This is joint work with Tianyi Yu of UQAM.</p>
</div>


<!-- Code that makes the pop-up windows -->

<style>
.abstract-link {
  color: rgb(69, 68, 182);
  font-weight: bold;
  cursor: pointer;
}
.abstract-link:hover {
      color: rgb(69, 68, 182);
      text-decoration: underline;
      font-weight: bold;
    }
</style>

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

<!-- Modal structure -->
<div id="abstract-modal-overlay" onclick="closeAbstractModal(event)">
  <div id="abstract-modal" onclick="event.stopPropagation()">
    <span id="abstract-modal-close" onclick="closeAbstractModal()">&times;</span>
    <h2>Abstract</h2>
    <div id="abstract-modal-content"></div>
  </div>
</div>

<script>
function showAbstract(id) {
  const content = document.getElementById(id).innerHTML;
  document.getElementById('abstract-modal-content').innerHTML = content;
  document.getElementById('abstract-modal-overlay').style.display = 'block';
}

function closeAbstractModal(event) {
  if (!event || event.target.id === 'abstract-modal-overlay' || event.target.id === 'abstract-modal-close') {
    document.getElementById('abstract-modal-overlay').style.display = 'none';
  }
}
</script>
