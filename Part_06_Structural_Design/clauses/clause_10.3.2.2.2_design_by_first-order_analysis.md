---
clause: "10.3.2.2.2"
title: "Design by first-order analysis"
chapter: "10"
chapter_title: "Steel Structures"
related_tables: ["../json/table_06_6.10.2..json", "../json/table_06_6.10.2.json", "../json/table_06_6.10.3..json", "../json/table_06_6.10.3.json", "../json/table_06_6.10.1.json"]
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_ba6dc7.mmd"]
---
# Section 10.3.2.2.2: Design by first-order analysis

10.3.2.2.2 Design by first-order analysis
Required strengths are permitted to be determined by a first-order analysis, with all
$$members designed using  K = 1.0, provided that$$
(a) The required compressive strengths of all members whose flexural stiffnesses are
considered to contribute to the lateral stability of the structure satisfy the following
limitation:
iH — 0.5H%
(6.10.9)
Where,
i = 1.0(LRFD)            α = 1.6 (ASD)
$$H= required axial compressive strength under LRFD or ASD load combinations$$
H%= member yield strength (= %), N.
(b) All load combinations include an additional lateral load, Ni , applied in combination
with other loads at each level of the structure, where
3 = 2.1 ¯
∆
)± S œ 0.0042S
(6.10.10)
$$Yi  = gravity load from the LRFD load combination or 1.6 times the ASD load$$
combination applied at level i, N
$$Δ/L = the maximum ratio of ∆ to L for all stories in the structure$$
∆ = first-order interstory drift due to the design loads, mm. Where ∆ varies over the
plan area of the structure, ∆ shall be average drift weighted in proportion to vertical
load or, alternatively, maximum drift.
$$L     = story height, mm$$
This additional lateral load shall be considered independently in two orthogonal
directions.
(c) The non-sway amplification of beam-column moments is considered by applying the
B1 amplifier of Sec10.3.2.1 to the total member moments.
10.4
Design of Members for Tension
This Section applies to steel members subject to axial tension caused by static forces acting
through the centroidal axis.
10.4.1
Slenderness Limitations
$$The maximum slenderness (<=/_)limit for design of structural members (except cables$$
and hanger rods) in tension shall be 300 unless it is justified by a comprehensive dynamic
analysis (including 2nd order effects if applicable) that a higher slenderness ratio is
satisfactory.
Chapter 10
Here,
== laterally unbraced length of the member, mm
_ = governing radius of gyration, mm
<= the effective length factor determined in accordance with Sec 10.3.2.
10.4.2
Tensile Strength
⁄
, of tension
members, shall be the lower value obtained according to the limit states of tensile yielding
in the gross section and tensile rupture in the net section.
(a) For tensile yielding in the gross section:
$$H =  %$$
(6.10.11)
(b) For tensile rupture in the net section:
$$H =  $$
(6.10.12)
Where,
$$V= effective net area, mm2$$
$$X = gross area of member, mm2$$
f  = specified minimum yield stress of the type of steel being used, MPa
$$^2  = specified minimum tensile strength of the type of steel being used, MPa$$
When members without holes are fully connected by welds, the effective net area used in
Eq.6.10.12 shall be as defined in Sec10.4.3. When holes are present in a member with
welded end connections, or at the welded connection in the case of plug or slot welds, the
effective net area through the holes shall be used in Eq.6.10.12.
10.4.3
Area Determination
10.4.3.1
Gross area
The gross area, Ag, of a member is the total cross-sectional area.
Chapter 10
10.4.3.2
Net area
The net area, An, of a member is the sum of the products of the thickness and the net width
of each element computed as follows:
In computing net area for tension and shear, the width of a bolt hole shall be taken as
2 mm greater than the nominal dimension of the hole.
For a chain of holes extending across a part in any diagonal or zigzag line, the net width of
the part shall be obtained by deducting from the gross width the sum of the diameters or
slot dimensions as provided in Sec10.10.3.2, of all holes in the chain, and adding, for each
gage space in the chain, the quantity s2/(4g)
Where,
s = longitudinal center-to-center spacing (pitch) of any two consecutive holes, mm.
g= transverse center-to-center spacing (gage) between fastener gage lines, mm.
For angles, the gage for holes in opposite adjacent legs shall be the sum of the gages from
the back of the angles less the thickness.
For slotted HSS welded to a gusset plate, the net area, An, is the gross area minus the product
of the thickness and the total width of material that is removed to form the slot.
In determining net area across plug or slot welds, the weld metal shall not be considered as
adding to net area.
10.4.3.3
Effective net area
The effective area of tension members shall be determined as follows:
$$Ae = AnU$$
(6.10.13)
Where, Q is the shear lag factor as obtained from Table 6.10.2.
Members such as single angles, double angles and WT sections shall have connections
proportioned such that U is equal to or greater than 0.60. Alternatively, a lesser value of U
is permitted if these tension members are designed for the effect of eccentricity in
accordance with Sections 10.8.1.2 or 10.8.2.
10.4.4
Built-Up Members
For limitations on the longitudinal spacing of connectors between elements in continuous
contact consisting of a plate and a shape or two plates, Sec10.10.3.5.
Either perforated cover plates or tie plates without lacing are permitted to be used on the
open sides of built-up tension members. Tie plates shall have a length not less than
two-thirds the distance between the lines of welds or fasteners connecting them to the
components of the member. The thickness of such tie plates shall not be less than
one-fiftieth of the distance between these lines. The longitudinal spacing of intermittent
welds or fasteners at tie plates shall not exceed 150 mm.
Chapter 10
Table 6.10.2:Shear Lag Factors for Connections to Tension Members
Case
Description of Element
Shear Lag Factor, U
Example
1
All tension members where the
tension load is transmitted directly to
each of cross-sectional elements by
fasteners or welds. (except as in
Cases 3, 4, 5 and 6)
$$U = 1.0$$
-
2
All tension members, except plates
and HSS, where the tension load is
transmitted to some but not all of the
cross-sectional elements by fasteners
or longitudinal welds (Alternatively,
for W, M, S and HP, Case 7 may be
used.)
$$Q = 1 −^3´/:$$
3
All tension members where the
tension load is transmitted by
transverse welds to some but not all
of the cross-sectional elements.
U = 1.0 and,
$$An = area of the$$
directly
connected
elements
-
4
Plates where the tension load is
transmitted by longitudinal welds
only.
$$I  \geq  2w … U = 1.0$$
$$2w > I  \geq  1.5w…U =$$
0.87
$$1.5w > I  \geq  w…U = 0.75$$
5
Round HSS with a single concentric
gusset plate
$$I  \geq  1.3D … U = 1.0$$
$$D  \leq  I < 1.3D …U = 1- ^3´ =$$
D/π
6
Rectangular
HSS
with
a
single
concentric
gusset
plate
$$I  \geq  H … U = 1 - ^3c/L$$
$$^3c =$$
2 + 22
4( + 2)
Chapter 10
Case
Description of Element
Shear Lag Factor, U
Example
With
two
side
gusset plates
$$I  \geq  H … U = 1 - ^3c/L$$
$$^3c =$$
2
4( + 2)
7
W, M, S or
HP Shapes or
Tees cut from
these shapes.
(If
U
is
calculated
per Case 2,
the
larger
value
is
permitted to
be used)
With
flange
connected with 3 or
more fasteners per
line in direction of
loading
$$bf   \geq   2/3d …U = 0.90$$
$$bf   \leq   2/3d…U = 0.85$$
-
With
web
connected with 4 or
more fasteners per
line in the direction
of loading
$$U = 0.70$$
-
8
Single angles
(If
U
is
calculated
per Case 2,
the
larger
value
is
permitted to
be used
With 4 or more
fasteners per line in
direction of loading
$$U = 0.80$$
-
With
2
or
3
fasteners per line in
the
direction
of
loading
$$U = 0.60$$
-
$$I = Length of connection, mm;$$
w = plate width, mm;
$$^3c = connection eccentricity, mm;$$
$$B = overall width of rectangular HSS member, measured 90o to the plane of the$$
connection, mm;
H = overall height of rectangular HSS member, measured in the plane of the connection,
mm
10.4.5
Pin-Connected Members
10.4.5.1
Tensile strength
The design tensile strength, tPn and the allowable tensile strength,
,
/
t
n
P

of
pin-connected members, shall be the lower value obtained according to the limit states of
tensile rupture, shear rupture, bearing, and yielding.
Chapter 10
(a) For tensile rupture on the net effective area:
P=2tbeffFu
(6.10.14)
ϕ¶  = 0.75 (LRFD)  Ω¶ = 2.00 (ASD)
(b) For shear rupture on the effective area:
P= 0.6FuAsf
(6.10.15)
{  = 0.75 (LRFD) Ω·¸ = 2.00 (ASD)
Where,
$$Asf = 2t(a+d/2), mm2$$
a = shortest distance from edge of the pin hole to the edge of the member
measured parallel to the direction of the force, mm
beff = 2t + 16, mm but not more than the actual distance from the edge of
the hole to the edge of the part measured in the direction normal to the
applied force
d = pin diameter, mm
t = thickness of plate, mm
(c) For bearing on the projected area of the pin, see Sec 10.10.7.
(d) For yielding on the gross-section, use Eq.6.10.11.
10.4.5.2
Dimensional requirements 1.33beff
The pin hole shall be located midway between the edges of the member in the direction
normal to the applied force. When the pin is expected to provide for relative movement
between connected parts while under full load, the diameter of the pin hole shall not be
more than 1 mm greater than the diameter of the pin.
The width of the plate at the pin hole shall not be less than (2beff + d) and the minimum
extension, a, beyond the bearing end of the pin hole, parallel to the axis of the member,
shall not be less than 1.33beff
The corners beyond the pin hole are permitted to be cut at 450 to the axis of the member,
provided the net area beyond the pin hole, on a plane perpendicular to the cut, is not less
than that required beyond the pin hole parallel to the axis of the member.
10.4.6
Eyebars
10.4.6.1
Tensile strength
The available tensile strength of eyebars shall be determined in accordance with Sec10.4.2,
with Ag taken as the cross-sectional area of the body.
Chapter 10
For calculation purposes, the width of the body of the eyebars shall not exceed eight times
its thickness.
10.4.6.2
Dimensional requirements
Eyebars shall be of uniform thickness, without reinforcement at the pin holes, and have
circular heads with the periphery concentric with the pin hole.
The radius of transition between the circular head and the eyebar body shall not be less
than the head diameter.
The pin diameter shall not be less than seven-eighths times the eyebar body width, and the
pin hole diameter shall not be more than 1 mm greater than the pin diameter.
For steels having Fy greater than 485 MPa, the hole diameter shall not exceed five times
the plate thickness and the width of the eyebar body shall be reduced accordingly.
A thickness of less than 13 mm is permissible only if external nuts are provided to tighten
pin plates and filler plates into snug contact. The width from hole edge to plate edge
perpendicular to the direction of applied load shall be greater than two-thirds and, for the
purpose of calculation, not more than three-fourths times the eyebar body width.
10.5
Design of Members for Compression
This Section addresses members subject to axial compression through the centroidal axis.
10.5.1
General Provisions
The design compressive strength, ϕºPn , and the allowable compressive strength, H |
⁄
,
are determined as follows:
The nominal compressive strength, Pn shall be the lowest value obtained according to the
limit states of flexural buckling, torsional buckling and flexural-torsional buckling.
For doubly symmetric and singly symmetric members the limit state of flexural buckling
is applicable.
For singly symmetric and unsymmetric members, and certain doubly symmetric members,
such as cruciform or built-up columns, the limit states of torsional or flexural-torsional
buckling are also applicable.
ϕ = 0.90 (LRFD)      Ω = 1.67 (ASD)
10.5.2
Slenderness Limitations and Effective Length
The effective length factor, K for calculation of column slenderness, KL/r, shall be
determined in accordance with Sec 10.3.
Where,
$$L = laterally unbraced length of the member, mm$$
r = governing radius of gyration, mm
K= the effective length factor determined in accordance with Sec 10.3.2.
Chapter 10
The maximum limit of slenderness, <= _
⁄ , for compression members shall be 150 unless
a comprehensive analysis including second order effects (including dynamic effects if any)
shows that a higher value is justified.
10.5.3
Compressive Strength for Flexural Buckling of Members without Slender
Elements
This Section applies to compression members with compact and non-compact sections, as
defined in Sec 10.2.4, for uniformly compressed elements.
The nominal compressive strength, H7, shall be determined based on the limit state of
flexural buckling.
$$H =  $$
(6.10.16)
The flexural buckling stress,  , is determined as follows:
(a) When
¬)
— 4.71‹
'
K”         (or    ≥ 0.44  % )
 = »0.658
¼”
¼£½  %
(6.10.17)
(b) When
¬)
> 4.71‹
'
K”         (or   ž 0.44  % )
Fer=0.877 Fe
(6.10.18)
Where,
  = elastic critical buckling stress determined according to Eq.6.10.19,
