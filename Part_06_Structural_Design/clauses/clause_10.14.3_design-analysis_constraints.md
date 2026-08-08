---
clause: "10.14.3"
title: "Design-Analysis Constraints"
chapter: "10"
chapter_title: "Steel Structures"
related_tables: []
related_diagrams: []
related_flowcharts: []
---
# Section 10.14.3: Design-Analysis Constraints

10.14.3 Design-Analysis Constraints
(1) The second-order analysis shall consider both P -δ and P -Δ effects. It is permitted to
perform the analysis using any general second-order analysis method, or by the
amplified first-order analysis method of Sec 10.3.2, provided that the B1 and B2
Chapter 10
factors are based on the reduced stiffnesses defined in Eq. 6.10.263 and 6.10.264.
Analyses shall be conducted according to the design and loading requirements
specified in either Sec 10.2.3.3 (LRFD) or Sec 10.2.3.4 (ASD). For ASD, the second-
order analysis shall be carried out under 1.6 times the ASD load combinations and the
results shall be divided by 1.6 to obtain the required strengths.
Methods of analysis that neglect the effects of P - δ  on the lateral displacement of
the structure are permitted where the axial loads in all members whose flexural
stiffnesses are considered to contribute to the lateral stability of the structure satisfy
the following limit:
iH ž 0.15 H)
(6.10.262)
Where,
H = required axial compressive strength under LRFD or ASD load combinations,
N
$$H) = ë:/= evaluated in the plane of bending$$
And, i = 1.0 (LRFD)   α = 1.6 (ASD)
(2) A notional load, 3 = 0.002S, applied independently in two orthogonal directions,
shall be applied as a lateral load in all load combinations. This load shall be in addition
to other lateral loads, if any,
Where,
3 = notional lateral load applied at level , N
S = gravity load from LRFD load combination or 1.6 times the ASD load
combination applied at level i, N
The notional load coefficient of 0.002 is based on an assumed initial story out-of-
plumbness ratio of 1/500. Where a smaller assumed out-of-plumbness is justified, the
notional load coefficient may be adjusted proportionally.
For frames where the ratio of second-order drift to first-order drift is equal to or less
than 1.5, it is permissible to apply the notional load, Ni , as a minimum lateral load for
the gravity-only load combinations and not in combination with other lateral loads.
Chapter 10
For all cases, it is permissible to use the assumed out-of-plumbness geometry in the
analysis of the structure in lieu of applying a notional load or a minimum lateral load
as defined above.
(3) A reduced flexural stiffness, :∗,
:∗= 0.8>:
(6.10.263)
shall be used for all members whose flexural stiffness is considered to contribute to
the lateral stability of the structure,
Where,
: = moment of inertia about the axis of bending, mm4
$$> = 1.0 for iH/H% — 0.5$$
= 4ðiH H%Ã1 −iH H%
⁄
Ä
⁄
ò for iH/H% > 0.5
$$H  = required axial compressive strength under LRFD or ASD load combinations, N$$
H% =  %, member yield strength, N
And α = 1.0 (LRFD)   α = 1.6 (ASD)
In lieu of using > ž 1.0, where, iH/H% > 0.5, > = 1.0 may be used for all
members, provided that an additive notional load of 0.001Yi   is added to the notional
load required in (2).
(4) A reduced axial stiffness, EA*,
∗= 0.8 
(6.10.264)
shall be used for members whose axial stiffness is considered to contribute to the
lateral stability of the structure, where A is the cross-sectional member area.
Chapter 10
10.15
Inelastic Analysis and Design