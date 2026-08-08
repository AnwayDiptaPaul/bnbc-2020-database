---
clause: "10.19.3.2"
title: "Torsional bracing"
chapter: "10"
chapter_title: "Steel Structures"
related_tables: []
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_6349b9.mmd"]
---
# Section 10.19.3.2: Torsional bracing

10.19.3.2 Torsional bracing
It is permitted to provide either nodal or continuous torsional bracing along the beam
length. It is permitted to attach the bracing at any cross-sectional location and it need not
be attached near the compression flange. The connection between a torsional brace and the
beam shall be able to support the required moment given below.
(a) Nodal bracing
The required bracing moment is
 =
Ê.Ê˜ "¢)
@Ð)Ð
(6.10.293)
The required cross-frame or diaphragm bracing stiffness is
m- =
,U
¯E VU
(6.10.294)
Chapter 10
Where,
m- = 1
{ ì2.4=

7:%
í (LRFD)
m- = | •
.˜)"¢©
'L”@Ð
©– (ASD)                                                                              (6.10.295)
m =
×.× '
/â ¯


+
 ±
(6.10.296)
Where,
{ = 0.75 (LRFD)
| = 3.00 (ASD)
$$L = span length, mm$$
n = number of nodal braced points within the span
$$E = modulus of elasticity of steel 200000 MPa$$
:% = out-of-plane moment of inertia, mm4
  = modification factor defined in Sec 10.6
 = beam web thickness, mm
 = web stiffener thickness, mm
 = stiffener width for one-sided stiffeners (use twice the individual stiffener width
for pairs of stiffeners), mm.
$$m- = brace stiffness excluding web distortion, N-mm/radian$$
m = web distortional stiffness, including the effect of web transverse stiffeners, if
any, N-mm/radian
For design according to Sec 10.2.3.3 (LRFD)
= required flexural strength using LRFD load combinations, N-mm
For design according to Sec 10.2.3.4 (ASD)
= required flexural strength using ASD load combinations, N-mm
If   m ž m-, Eq. 6.10.294 is negative, which indicates that torsional beam bracing will
not be effective due to inadequate web distortional stiffness.
Chapter 10
When required, the web stiffener shall extend the full depth of the braced member and shall
be attached to the flange if the torsional brace is also attached to the flange. Alternatively,
it shall be permissible to stop the stiffener short by a distance equal to 4  from any beam
flange that is not directly attached to the torsional brace. When =  is less than => then =
in Eq. 6.10.293 shall be permitted to be taken equal to =>.
(b) Continuous torsional bracing
$$For continuous bracing, use Equations 6.10.293, 6.10.294 and 6.10.296 with =/7 taken as$$
1.0 and = taken as =>; bracing moment and stiffness are given per unit span length. The
distortional stiffness for an unstiffened web is
m =

/â
(6.10.297)