Sec 10.5.4, or the provisions of Sec 10.3.2, as applicable,
 =
«©'
¯¿À
¢ ±
©
(6.10.19)
10.5.4
Compressive Strength for Torsional and Flexural-Torsional Buckling of
Members without Slender Elements
This section applies to singly symmetric and unsymmetric members, and certain doubly
symmetric members, such as cruciform or built-up columns with compact and non compact
sections, as defined in Sec 10.2.4 for uniformly compressed elements. These provisions are
not required for single angles, which are covered in Sec 10.5.5.
Chapter 10
The nominal compressive strength, H, shall be determined based on the limit states of
flexural-torsional and torsional buckling, as follows:
$$H =  $$
(6.10.20)
For double-angle and tee-shaped compression members:
 = ¯
.
± »1 −‹1 −
©½
(6.10.21)
Where,
% is taken as   from Eq.6.10.17 or 6.10.18, for flexural buckling about the
y-axis of symmetry and
¬)
=
¬)
” , and
$ =
ÅN
©
(6.10.22)
For all other cases,   shall be determined according to Eq.6.10.17 or 6.10.18, using the
torsional or flexural-torsional elastic buckling stress,  determined as follows:
For doubly symmetric members:
 = È
(¬Â))© + 1;É

(6.10.23)
For singly symmetric members where y is the axis of symmetry:
 = ¯
