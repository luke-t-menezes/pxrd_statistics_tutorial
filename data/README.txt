# Example 1: Baseline fit of the a sample of Gd1.5Mn0.25Zr2.25O7 with the defect-fluorite structure type.

# Example 2: Decreasing the lattice parameter from 5.2 Å to 5.1 Å.
#            If the lattice parameter had increased which way would the peaks shift?

# Example 3: Decreasing the crystallite size.
#            The crystallite size in the calculated pattern is 10 nm.

# Example 4: Introduce preferred orientation in the crystallites.
#            One assumpetion in PXRD is that after you grind the sample all of the lattice planes are equally represented.
#            If some are displayed more than others than the peaks corresponding to those planes will have greater intensity

# Example 5: Swap out the elements in the unit cell
#            Here the Gd, Mn, Zr, and O in the unit cell have been swapped out with random other elements.
#            Gd (Z=64) -> Al (Z=13)
#            Mn (Z=25) -> I (Z=53)
#            Zr (Z=40) -> Be (Z=4)
#            O (Z=0) -> Gd (Z=64)

# Example 6: Lower symmetry
#            The original structure is face-centered cubic. The symmetry has been decreased to body-centered cubic.

# Example 7: Decrease the symmetry with a super-cell
#            The original unit cell is small, but high-symmetry.
#            We can check for long-range order by increasing the unit cell size and lowering the symmetry.

# Example 8: Highly-crystalline material and sharp peaks
#            The crystallite size has been increased to 1000 nm

# Example 9: Only fit Kα1 (exclude Kα2)
#            Lab X-rays from a Cu source are produced with two very similiar wavelengths,1.5406 Å (Kα1) and 1.5444 Å (Kα2).
#            Each produces their own set of diffraction peaks.
#            This is what it would look like if you exclude 1.5444 Å (Kα2) from the simulation.

# Example 10: Swap the elements in the unit cell with neighboring elements
#             Compare to example 5. All of the elements are still swapped,
#             but because the new elements have basically the same number of electrons they are pretty much indistinguishable in XRD.
#            Gd (Z=64) -> Eu (Z=63)
#            Mn (Z=25) -> Cr (Z=24)
#            Zr (Z=40) -> Y (Z=39)
#            O (Z=0) -> F (Z=9)