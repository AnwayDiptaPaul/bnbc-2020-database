---
clause: "10.20.9.6"
title: "Column-beam moment ratio"
chapter: "10"
chapter_title: "Steel Structures"
related_tables: []
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_355bf8.mmd"]
---
# Section 10.20.9.6: Column-beam moment ratio

10.20.9.6 Column-beam moment ratio
The following relationship shall be satisfied at beam-to-column connections:
∗
∗> 1.0
(6.10.300)
∑
∗= the sum of the moments in the column above and below the joint at the
intersection of the beam and column centerlines. ∑
∗ is determined by summing the
projections of the nominal flexural strengths of the columns (including haunches where
used) above and below the joint to the beam centerline with a reduction for the axial force
in the column. It is permitted to take ∑
$$∗= ∑TÃ % −H $$
⁄
Ä (LRFD) or
∑TÃ % 1.5
⁄
−H 
⁄
Ä (ASD), as appropriate. When the centerlines of opposing beams
in the same joint do not coincide, the mid-line between centerlines shall be used.
∑
∗= the sum of the moments in the beams at the intersection of the beam and column
centerlines. ∑
∗ is determined by summing the projections of the expected flexural
strengths of the beams at the plastic hinge locations to the column centerline. It is permitted
to take ∑
$$∗= ∑Ã1.1J% %T + Ä (LRFD) or ∑$$
$$∗= ∑ð(1.1/1.5)J% %T +$$
ò (ASD), as appropriate. Alternatively, it is permitted to determine ∑
∗ consistent
with a prequalified connection design as designated in ANSI/AISC 358, or as otherwise
determined in a connection prequalification in accordance with Appendix N, or in a
program of qualification testing in accordance with Appendix Q. When connections with
reduced beam sections are used, it is permitted to take ∑
$$∗= ∑Ã1.1J% %T,!+ +$$
Ä (LRFD) or ∑
∗= ∑ð(1.1/1.5)J% %T,!+ + ò (ASD), as appropriate.
Where,

=  gross area of column, mm
% =  specified minimum yield stress of column, MPa
 = the additional moment due to shear amplification from the location of the plastic
hinge to the column centerline, based on ASD load combinations,
N-mm.
Chapter 10
  =  the additional moment due to shear amplification from the location of the
plastic hinge to the column centerline, based on LRFD load combinations, N-
mm
H   =  required compressive strength using ASD load combinations, (positive
number) N.
H   =  required compressive strength using LRFD load combinations, (positive
number) N
T  =  plastic section modulus of the beam, mm3
T
=  plastic section modulus of the column, mm3
T,!+  =  minimum plastic section modulus at the reduced beam section, mm3
Exception:
This requirement does not apply if either of the following two conditions is satisfied:
(a) Columns with H ž 0.3H for all load combinations other than  those determined
using  the  amplified  seismic  load  that  satisfy  either  of  the following:
(i) Columns used in a one-story building or the top story of a multistory building.
(ii) Columns where: (1) the sum of the available shear strengths of all exempted
columns in the story is less than 20 percent of the sum of the available shear
strengths of all moment frame columns in the story acting in the same direction;
and (2) the sum of the available shear strengths of all exempted columns on
each moment frame column line within that story is less than 33 percent of the
available shear strength of all moment frame columns on that column line. For
the purpose of this exception, a column line is defined as a single line of columns
or parallel lines of columns located within 10 percent of the plan dimension
perpendicular to the line of columns.
Where,
For design according to Specification Sec 10.2.3.3 (LRFD),
H =  %
, N
H = H, required compressive strength, using LRFD load combinations, N
Chapter 10
For design according to Specification Sec 10.2.3.4 (ASD),
H =  %
/1.5, N
H = H, required compressive strength, using ASD load combinations, N
(b) Columns in any story that has a ratio of available shear strength to required shear
strength that is 50 percent greater than the story above.