.
± »1 −‹1 −
©½
(6.10.24)
For unsymmetric members,    is the lowest root of the cubic equation:
(  − &)Ã  − %Ä(  − $) − Ã  − %Ä ¯
&Ç
̅Ç±

− (  − &) ¯
%Ç
̅Ç±

= 0
(6.10.25)
Chapter 10
Where,

= gross area of member, mm2
 = warping constant, mm6
_̅Ê
 = eÊ
 + fÊ
 +
?Æ
(6.10.26)
2 = 1 −
̅Ç
©
(6.10.27)
& =
«©'
©
(6.10.28)
% =
«©'
•
¿”À
©
(6.10.29)
$ = ¯
(¬Â))© + 1;±

©
(6.10.30)
1 = shear modulus of elasticity of steel = 77200 MPa
:&, :% = moment of inertia about the principal axes, mm4
; = torsional constant, mm4
<$ =effective length factor for torsional buckling
$$eF, fF = coordinates of shear center with respect to the centroid, mm$$
$$_Fc =polar radius of gyration about the shear center, mm$$
_% =radius of gyration about y-axis, mm
10.5.5
Single Angle Compression Members
The nominal compressive strength, H , of single angle members shall be determined in
accordance with Sec 10.5.3 or Sec 10.5.7, as appropriate, for axially loaded members,
as well as those subject to the slenderness modification of Sec 10.5.5(a) or 10.5.5(b),
provided the members meet the criteria imposed.
The effects of eccentricity on single angle members are permitted to be neglected when the
members are evaluated as axially loaded compression members using one of the effective
slenderness ratios specified below, provided that: (1) members are loaded at the ends in
compression through the same one leg; (2) members are attached by welding or by
minimum two-bolt connections; and (3) there are no intermediate transverse loads.
Chapter 10
(a)
For equal-leg angles or unequal-leg angles connected through the longer leg that are
individual members or are web members of planar trusses with adjacent web
members attached to the same side of the gusset plate or chord:
(i) When     0 —
)
š — 80
¬)
= 72 +
š
(6.10.31)
(ii) When
)
š > 80
¬)
= 32 +
.Ì)
š
— 200
(6.10.32)
For unequal-leg angles with leg length ratios less than 1.7 and connected through the
shorter leg, KL/r from Eq.6.10.31 and Eq.6.10.32 shall be increased by adding 4
[(bl /bs )2  − 1], but KL/r of the members shall not be less than 0.95L/rz .
(b) For equal-leg angles or unequal-leg angles connected through the longer leg that are
web members of box or space trusses with adjacent web members attached to the
same side of the gusset plate or chord:
(i) When   0 —
)
š — 75
¬)
= 60 +
Ê.Í)
š
(6.10.33a)
(ii) When
)
š > 75
¬)
= 45 +
)
š — 200
(6.10.33b)
For unequal-leg angles with leg length ratios less than 1.7 and connected through the
shorter leg, KL/r from Eq.6.10.33a and 6.10.33b shall be increased by adding
6Î(	D 	
⁄
) −1Ï, but KL/r of the members shall not be less than 0.82L /rz .
Where,
=    = length of member between work points at truss chord centerlines, mm
$$D  = longer leg of angle, mm$$
  = shorter leg of angle, mm
_&  = radius of gyration about geometric axis parallel to connected leg, mm
_$  = radius of gyration for the minor principal axis, mm
Chapter 10
(c)
Single angle members with different end conditions from those described in Sections
10.5.5(a) or (b), with leg length ratios greater than 1.7, or with transverse loading
shall be evaluated for combined axial load and flexure using the provisions of Sec
10.8. End connection to different legs on each end or to both legs, the use of single
bolts or the attachment of adjacent web members to opposite sides of the gusset plate
or chord shall constitute different end conditions requiring the use of Sec 10.8
provisions.
10.5.6
Built-up Members
10.5.6.1
Compressive Strength
(a) The nominal compressive strength of built-up members composed of two or more
shapes that are interconnected by bolts or welds shall be determined in accordance
with Sections 10.5.3, 10.5.4, or 10.5.7 subject to the following modification. In lieu of
more accurate analysis, if the buckling mode involves relative deformations that
produce shear forces in the connectors between individual shapes, KL/r is replaced by
(KL/r)m  determined as follows:
(i) For intermediate connectors that are snug-tight bolted:
¯
¬)
±
= ‹¯
¬)
±
Ê

+ ¯

b±

(6.10.34)
(ii) For intermediate connectors that are welded or pretensioned bolted:
¯
¬)
±
= ‹¯
¬)
±
Ê

+ 0.82
¡©
(Á¡©) ¯

bÐ±

(6.10.35)
Where,
¯
¬)
±
= modified column slenderness of built-up member
¯
¬)
±
Ê= column slenderness of built-up member acting as a unit in the
buckling direction being considered
U
= distance between connectors, mm
_
= minimum radius of gyration of individual component, mm
_ = radius of gyration of individual component relative to its
centroidal axis parallel to member axis of buckling, mm
i
$$= separation ratio = ℎ/2_$$
2 =
distance
between
centroids
of
individual
components
perpendicular to the member axis of buckling, mm
Chapter 10
(b) The nominal compressive strength of built-up members composed of two or more
shapes or plates with at least one open side interconnected by perforated cover plates
or lacing with tie plates shall be determined in accordance with Sections 10.5.3, 10.5.4,
or 10.5.7 subject to modification given in Sec 10.5.6.1 (a).
10.5.6.2
Dimensional requirements
Individual components of compression members composed of two or more shapes shall be
connected to one another at intervals, a, such that the effective slenderness ratio [ _
⁄  of
each of the component shapes, between the fasteners, does not exceed three-fourths times
the governing slenderness ratio of the built-up member. The least radius of gyration,_,
shall be used in computing the slenderness ratio of each component part. The end
connection shall be welded or pre-tensioned bolted with Class A or B faying surfaces.
At the ends of built-up compression members bearing on base plates or milled surfaces, all
components in contact with one another shall be connected by a weld having a length not
less than the maximum width of the member or by bolts spaced longitudinally not more
than four diameters apart for a distance equal to 1 1
 times the maximum width of the
member.
Along the length of built-up compression members between the end connections required
above, longitudinal spacing for intermittent welds or bolts shall be adequate to provide for
the transfer of the required forces. For limitations on the longitudinal spacing of fasteners
between elements in continuous contact consisting of a plate and a shape or two plates, see
Sec 10.10.3.5. Where a component of a built-up compression member consists of an
outside plate, the maximum spacing shall not exceed the thickness of the thinner outside
plate times 0.75•  %
⁄
, nor 305 mm, when intermittent welds are provided along the
edges of the components or when fasteners are provided on all gage lines at each section.
When fasteners are staggered, the maximum spacing on each gage line shall not exceed the
thickness of thinner outside plate times  1.12•  %
⁄
nor 460 mm.
Open sides of compression members built up from plates or shapes shall be provided with
continuous cover plates perforated with a succession of access holes. The unsupported
width of such plates at access holes, as defined in Sec 10.2.4, is assumed to contribute to
the available strength provided the following requirements are met:
(1) The width-thickness ratio shall conform to the limitations of Sec 10.2.4.
(2) The ratio of length (in direction of stress) to width of hole shall not exceed two.
(3) The clear distance between holes in the direction of stress shall be not less than
the transverse distance between nearest lines of connecting fasteners or welds.
(4) The periphery of the holes at all points shall have a minimum radius of 38 mm.
As an alternative to perforated cover plates, lacing with tie plates is permitted at each end
and at intermediate points if the lacing is interrupted. Tie plates shall be as near the ends
as practicable. In members providing available strength, the end tie plates shall have a
Chapter 10
length of not less than the distance between the lines of fasteners or welds connecting them
to the components of the member. Intermediate tie plates shall have a length not less than
one-half of this distance. The thickness of tie plates shall be not less than one-fiftieth of the
distance between lines of welds or fasteners connecting them to the segments of the
members. In welded construction, the welding on each line connecting a tie plate shall total
not less than one-third the length of the plate. In bolted construction, the spacing in the
direction of stress in tie plates shall be not more than six diameters and the tie plates shall
be connected to each segment by at least three fasteners.
Lacing, including flat bars, angles, channels, or other shapes employed as lacing, shall be
$$so spaced that the =/_ ratio of the flange included between their connections shall not$$
exceed three-fourths times the governing slenderness ratio for the member as a whole.
Lacing shall be proportioned to provide a shearing strength normal to the axis of the
$$member equal to 2 percent of the available compressive strength of the member. The =/_$$
ratio for lacing bars arranged in single systems shall not exceed 140. For double lacing this
ratio shall not exceed 200. Double lacing bars shall be joined at the intersections. For lacing
bars in compression, =  is permitted to be taken as the unsupported length of the lacing bar
between welds or fasteners connecting it to the components of the built-up member for
single lacing, and 70 percent of that distance for double lacing.
For additional spacing requirements, see Sec 10.10.3.5.
10.5.7
Members with Slender Elements
This Section applies to compression members with slender sections, as defined in
Sec10.2.4 for uniformly compressed elements.
The nominal compressive strength, H, shall be determined based on the limit states of
flexural, torsional and flexural-torsional buckling.
H7 =  Ñ_X
(6.10.36)
When
¬)
— 4.71‹
'
ÒK”             (or   œ 0.44 I %)
 = I »0.658
