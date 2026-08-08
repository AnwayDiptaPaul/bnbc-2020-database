---
clause: "10.2.3.13.2"
title: "Net area"
chapter: "10"
chapter_title: "Steel Structures"
related_tables: ["../json/table_06_6.10.1..json", "../json/table_06_6.10.1.json"]
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_42eac9.mmd"]
---
# Section 10.2.3.13.2: Net area

10.2.3.13.2 Net area
The net area, of a member is the sum of the products of the thickness and the net width
of each element computed as follows:
In computing net area for tension and shear, the width of a bolt hole shall be taken as 2 mm
greater than the nominal dimension of the hole.
For a chain of holes extending across a part in any diagonal or zigzag line, the net width of
the part shall be obtained by deducting from the gross width the sum of the diameters or
slot dimensions as provided in Sec 10.10.3.2, of all holes in the chain, and adding, for each
gage space in the chain, the quantitys (4X)
⁄
.
Where,
s = longitudinal center-to-center spacing (pitch) of any two consecutive holes, mm.
g = transverse center-to-center spacing (gage) between fastener gage lines, mm.
For angles, the gage for holes in opposite adjacent legs shall be the sum of the gages from
the back of the angles less the thickness.
For slotted HSS welded to a gusset plate, the net area, , is the gross area the product of
the thickness and the total width of material that is removed to form the slot.
In determining net area across plug or slot welds, the weld metal shall not be considered as
adding to net area.
10.2.4
Classification of Sections for Local Buckling
Sections are classified as compact, noncompact, or slender-element sections. For a section
to qualify as compact its flanges must be continuously connected to the web or webs and
the width-thickness ratios of its compression elements must not exceed the limiting width-
thickness ratios x from Table 6.10.1. If the width- thickness ratio of one or more
compression elements exceeds x , but does not exceed x from Table 6.10.1, the section
is noncompact. If the width-thickness ratio of any element exceeds x, the section is
referred to as a slender-element section.
10.2.4.1
Unstiffened elements
For unstiffened elements supported along only one edge parallel to the direction of the
compression force, the width shall be taken as follows:
(a) For flanges of I-shaped members and tees, the width b is one-half the full-flange
width, 	.
(b) For legs of angles and flanges of channels and zees, the width b is the full nominal
dimension.
Chapter 10
(c) For plates, the width b is the distance from the free edge to the first row of
fasteners or line of welds.
(d) For stems of tees, d is taken as the full nominal depth of the section.
10.2.4.2
Stiffened elements
For stiffened elements supported along two edges parallel to the direction of the
compression force, the width shall be taken as follows:
(a) For webs of rolled or formed sections, h is the clear distance between flanges less
the fillet or corner radius at each flange; ℎ is twice the distance from the centroid
to the inside face of the compression flange less the fillet or corner radius.
(b) For webs of built-up sections, h is the distance between adjacent lines of fasteners
or the clear distance between flanges when welds are used, and ℎ is twice the
distance from the centroid to the nearest line of fasteners at the compression flange
or the inside face of the compression flange when welds are used; ℎ is twice the
distance from the plastic neutral axis to the nearest line of fasteners at the
compression flange or the inside face of the compression flange when welds are
used.
(c) For flange or diaphragm plates in built-up sections, the width b is the distance
between adjacent lines of fasteners or lines of welds.
(d) For flanges of rectangular hollow structural sections (HSS), the width b is the
clear distance between webs less the inside corner radius on each side. For webs
of rectangular HSS, h is the clear distance between the flanges less the inside
corner radius on each side. If the corner radius is not known, b and h shall be taken
as the corresponding outside dimension minus three times the thickness. The
thickness, t, shall be taken as the design wall thickness, per Sec 10.2.3.12.
(e) For tapered flanges of rolled sections, the thickness is the nominal value halfway
between the free edge and the corresponding face of the web.
10.2.5
Fabrication, Erection and Quality
Shop drawings, fabrication, shop painting, erection, and quality control shall meet the
requirements stipulated in Sec10.13, Fabrication, Erection, and Quality Control.
10.3
Stability Analysis and Design
This Section addresses general requirements for the stability analysis and design of
members and frames of steel buildings and structures.
10.3.1
Stability Design Requirements
Stability shall be provided for the structure as a whole and for each of its elements. Any
method that considers the influence of second-order effects (including P- and P- effects),
Chapter 10
flexural, shear and axial deformations, geometric imperfections, and member stiffness
reduction due to residual stresses on the stability of the structure and its elements is
permitted. The methods prescribed in this Section and Sec 10.14: Direct Analysis Method,
satisfy these requirements. All component and connection deformations that contribute to
the lateral displacements shall be considered in the stability analysis. In structures designed
by elastic analysis, individual member stability and stability of the structure as a whole are
provided jointly by:
(a) Calculation of the required strengths for members, connections and other elements
using one of the methods specified in Sec10.3.2.2, and
(b) Satisfaction of the member and connection design requirements in this
specification based upon those required strengths.
In structures designed by inelastic analysis, the provisions of Sec 10.15 shall be satisfied.
10.3.1.1
Member stability design requirements
Individual member stability is provided by satisfying the provisions of Sections 10.5 to
10.11. Where elements are designed to function as braces to define the unbraced length of
columns and beams, the bracing system shall have sufficient stiffness and strength to
control member movement at the braced points. Methods of satisfying this requirement are
provided in Sec 10.19.
10.3.1.2
System stability design requirements
Lateral stability shall be provided by moment frames, braced frames, shear walls, and/or
other equivalent lateral load resisting systems. The overturning effects of drift and the
destabilizing influence of gravity loads shall be considered. Force transfer and load sharing
between elements of the framing systems shall be considered. Braced-frame and shear-wall
systems, moment frames, gravity framing systems, and combined systems shall satisfy the
following specific requirements: