# The Sharp Tail of Uniform Stability

## Abstract

Uniform stability controls how much one training example can change the loss at any test point. A new logarithmic-free upper bound shows that a $\gamma$-uniformly stable algorithm with loss in $[0,L]$ has generalization gap at most 

$$O\\!\left(\gamma\log(1/\delta) +L\sqrt{\frac{\log(1/\delta)}{n}}\right)$$

 with probability $1-\delta$. Whether an actual bounded-loss learning algorithm can realize the linear dependence on $\log(1/\delta)$ has remained open. The known construction realizes it only for auxiliary weakly dependent random variables whose pointwise range grows with $n$. The known learning lower bound holds only at constant probability. We close this gap. For every $n$, stability level $\gamma$, and loss bound $L$, we construct one deterministic $\gamma$-uniformly stable learning problem whose tail satisfies, simultaneously for $1\le p\le c n$, 

$$\mathbb P\\!\left( R(A_S)-R_S(A_S) \ge c'\min\\!\left\\{L,\gamma p+L\sqrt{p/n}\right\\} \right)\ge e^{-p}.$$

 The construction is ordinary bounded absolute-loss regression with constant labels. Its key is a multiscale collection of rare Rademacher features. A coordinatewise ramp is stable in sup norm, while an odd symmetrized maximum converts a unique extreme feature into a gap of order $\gamma p$ without violating the loss bound. Geometrically spaced ramps put all confidence levels into the same problem. Together with the logarithmic-free upper bound, this determines the optimal high-probability and moment dependence of uniform stability up to universal constants.

## Contributions

- We give the first bounded-loss uniformly stable learner with an
$\Omega(\gamma\log(1/\delta))$ high-probability generalization gap.
- A single problem realizes
$\Omega(\min\\{L,\gamma p+L\sqrt{p/n}\\})$ simultaneously for all $1\le p\le cn$.
Consequently, the moment upper bound in is sharp for actual learning algorithms.
- The construction uses deterministic learning and standard absolute regression loss. We prove
uniform stability over all replacement datasets, not only on the high-probability event.

## Keywords

uniform stability, generalization bounds, lower bounds, moment inequalities, concentration, high-probability bounds, learning theory

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