Ó¼”
¼£ ½  %
(6.10.37)
When
¬)
> 4.71‹
'
ÒK”              (or   ž 0.44 I %)
 = 0.877 
(6.10.38)
Chapter 10
Where,
 = elastic critical buckling  stress, calculated using Eq.6.10.19 and 6.10.23 for
doubly symmetric members, Eq.6.10.19 and 6.10.24 for singly symmetric
members, and Eq.6.10.25 for unsymmetric members, except for single angles
where Fe is calculated using Eq.6.10.19.
I =1.0 for members with compact and noncompact sections, as defined in Sec 10.2.4,
for uniformly compressed elements.
= II for members with slender-element sections, as defined in Sec 10.2.4, for
uniformly compressed elements.
10.5.7.1
Slender unstiffened elements,
s
Q
The reduction factor Ifor slender unstiffened elements is defined as follows:
(a) For flanges, angles, and plates projecting from rolled columns or other compression
members:
When

'
K”
I = 1.0
(6.10.39)
When 0.56•  %
⁄
ž 	 
⁄ ž 1.03•  %
⁄
I = 1.415 −0.74 ¯

K”
'
(6.10.40)
When 	 
⁄ œ 1.03•  %
⁄
I =
›±
©
(6.10.41)
(b) For flanges, angles, and plates projecting from built-up columns or other compression
members:
When

'Ö’
K”
I = 1.0
(6.10.42)
Chapter 10
When  0.64‹
'Ö’
K” ž 	 
⁄ — 1.17‹
'Ö’
K”
I = 1.415 −0.65 ¯

K”
'Ö’
(6.10.43)
When

'Ö’
K”
I =
›±
©
(6.10.44)
Where,[ =
˜
⁄
, and shall not be taken less than 0.35 nor greater than 0.76 for
calculation purposes.
(c) For single angles
When

'
K”
I = 1.0
(6.10.45)
When 0.45•  %
⁄
ž 	 
⁄ — 0.91•  %
⁄
I = 1.34 −0.76 ¯

K”
'
(6.10.46)
When 	 
⁄ > 0.91•  %
⁄
I =
›±
©
(6.10.47)
Where,	 = full width of longest angle leg, mm
(d) For stems of tees
When

'
K”
I = 1.0
(6.10.48)
Chapter 10
When 0.75‹
'
K” ž  
⁄ — 1.03‹
'
K”
I = 1.908 −1.22 ¯

K”
'
(6.10.49)
When  
⁄ > 1.03‹
'
K”
I =
›±
©
(6.10.50)
Where,
= width of unstiffened compression element, as defined in Sec 10.2.4, mm
 = the full nominal depth of tee, mm
 = thickness of element, mm
10.5.7.2
Slender unstiffened elements,
s
Q
The reduction factor, I, for slender stiffened elements is defined as follows:
I =
?
(6.10.51)
A
= total cross-sectional area of member, mm2
 = summation of effective areas of the cross section based on the reduced
effective width, 	, mm2.
The reduced effective width, 	, is determined as follows:
(a) For  uniformly  compressed  slender  elements,  with

'
 ,  except flanges
of square and rectangular sections of uniform thickness:
 = 1.92‹
'
 Û1 −
⁄ ) ‹
'
Ü —
(6.10.52)
Where,W is taken as   with    calculated based on Q = 1.0.
Chapter 10
(b) For flanges of square and rectangular slender-element sections of uniform thickness
with

'

 = 1.92‹
'
 Û1 −
⁄ ) ‹
'
Ü —
(6.10.53)
$$Where W = H $$
⁄
(c) For axially-loaded circular sections:
When  0.11
'
K” ž

'
K”
$$I = I =$$
⁄ ) +

