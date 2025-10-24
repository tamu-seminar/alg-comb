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

| Date | Speaker | Title | Other |
|------|---------|-------|-------|
| August 29, 2025 | [Gregory Berkolaiko](https://people.tamu.edu/~gberkolaiko/) (TAMU) | Oscillation of graph eigenfunctions and its applications | <button type="button" class="abstract-link" onclick="showAbstract('abs-berkolaiko')">View Abstract</button> |
| September 5, 2025 | | | No seminar (promotion talks) |
| September 12, 2025 | | | No seminar (promotion talks) |
| September 19, 2025 | [Frank Sottile](https://franksottile.github.io/) (TAMU) | $(n-1)!$ formulas for double Schubert polynomials | <button type="button" class="abstract-link" onclick="showAbstract('abs-sottile')">View Abstract</button> |
| September 26, 2025 | [Anne Shepler](https://sites.math.unt.edu/~ashepler/) (UNT) | Coxeter and $q$-Catalan numbers for reflection groups over unpleasant fields | <button type="button" class="abstract-link" onclick="showAbstract('shepler')">View Abstract</button> |
| October 3, 2025 | [Colin Defant](https://sites.google.com/view/colin-defant/home) (Harvard) | Braid Group Presentations and Triangulations of the Permutahedron| <button type="button" class="abstract-link" onclick="showAbstract('defant')">View Abstract</button> |
| October 10, 2025 |  | | |
| October 17, 2025 | [Patricia Klein](https://patriciajklein.github.io/) (TAMU) | Algebra and geometry of ASM weak order | <button type="button" class="abstract-link" onclick="showAbstract('klein')">View Abstract</button> |
| October 24, 2025 | | | |
| October 31, 2025 |[Pablo Ocal](https://pabloocal.github.io/) (ICERM) | The tableaux algebra, with applications to geometry and crystals | <button type="button" class="abstract-link" onclick="showAbstract('ocal')">View Abstract</button> |
| November 7, 2025 | [Blake Jackson](https://www.blakejacksonmath.com/) (UConn) | | |
| November 14, 2025 | | | |
| November 21, 2025 | [Jake Fillman](https://sites.google.com/site/jakefillman/) (TAMU)| On the spectra of periodic graph operators | |
| November 28, 2025 | | | No seminar (Thanksgiving) |
| December 5, 2025 | [Sean Griffin](https://sites.google.com/view/sgriffin/home) (UNT) | | |



# Related Links

- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/algebra-combinatorics/index.html) (not working as of Aug 13, 2025)
- [Departmental website of the algebra and combinatorics group](https://artsci.tamu.edu/mathematics/research/algebra-combinatorics/index.html#Algebra%20and%20Combinatorics) (very out of date of Aug 13, 2025)













<!-- Abstract content -->

<div id="abs-berkolaiko" style="display:none;" aria-hidden="true">
  <p>Oscillation theory, originally due to Sturm, seeks to connect the
number of sign changes of an eigenfunction of a self-adjoint operator
to the label $k$ of the corresponding eigenvalue.  Its applications
run in both directions: knowing $k$, one may wish to estimate the zero
set, or the topology of its complement, useful in clustering and
partitioning problems.  Conversely, knowing an eigenvector (and thus
the number of its sign changes), one may want to determine if it is
the ground state, useful in the linear stability analysis of solutions
to nonlinear equations.</p>

<p>Within the setting of generalized graph Laplacians, Fiedler's theorem
says that the $k$-th eigenvector of a tree (a graph without cycles)
changes sign across exactly $k-1$ edges.  We present a formula for the
number of sign changes on a general graph, which attributes the excess
sign changes to the cycles in the graph and their intersections.</p>

<p>This result has many interesting connections.  First, it allows one to
derive a simple formula for the effective mass tensor of a particular
class of crystals (periodic lattices), namely the maximal abelian
covers of finite graphs.  Second, it can be used to efficiently
determine stability of a stationary solution on a coupled oscillator
network, such as the non-uniform Kuramoto model for the
synchronization of a network of electrical oscillators.  Finally, the
determinant of the matrix which determines the excess sign changes is
closely related to the graph's Kirchhoff polynomial (which counts the
weighted spanning trees), hinting at connections to both Feynman
amplitudes and matroids.</p>

<p>Based on a joint work with Jared Bronski and Mark Goresky.</p>
</div>

<div id="abs-sottile" style="display:none;" aria-hidden="true">
<p>Double Schubert polynomials are a family of polynomials in two sets of variables which represent classes in equivariant cohomology in the flag manifold.   They are indexed by permutations in the symmetric group.  They have many known formulas, including one in terms of pipe dreams by Bergeron and Billey and another in terms of bumpless pipe dreams by Lam, Lee, and Shimizono.</p>

<p>Today, I will describe $(n-1)!$ different formulas for double Schubert polynomials expressed in terms of certain chains in the Bruhat order.  Two of them are the previously mentions pipe dream formulas.  While the results are combinatorial, the methods are geometric.  One ingredient is a specialisation formula from work with Adeyemo from 2017 and another is a Pieri-type formula from work with Li, Ravikumar, and Yang from 2019.  The formula (and proof) generalizes a similar result for ordinary Schubert polynomials from 2002 in work with Bergeron.</p>

<p>This is joint work with Tianyi Yu of UQAM.</p>
</div>

<div id="shepler" style="display:none;" aria-hidden="true">
<p>Motivated by Catalan combinatorics for Weyl and Coxeter groups, we consider differential derivations for reflection groups defined over arbitrary fields, including those with challenging characteristics.  In the classical invariant theory of complex reflection groups, Solomon's celebrated 1963 theorem reveals the invariants of the exterior algebra of differential forms as an exterior algebra in its own right.  We investigate similar invariants when the characteristic of the field divides the order of the acting group and traditional proof techniques break down.</p>
</div>

<div id="defant" style="display:none;" aria-hidden="true">
<p>For each finite Coxeter group $W$ and each standard Coxeter element of $W$, we construct a triangulation of the $W$-permutahedron. Our proof relies on the theory of total linear stability for Dynkin quivers. We also explore several notable combinatorial properties of these triangulations that relate the Bruhat order, the noncrossing partition lattice, and Cambrian congruences. Each triangulation gives an explicit mechanism for relating two different presentations of the corresponding braid group (the standard Artin presentation and Bessis's dual presentation). This is joint work with Melissa Sherman-Bennett and Nathan Williams. </p>
</div>

<div id="ocal" style="display:none;" aria-hidden="true">
<p>Tableaux are fundamental objects in combinatorics and the representation theory of the symmetric group, but they are rarely studied for their own sake. In this talk I will present a natural monoid structure on the set of semistandard Young tableaux, and the good properties inherited by its associated algebra. Just to name a few, it is Koszul, Noetherian, reduced, Jacobson, and Cohen--Macaulay. We will then mention two applications of our work; one to algebraic geometry, and another to representation theory. For the first, we will show that the tableaux algebra is a flat degeneration of the algebra of global sections of the partial flag variety. For the second, we will show that the monoid structure of semistandard Young tableaux induces a crystal embedding when applied to the highest (or lowest) weight vectors. </p>
</div>


<div id="klein" style="display:none;" aria-hidden="true">
<p> In 2018, Hamaker and Reiner generalized the notions of weak order and descent sets from permutations to alternating sign matrices (ASMs).  As one associates a matrix Schubert variety to a permutation, one can more generally associate an intersection of matrix Schubert varieties (now called ASM varieties) to an ASM.  In this talk, we will review the role of matrix Schubert varieties - and their unions and intersections - in Schubert calculus and describe classical uses of the permutation matrices and strong Bruhat order in encoding algebro-geometric invariants.  We will then describe new work giving relationships between poset combinatorics and algebro-geometric invariants determined by the ASMs under weak order. This is joint work with Laura Escobar and Anna Weigandt.
 </p>
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
