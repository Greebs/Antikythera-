# Antikythera-
Sononumeric Explorer

**tl;dr**

Antikythera reveals that the integers within any octave interval form a closed system under multiplication, with exactly two non-arbitrary landmarks — the identity and √2 — that organize the entire space. √2 is simultaneously the geometric mean of the octave, the point of maximum harmonic tension, and the exact frequency ratio of the tritone, meaning its ancient reputation as the *diabolus in musica* is a direct mathematical consequence of its position. Every composite integer in this space is an interference pattern of its prime factors, every product folds back into the same interval, and the entire multiplicative structure of an octave can be rendered as a continuous, navigable geometry in which every element is related to every other by the same underlying symmetry.

**Antikythera — Sononumeric Explorer**

Antikythera is an interactive mathematical visualizer built on an original framework for understanding multiplicative structure within bounded integer intervals.

**The Core Mathematics**

The integers in any octave — the interval [2^N, 2^(N+1)) — form a closed system under multiplication when octave reduction is applied. Octave reduction means: multiply two values, then divide or multiply by 2 until the result falls back into the same interval. This is modular arithmetic on logarithms — addition mod 1 in log₂ space — because log₂ converts multiplication into addition, and the octave boundary acts as the modulus.

The result is that an entire multiplication table folds into a finite, navigable square. Every product lands back in the same octave. The structure is closed, complete, and visually tractable.

**The Two Landmarks**

Within this space, there are exactly two non-arbitrary positions. The identity — the octave boundary, 2 — sits at log₂ = 0. The inflection point — √2, the geometric mean of the octave boundaries — sits at log₂ = 0.5. It is symmetric under the map x ↦ 2/x, its own octave complement, and the point of maximum harmonic tension and product density. Everything between them is a continuous gradient. The colour coding in Antikythera runs between these two points because they are the only honest anchors in the space — everything else would be arbitrary.

In music, this inflection point is the tritone — the interval that divides the octave exactly in half, the only interval that is its own inversion. Its historical designation as *diabolus in musica* reflects its position as the point of maximum distance from the identity in log₂ space. Antikythera makes this structural pivot visible and navigable.

**The Matrix**

The product matrix is the central object. Each cell holds the octave-reduced product of a row value and a column value. The colour at each cell encodes where in the octave that product sits — running from identity (blue) through inflection (orange). Animating through the rows produces coherent, continuous motion because sub-integer interpolation traces smooth paths through the multiplicative structure. The matrix is not a lookup table — it is a map of an arithmetic landscape.

**The Views**

Each view in Antikythera is a different projection of the same underlying data.

The **Phase** view animates the matrix row by row as a chord diagram — each integer mapped to an angle by its fractional log₂, with products drawn as midpoints between source and target angles. The geometry is not decorative: angular position encodes ratio, not magnitude.

The **Reticulum** superimposes all frames simultaneously, revealing the full multiplicative orbit — the complete set of paths traced by a given function through the octave.

The **Zoetrope** renders the structure on a three-dimensional torus in WebGL. The major circle sweeps through animation frames; the minor circle encodes product position within the octave. The torus topology is not arbitrary — the two-dimensional periodicity of the space genuinely has that shape. Particle size scales with inflection proximity, making the colour gradient and the size gradient reinforce the same information.

The **Antikythera** view is a product-angle calculator: nodes placed at positions in the octave, with products computed between them in real time. Moving one node shifts all products simultaneously.

The **Atlas** view is a prime composition wheel, encoding the omega order — the number of prime factors — of each integer through colour, revealing how composite structure distributes across the octave.

**What It Reveals**

Prime integers appear as irreducible points — no internal structure, no interference. Composite integers are interference patterns: their position is accumulated phase, their omega order is the number of constituent waves. The chord diagrams produce caustics. The midpoint loci of inverse functions produce Möbius-like structure. These are not visual artifacts — they are properties of the arithmetic made visible by the framework.

The deeper claim of Antikythera is that the octave is not merely a musical convenience but a natural boundary with genuine geometric content. The identity and the inflection point organize everything within it. The gradient between them is the only continuous, geometrically meaningful colouring of the space. And every integer in the octave is related to every other by the same underlying symmetry — which is what the maxim means:

*"Every tree is every other tree."*