×
(6.10.54)
Where,
= outside diameter, mm
 = wall thickness, mm
10.6
Design of Members for Flexure
This Section applies to members subject to simple bending about one principal axis. For
simple bending, the member is loaded in a plane parallel to a principal axis that passes
through the shear center or is restrained against twisting at load points and supports. The
general provisions are provided in Sec 10.6.1. Various Section properties of members are
provided in Table 6.10.3.
10.6.1
General Provisions
The design flexural strength,{, and the allowable flexural strength, Ω
⁄
,shall be
determined as follows:
(a) For all provisions in this Sec 10.6
{  = 0.90 (LRFD)
Ω  = 1.67 (ASD)
And, the nominal flexural strength,, shall be determined according to Sections
10.6.2 to 10.6.12.
Chapter 10
(b) The provisions in this Chapter are based on the assumption that points of support for
beams and girders are restrained against rotation about their longitudinal axis.
The following terms are common to the Equations in this Chapter except where noted:
  = lateral-torsional buckling modification factor for non-uniform moment diagrams
when both ends of the unsupported segment are braced
 =
.Ì" Ýš
.Ì" ÝšÁ×"ÞÁ˜"ßÁ×"à J — 3.0
(6.10.55)
Where,
&  = absolute value of maximum moment in the unbraced segment, N-
mm
? = absolute value of moment at quarter point of the unbraced segment,
N-mm
! = absolute value of moment at centerline of the unbraced segment,
N-mm
@ = absolute value of moment at three-quarter point of the unbraced
segment, N-mm
$$J = cross-section monosymmetry parameter$$
= 1.0, doubly symmetric members
= 1.0, singly symmetric members subjected to single curvature
bending
= 0.5 + 2 •
L”’
L” –

, singly symmetric members subjected to reverse
curvature bending
:% = moment of inertia about the principal y-axis, mm4
:% = moment of inertia about y-axis referred to the compression flange,
or if reverse curvature bending, referred to the smaller flange, mm4
Chapter 10
In singly symmetric members subjected to reverse curvature bending, the lateral- torsional
buckling strength shall be checked for both flanges. The available flexural strength shall
be greater than or equal to the maximum required moment causing compression within the
flange under consideration.
Cb is permitted to be conservatively taken as 1.0 for all cases. For cantilevers or overhangs
where the free end is unbraced, Cb = 1.0.
Table 6.10.3: Section Types and Selection Table for the Application of Sub-sections
of Sec 10.6
Sub-
Section in
this
provision
Cross Section
Flange
Slenderness
Web
Slenderness
Limit
States
10.6.2
C
C
Y,LTB
10.6.3
NC, S
C
LTB, FLB
10.6.4
C, NC, S
C, NC
Y, LTB,
FLB, TFY
10.6.5
C, NC, S
S
Y, LTB,
FLB, TFY
10.6.6
C, NC, S
N/A
Y, FLB
10.6.7
C, NC, S
C, NC
Y, FLB,
WLB
10.6.8
N/A
N/A
Y, LB
Chapter 10
Sub-
Section in
this
provision
Cross Section
Flange
Slenderness
Web
Slenderness
Limit
States
10.6.9
C, NC, S
N/A
Y, LTB,
FLB
10.6.10
N/A
N/A
Y, LTB,
LLB
10.6.11
N/A
N/A
Y, LTB
10.6.12
Unsymmetrical
shapes
N/A
N/A
All limit
states
Y = yielding, LTB = lateral-torsional buckling, FLB = flange local buckling,
WLB = web local buckling, TFY = tension flange yielding, LLB = leg local buckling,
$$LB = local buckling, C = compact, NC = noncompact, S = slender$$
10.6.2
Doubly Symmetric Compact I-Shaped Members and Channels Bent about
their Major Axis
This Section applies to doubly symmetric I-shaped members and channels bent about their
major axis, having compact webs and compact flanges as defined in Sec10.2.4.
The nominal flexural strength,, shall be the lower value obtained according to the limit
states of yielding (plastic moment) and lateral-torsional buckling.
10.6.2.1
Yielding
 =  =  %T&
(6.10.56)
Where,
% = specified minimum yield stress of the type of steel being used, MPa
T&  = plastic section modulus about the x-axis, mm3
Chapter 10
10.6.2.2
Lateral –torsional buckling
(a)  When =≤=, the limit state of lateral-torsional buckling does not apply.
(b) When =<=≤ =
 =  Û −Ã −0.7 %O&Ä •
)ÐE)“
)¢E)“–Ü — 
(6.10.57)
(c) When  =>=
 =  O& — 
(6.10.58)
Where,
=  = length between points that are either braced against lateral displacement of
compression flange or braced against twist of the cross section, mm
 =
¯
ÀÐ
© ‹1 + 0.078
N
+š/Ç ¯
)Ð
›á±

(6.10.59)
And where,
= modulus of elasticity of steel = 200000 MPa
;
= torsional constant, mm4
O& = elastic section modulus taken about the x-axis, mm3
The limiting lengths =and =are determined as follows:
= = 1.76_%‹
'
K”
(6.10.60)
'
N
+š/â
ã1 + ‹1 + 6.76 ¯
'
+š/â
N ±

(6.10.61)
Where,
 =
+š
(6.10.62)
And,
For a doubly symmetric I-shape: c = 1
(6.10.63a)
For a channel: Ñ =
/â
 ‹
