The Macaulay2 Package Miura contains functions that compute divisor class group arithmetic for nonsingular curves. The package reduces computation in a divisor class group to that in the ideal class group via the isomorphism. The underlying quotient ring  should be over the ideal given by a nonsingular curve in the form of Miura.
Although computing two integral ideals is not hard, we need to obtain an ideal such that the shortest Groebner basis component is minimum
in order to obtain the representative of the ideal class. Although the basic  procedure is due to Arita,  the source code has become much shorter using MaCaulay2.
The package is useful not just for computation itself but also for understanding the divisor class group arithmetic from the ideal point of view.
