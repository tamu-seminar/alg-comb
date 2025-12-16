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
| January 30, 2026  |         |       |       |
| February 6, 2026  |         |       |       |
| February 13, 2026 |         |       |       |
| February 20, 2026 | [Christin Bibby](https://www.math.lsu.edu/~bibby/) (LSU)    |   TBA    |   TBA    |
| February 27, 2026 |         |       |       |
| March 6, 2026     |         |       |       |
| March 13, 2026    |         |       |       |
| March 20, 2026    |         |       |       |
| March 27, 2026    |         |       |       |
| April 3, 2026     |         |       |       |
| April 10, 2026    |         |       |       |
| April 17, 2026    |         |       |       |
| April 24, 2026    |         |       |       |
| April 25-26, 2026    |         |  Combinatexas     |  [Conference Website](https://sites.google.com/view/combinatexas-2026/home)     |



# Past Semesters
- [Fall 2025](2025_2.md)


# Related Links

- [Combinatexas](https://sites.google.com/view/combinatexas-2026/home)
- [Geometry Seminar](https://tamu-seminar.github.io/geometry/) 
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
<p>Tableaux are fundamental objects in representation theory and combinatorics, and variations of the Schensted algorithm have endowed them with rich algebraic structures. In this talk I will discuss a naive monoid structure on the set of semistandard Young tableaux that does not arise as an insertion algorithm, and the good properties inherited by its associated algebra. Just to name a few, it is Koszul, Noetherian, reduced, Jacobson, and Cohen--Macaulay. We will then mention two applications of our work; one to algebraic geometry, and another to representation theory. For the first, we will show that the tableaux algebra is a flat degeneration of the algebra of global sections of the partial flag variety. For the second, we will show that this naive monoid structure of semistandard Young tableaux induces a crystal embedding when applied to the highest (or lowest) weight vectors. </p>
</div>


<div id="klein" style="display:none;" aria-hidden="true">
<p> In 2018, Hamaker and Reiner generalized the notions of weak order and descent sets from permutations to alternating sign matrices (ASMs).  As one associates a matrix Schubert variety to a permutation, one can more generally associate an intersection of matrix Schubert varieties (now called ASM varieties) to an ASM.  In this talk, we will review the role of matrix Schubert varieties - and their unions and intersections - in Schubert calculus and describe classical uses of the permutation matrices and strong Bruhat order in encoding algebro-geometric invariants.  We will then describe new work giving relationships between poset combinatorics and algebro-geometric invariants determined by the ASMs under weak order. This is joint work with Laura Escobar and Anna Weigandt.
 </p>
</div>


<div id="jackson" style="display:none;" aria-hidden="true">
<p> Machine learning (ML) and Artificial Intelligence (AI) are changing how mathematics research is done, and combinatorics is no exception. This talk will showcase some of the main concepts at the intersection of ML and combinatorics by discussing ongoing research on the q,t-Catalan numbers, a family of polynomials that refine the classical Catalan numbers. The q,t-Catalan numbers originally arose in the study of modules over the space of diagonal harmonics, but have since been realized combinatorially via pairs of statistics on Dyck paths. The two pairs of statistics that realize the q,t-Catalan numbers are (area, bounce) and (dinv, area), and there is a bijection on Dyck paths, called the zeta map, which maps area to dinv and bounce to area. The goal of this project is to use the well-understood zeta map as a proving ground for using ML to understand combinatorial bijections. We show not only that the machine can learn the zeta map, but also that its combinatorics can be extracted from the model. Using insights from the learned model, we provide a new combinatorial description of the zeta map.
 </p>
</div>

<div id="fillman" style="display:none;" aria-hidden="true">
<p> Periodic Schrödinger operators on graphs play an important role in mathematical physics, as they furnish models of crystals and photonic metamaterials. I will describe some recent results that connect combinatorial and topological aspects of the graph with the measure of the spectrum and spectral gaps.
 </p>
</div>

<div id="hamaker" style="display:none;" aria-hidden="true">
<p> Mu involutions interpolate between permutations and involutions. They index Borel orbits in the variety of complete quadrics, or equivalently certain subvarieties of the flag variety. I will discuss several of their Coxeter theoretic properties: strong and weak Bruhat order, an exchange lemma, atoms. Then I will explain a combinatorial recurrence for cohomology representatives of their associated orbits before concluding with some speculative remarks regarding Schubert calculus on the variety of complete quadrics. This is joint work with Jack Chou.
 </p>
</div>

<div id="griffin" style="display:none;" aria-hidden="true">
<p> 
The Stanley-Stembridge conjecture asserts that the chromatic symmetric functions for particular graphs are e-positive, meaning that they expand positively in the elementary symmetric function basis. Recently, Hikita proved this conjecture by guessing a remarkable formula for the e-expansion coefficients and then proving it satisfies a well-known recurrence. We give a second proof of Hikita's formula by direct algebraic methods involving the $A_{q,t}$ algebra of Carlsson and Mellit and localization formulas for parabolic flag Hilbert schemes. In fact, we obtain an expansion into Macdonald polynomials that involve an extra parameter $t$. Upon specializing t to different values, we obtain expansions into various bases of symmetric functions, including Hikita's elementary basis expansion.
</p>
<p>
This is joint work with Anton Mellit, Marino Romero, Kevin Weigl, and Joshua Jeishing Wen.
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