L”
@™
(6.10.63b)
Where, ho = distance between the flange centroids, mm
Chapter 10
10.6.3
Doubly Symmetric I-Shaped Members with Compact Webs and Noncompact
or Slender Flanges Bent about their Major Axis
This Section applies to doubly symmetric I-shaped members bent about their major axis
having compact webs and noncompact or slender flanges as defined in Sec10.2.4.
The nominal flexural strength, , shall be the lower value obtained according to the limit
states of lateral-torsional buckling and compression flange local buckling.
10.6.3.1
Lateral –torsional buckling
For lateral-torsional buckling, the provisions of Sec 10.6.2.2 shall apply.
10.6.3.2
Compression flange local buckling
(a) For sections with noncompact flanges
 = Û −Ã −0.7 %O&Ä •
(6.10.64)
(b) For sections with slender flanges
 =
ä©
(6.10.65)
Where,
x = 	
2
x = xis the limiting slenderness for a compact flange, Table 6.10.1
x = xis the limiting slenderness for a noncompact flange, Table 6.10.1
[ =
˜
⁄
and shall not be taken less than 0.35 nor greater than 0.76 for
calculation purposes
10.6.4
Other I-Shaped Members with Compact or Noncompact Webs Bent about
their Major Axis
This Section applies to: (a) doubly symmetric I-shaped members bent about their major
axis with noncompact webs; and (b) singly symmetric I-shaped members with webs
attached to the mid-width of the flanges, bent about their major axis, with compact or
noncompact webs, as defined in Section 10.2.4.
Chapter 10
The nominal flexural strength, , shall be the lowest value obtained according to the limit
states of compression flange yielding, lateral-torsional buckling, compression flange local
buckling and tension flange yielding.
10.6.4.1
Compression flange yielding
 = J% = J %O&
(6.10.66)
10.6.4.2
Lateral-torsional buckling
(a) When = ≤ = , the limit state of lateral-torsional buckling does not apply.
(b) When =<=  ≤ =
 =  ÛJ% −ÃJ% − )O&Ä •
)ÐE)“
J%
(6.10.67)
(c) When =>=
 =  O& — J%
(6.10.68)
Where
% =  %O&
(6.10.69)
 =
¯
ÀÐ
¢›±
© ‹1 + 0.078
N
)Ð
›±

(6.10.70)
For,
L”’
L” — 0.23, J shall be taken as zero.
The stress,  ), is determined as follows:
(i) For
+š›
+š’ œ 0.7
) = 0.7 %
(6.10.71a)
(ii) For
åæç
åæè ž 0.7
) =  %
+š›
+š’ œ 0.5 %
(6.10.71b)
Chapter 10
The limiting laterally unbraced length for the limit state of yielding, = is,
'
K”
(6.10.72)
The limiting unbraced length for the limit state of inelastic lateral-torsional buckling, =, is
'
KÀ ‹
N
ã1 + ‹1 + 6.76 ¯
KÀ
'
N ±

(6.10.73)
The web plastification factor, J, is determined as follows:
(i) For
/’
J =
"“
"”’
(6.10.74a)
(ii) For
/’
J = Û
"“
"“
"“
"”’
(6.10.74b)
Where
 = T& % — 1.6O& %
flanges, respectively, mm3
x    = ℎ

x = x limiting slenderness for a compact web, Table 6.10.1
x = x limiting slenderness for a noncompact web, Table 6.10.1
Chapter 10
The effective radius of gyration for lateral-torsional buckling, rt , is determined as follows:
(i) For I-shapes with a rectangular compression flange:
Ù’
ê™
é©
(6.10.75)
Where,
U =
(6.10.76)
=compression flange width, mm
= compression flange thickness, mm
(ii) For I-shapes with channel caps or cover plates attached to the compression flange:
the web area in compression due to application of major axis bending moment alone, mm
U = the ratio of two times the web area in compression due to application of major axis
bending moment alone to the area of the compression flange components.
10.6.4.3
Compression flange local buckling
(a) For sections with compact flanges, the limit state of local buckling does not apply.
(b) For sections with noncompact flanges
 = ÛJ% −ÃJ% − )O&Ä •
(6.10.77)
(c) For sections with slender flanges
 =
ä©
(6.10.78)
Where,
) is defined in Eq. 6.10.71a and Eq. 6.10.72b
Chapter 10
J = is the web plastification factor, determined by Eq. 6.10.74
[ =
˜
⁄
and shall not be taken less than 0.35 nor greater than 0.76 for
calculation purposes
x = 	
2
x = x limiting slenderness for a compact flange, Table 6.10.1
x = x limiting slenderness for a noncompact flange, Table 6.10.1
10.6.4.4
Tension flange yielding
(6.10.79)
Where,
is determined as follows:
(i) For
/’
"“
"”›
(6.10.80a)
(ii) For
/’
"“
"“
"“
"”›
(6.10.80b)
Where,
x    = ℎ

x = x , the limiting slenderness for a compact web, defined in Table
6.10.1
x = x , the limiting slenderness for a noncompact web, defined in Table
6.10.1
Chapter 10
10.6.5
Doubly Symmetric and Singly Symmetric I-Shaped Members with Slender
Webs Bent about Major Axis
This Section applies to doubly symmetric and singly symmetric I-shaped members with
slender webs attached to the mid-width of the flanges, bent about their major axis, as
defined in Sec10.2.4.
The nominal flexural strength , shall be the lowest value obtained according to the limit
states of compression flange yielding, lateral-torsional buckling, compression flange local
buckling and tension flange yielding.
10.6.5.1
Compression flange yielding
 = J
%O&
(6.10.81)
10.6.5.2
Lateral-torsional buckling
 = J
O&
(6.10.82)
(a) When =  ≤ = , the limit state of lateral-torsional buckling does not apply.
(b) When =<= ≤ =
 =  Û % −Ã0.3 %Ä •
)ÐE)“
)¢E)“–Ü —  %
(6.10.83)
(c) When =>=
 =
¯
ÀÐ
¢›±
© —  %
(6.10.84)
Where,
= is defined by Eq.6.10.72
'
(6.10.85)
J
is the bending strength reduction factor:
J
= 1 −
™
/’
'
K”í — 1.0
(6.10.86)
U is defined by Eq.6.10.76 but shall not exceed 10 and
10.6.5.3
Compression flange local buckling
Chapter 10
 = J
O&
(6.10.87)
(a) For sections with compact flanges, the limit state of compression flange local
buckling does not apply.
(b) For sections with noncompact flanges
 = Û % −Ã0.3 %Ä •
(6.10.88)
(c) For sections with slender flanges
 =
ì
ÐÙ
©
(6.10.89)
Where,
[ =
˜
⁄
, and shall not be taken less than 0.35 nor greater than 0.76 for
calculation purposes
x = 	
2
x = x , the limiting slenderness for a compact flange, Table 6.10.1
x = x , the limiting slenderness for a noncompact flange, Table 6.10.1
10.6.5.4
Tension flange yielding
(6.10.90)
10.6.6
I-Shaped Members and Channels Bent about Their Minor Axis
This Section applies to I-shaped members and channels bent about their minor axis.
The nominal flexural strength, , shall be the lower value obtained according to the limit
states of yielding (plastic moment) and flange local buckling.
10.6.6.1
Yielding
Chapter 10
 =  =  %T% — 1.6 %O%
(6.10.91)
10.6.6.2
Flange local buckling
(a) For sections with compact flanges the limit state of yielding shall apply.
(b) For sections with noncompact flanges
 = Û −Ã −0.7 %O%Ä •
(6.10.92)
(c) For sections with slender flanges
 =  O%
(6.10.93)
Where,
 =
ì
ÐÙ
©
(6.10.94)
x =

x = x , the limiting slenderness for a compact flange, Table 6.10.1
x = x , the limiting slenderness for a noncompact flange, Table
6.10.1
O%for a channel shall be taken as the minimum section modulus
10.6.7
Square and Rectangular HSS and Box-Shaped Members
This section applies to square and rectangular HSS, and doubly symmetric box-shaped
members bent about either axis, having compact or noncompact webs and compact,
noncompact or slender flanges as defined in Sec10.2.4.
The nominal flexural strength, , shall be the lowest value obtained according to the limit
states of yielding (plastic moment), flange local buckling and web local buckling under
pure flexure.
Chapter 10
10.6.7.1
Yielding
 =  =  %Z
(6.10.95)
Where,
$$Z = plastic section modulus about the axis of bending, mm3$$
10.6.7.2
Flange local buckling
(a) For compact sections, the limit state of flange local buckling does not apply.
(b) For sections with noncompact flanges
 =  −Ã − %OÄ ì3.57

K”
' −4.0í — 
(6.10.96)
(b) For sections with slender flanges
 =  %O
(6.10.97)
Where, Ois the effective section modulus determined with the effective
width of the compression flange taken as:
 = 1.92‹
'
K” Û1 −
⁄ ‹
'
(6.10.98)
10.6.7.3
Web local buckling
(a) For compact sections, the limit state of web local buckling does not apply.
(b) For sections with noncompact webs
 =  −Ã − %O&Ä ì0.305
/
K”
' −0.738í —  (6.10.99)
10.6.8
Round HSS
This Section applies to round HSS having D/t ratios of less than
K”
The nominal flexural strength, , shall be the lower value obtained according to the limit
states of yielding (plastic moment) and local buckling.
Chapter 10
10.6.8.1
Yielding
 =  =  %Z
(6.10.100)
10.6.8.2
Local buckling
(a) For compact sections, the limit state of flange local buckling does not apply.
(b) For noncompact sections
 = ì
Ê.Ê'
ï
›
+  %íO
(6.10.101)
(b) For sections with slender walls
 =  O
(6.10.102)
Where,
 =
ï
›
(6.10.103)
$$S= elastic section modulus, mm3$$
10.6.9
Tees and Double Angles Loaded in the Plane of Symmetry
This Section applies to tees and double angles loaded in the plane of symmetry.The
nominal flexural strength, Mn, shall be the lowest value obtained according to the limit
states of yielding (plastic moment), lateral-torsional buckling and flange local buckling.
10.6.9.1
Yielding
 = 
(6.10.104)
Where,
 =  %T&  — 1.6% for stems in tension
(6.10.105)
— % for stems in compression
(6.10.106)
10.6.9.2
Lateral-torsional buckling
 =  =
)Ð
ð + √1 + ò
(6.10.107)
Where,
$$ = ±2.3 ¯$$

L”
N
(6.10.108)
The plus sign for B applies when the stem is in tension and the minus sign applies when
the stem is in compression. If the tip of the stem is in compression anywhere along the
unbraced length, the negative value of B shall be used.
Chapter 10
10.6.9.3
Flange local buckling of tees
 =  O&
(6.10.109)
O& is the elastic section modulus referred to the compression flange.
  is determined as follows:
(a) For compact sections, the limit state of flange local buckling does not apply.
(b) For noncompact sections
 =  % ì1.19 −0.50 •
Ù
K”
' í
(6.10.110)
(c) For slender sections
 =
ì
ÐÙ
©
(6.10.111)