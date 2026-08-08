---
clause: "2.4.17"
title: "Dynamic Response"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: ["../json/table_06_9..json", "../json/table_06_6.2.8.json", "../json/table_06_6.2.9.json", "../json/table_06_6.1.1.json", "../json/table_06_6.2.10.json", "../json/table_06_6.2.11.json", "../json/table_06_6.2.10..json", "../json/table_06_6.2.12.json"]
related_diagrams: ["../webp/fig_06_6.2.10.webp", "../webp/fig_06_6.2.2.webp", "../webp/fig_06_6.2.3.webp", "../webp/fig_06_6.2.4.webp", "../webp/fig_06_6.2.5.webp", "../webp/fig_06_6.2.6.webp", "../webp/fig_06_6.2.7.webp", "../webp/fig_06_6.2.6..webp", "../webp/fig_06_6.2.11.webp", "../webp/fig_06_6.2.8.webp", "../webp/fig_06_6.2.9.webp", "../webp/fig_06_6.2.12.webp", "../webp/fig_06_6.2.12..webp", "../webp/fig_06_6.2.13.webp", "../webp/fig_06_6.2.14.webp", "../webp/fig_06_6.2.15.webp", "../webp/fig_06_6.2.16.webp", "../webp/fig_06_6.2.17.webp", "../webp/fig_06_6.2.18.webp", "../webp/fig_06_6.2.19.webp", "../webp/fig_06_6.2.20.webp", "../webp/fig_06_6.2.21.webp", "../webp/fig_06_6.2.22.webp", "../webp/fig_06_6.2.23.webp", "../webp/fig_06_6.2.10..webp"]
related_flowcharts: ["../mmd/flow_06_proc_5cc3c5.mmd"]
---
# Section 2.4.17: Dynamic Response

2.4.17 Dynamic Response
Tests for the purpose of determining the dynamic response of a building or
other structure shall be in accordance with Sec 2.4.16.2. The structural model
and associated analysis shall account for mass distribution, stiffness, and
damping.
Chapter 2
Enclosed Buildings: Walls & Roofs
Notes:
1. Pressures shown are applied to the horizontal and vertical projections, for exposure
A, at h=9.1m, I=1.0, and Kzt = 1.0. Adjust to other conditions using Equation 6.2.3.
2. The load patterns shown shall be applied to each corner of the building in turn as the reference
corner. (See Figure 6.2.10)
3. For the design of the longitudinal MWFRS use θ = 0°, and locate the zone E/F, G/H boundary at
the mid-length of the building.
4. Load cases 1 and 2 must be checked for 25° < θ ≤ 45°. Load case 2 at 25° is provided only for
interpolation between 25° to 30°.
5. Plus and minus signs signify pressures acting toward and away from the projected surfaces,
respectively.
6. For roof slopes other than those shown, linear interpolation is permitted.
7. The total horizontal load shall not be less than that determined by assuming ps = 0 in zones B & D.
8. The zone pressures represent the following:
Horizontal pressure zones – Sum of the windward and leeward net (sum of internal and external)
pressures on vertical projection of:
A - End zone of wall
C - Interior zone of wall
B - End zone of roof
D - Interior zone of roof
Vertical pressure zones – Net (sum of internal and external) pressures on horizontal projection of:
E - End zone of windward roof       G - Interior zone of windward roof
F - End zone of leeward roof           H - Interior zone of leeward roof
9.  Where zone E or G falls on a roof overhang on the windward side of the building, use EOH and
GOH for the pressure on the horizontal projection of the overhang. Overhangs on the leeward
and side edges shall have the basic zone pressure applied.
10. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller, but not less than
either 4% of least horizontal dimension or 0.9 m.
h: Mean roof height, in feet (meters), except that eave height shall be used for roof angles <10°.
θ: Angle of plane of roof from horizontal, in degrees.
Chapter 2
Adjustment Factor for Building Height and Exposure, 
Mean roof height (m)
Exposure
A
B
C
4.6
1.00
1.21
1.47
6.0
1.00
1.29
1.55
7.6
1.00
1.35
1.61
9.1
1.00
1.40
1.66
10.7
1.05
1.45
1.70
12.2
1.09
1.49
1.74
13.7
1.12
1.53
1.78
15.2
1.16
1.56
1.81
16.8
1.19
1.59
1.84
18.3
1.22
1.62
1.87
Figure 6.2.2 Design wind pressure for main wind force resisting system- Method 1
(h ≤ 18.3 m)
Enclosed Buildings: Walls & Roofs
Notes:
1. Pressures shown are applied normal to the surface, for exposure A, at h = 9.1m, I = 1.0, and Kzt =
1.0. Adjust to other conditions using Equation 6.2.4.
2. Plus and minus signs signify pressures acting toward and away from the surfaces, respectively.
3. For hip roofs with θ ≤ 25°, Zone 3 shall be treated as Zone 2.
4. For effective wind areas between those given, value may be interpolated, otherwise use the value
associated with the lower effective wind area.
5. Notation:
a:  10 percent of least horizontal dimension or 0.4h, whichever is smaller, but not less than either 4%
of least horizontal dimension or 0.9 m.
h:  Mean roof height, in feet (meters), except that eave height shall be used for roof angles <10°.
θ:  Angle of plane of roof from horizontal, in degrees.
Chapter 2
Roof Overhang Net Design Wind Pressure, Pnet30  (kN/m2)
(Exposure A at h = 9.1 m with l= 1.0)
Roof
Pitch
Zone
Effective
Wind area (m2)
Basic Wind Speed V (m/s)
40.23
44.7
49.17
53.64 58.11 62.58
67.05
75.99
Roof  0 to 7 degrees
2
0.930
-1.005 -1.239 -1.502 -1.785 -2.096 -2.431 -2.790 -3.584
2
1.860
-0.986 -1.220 -1.473 -1.756 -2.058 -2.388 -2.742 -3.522
2
4.648
-0.962 -1.191 -1.440 -1.713 -2.010 -2.330 -2.675 -3.436
2
9.296
-0.947 -1.168 -1.412 -1.680 -1.971 -2.287 -2.627 -3.373
3
0.930
-1.656 -2.043 -2.470 -2.943 -3.450 -4.005 -4.594 -5.905
3
1.860
-1.297 -1.603 -1.938 -2.311 -2.708 -3.144 -3.609 -4.632
3
4.648
-0.828 -1.024 -1.240 -1.474 -1.727 -2.005 -2.302 -2.957
3
9.296
-0.479 -0.584 -0.708 -0.842 -0.986 -1.144 -1.311 -1.684
Figure 6.2.3 Design wind pressure for components and cladding - Method 1 (h ≤ 18.3 m)
Roof Overhang Net Design Wind Pressure, Pnet30  (kN/m2)
(Exposure A at h = 9.1 m with l= 1.0)
Roof
Pitch
Zone
Effective
Wind area
(m2)
Basic Wind Speed V (m/s)
40.23
44.7
49.17 53.64 58.11
62.58
67.05
75.99
Roof > 7 to 27 degrees
2
0.930
-1.302 -1.603 -1.943 -2.311 -2.713 -3.144
-3.613
-4.637
2
1.860
-1.302 -1.603 -1.943 -2.311 -2.713 -3.144
-3.613
-4.637
2
4.648
-1.302 -1.603 -1.943 -2.311 -2.713 -3.144
-3.613
-4.637
2
9.296
-1.302 -1.603 -1.943 -2.311 -2.713 -3.144
-3.613
-4.637
3
0.930
-2.187 -2.699 -3.268 -3.885 -4.560 -5.292
-6.072
-7.800
3
1.860
-1.971 -2.436 -2.948 -3.507 -4.115 -4.775
-5.479
-7.039
3
4.648
-1.689 -2.086 -2.526 -3.005 -3.526 -4.091
-4.694
-6.034
3
9.296
-1.479 -1.823 -2.206 -2.627 -3.082 -3.574
-4.106
-5.268
Chapter 2
Roof >27 to 45  degrees
2
0.930
-1.182 -1.460 -1.766 -2.101 -2.464 -2.861
-3.282
-4.216
2
1.860
-1.148 -1.416 -1.713 -2.038 -2.393 -2.775
-3.182
-4.091
2
4.648
-1.101 -1.359 -1.641 -1.952 -2.292 -2.660
-3.052
-3.924
2
9.296
-1.062 -1.311 -1.587 -1.890 -2.220 -2.574
-2.952
-3.795
3
0.930
-1.182 -1.460 -1.766 -2.101 -2.464 -2.861
-3.283
-4.216
3
1.860
-1.148 -1.416 -1.713 -2.038 -2.393 -2.775
-3.182
-4.091
3
4.648
-1.101 -1.359 -1.641 -1.952 -2.292 -2.660
-3.053
-3.923
3
9.296
-1.062 -1.311 -1.589 -1.890 -2.220 -2.574
-2.952
-3.795
Adjustment Factor for Building Height and Exposure, 
Mean roof height (m)
Exposure
A
B
C
4.6
1.00
1.21
1.47
6.1
1.00
1.29
1.55
7.6
1.00
1.35
1.61
9.15
1.00
1.40
1.66
10.7
1.05
1.45
1.70
12.2
1.09
1.49
1.74
13.7
1.12
1.53
1.78
15.2
1.16
1.56
1.81
16.8
1.19
1.59
1.84
18.3
1.22
1.62
1.87
Unit Conversion – 1.0 ft =0.3048 m; 1.0 ft2 = 0.0929 m2; 1.0 psf = 0.0479 kN/m2
Figure 6.2.3 (Contd.) Design wind pressure for components and cladding-Method 1
(h ≤ 18.3 m)
Chapter 2
Topographic Multipliers for Exposure B
H/Lh
K1 Multiplier
x/Lh
K2 Multiplier
z/Lh
K3 Multiplier
2-D
Ridge
2-D
Escarp.
3-D
Axisym.
Hill
2-D
Escarp.
All
Other
Cases
2-D
Ridge
2-D
Escarp.
3-D
Axisym.
Hill
0.20
0.29
0.17
0.21
0.00
1.00
1.00
0.00
1.00
1.00
1.00
0.25
0.36
0.21
0.26
0.50
0.88
0.67
0.10
0.74
0.78
0.67
0.30
0.43
0.26
0.32
1.00
0.75
0.33
0.20
0.55
0.61
0.45
0.35
0.51
0.30
0.37
1.50
0.63
0.00
0.30
0.41
0.47
0.30
0.40
0.58
0.34
0.42
2.00
0.50
0.00
0.40
0.30
0.37
0.20
0.45
0.65
0.38
0.47
2.50
0.38
0.00
0.50
0.22
0.29
0.14
0.50
0.72
0.43
0.53
3.00
0.25
0.00
0.60
0.17
0.22
0.09
3.50
0.13
0.00
0.70
0.12
0.17
0.06
4.00
0.00
0.00
0.80
0.09
0.14
0.04
0.90
0.07
0.11
0.03
1.00
0.05
0.08
0.02
1.50
0.01
0.02
0.00
2.00
0.00
0.00
0.00
Notes:
1.   For values of H/Lh, x/Lh and z/Lh other than those shown, linear interpolation is permitted.
2.   For H/Lh > 0.5, assume H/Lh = 0.5 for evaluating K1 and substitute 2H for Lh for evaluating K2 and
K3.
3.  Multipliers are based on the assumption that wind approaches the hill or escarpment along the
direction of maximum slope.
4.   Notation:
H:  Height of hill or escarpment relative to the upwind terrain, in meters.
Lh:  Distance upwind of crest to where the difference in ground elevation is half the height of hill
or escarpment, in meters.
K1:  Factor to account for shape of topographic feature and maximum speed-up effect.
K2:  Factor to account for reduction in speed-up with distance upwind or downwind of crest.
K3:  Factor to account for reduction in speed-up with height above local terrain.
x:    Distance (upwind or downwind) from the crest to the building site, in meters.
z:    Height above local ground level, in meters.
W:  Horizontal attenuation factor.
γ:    Height attenuation factor
Equation:
0/" 5 (1 + 01 0 02 ) ; K1   determined from Table below;    0 5 ¸1 −
||
êBÁ¹ ;    02 5
PÒë//BÁ
Chapter 2
Parameters for Speed-Up Over Hills and Escarpments
Hill Shape
K1/(H/Lh)
γ
μ
Exposure A Exposure B Exposure C
Upwind of
crest
Downwind
of Crest
2-dimensional ridges
(or valleys with negative
H in K1/(H/Lh)
1.30
1.45
1.55
3
1.5
1.5
2-dimensional
escarpments
0.75
0.85
0.95
2.5
1.5
4
3-dimensional
axisym.
Hill
0.95
1.05
1.15
4
1.5
1.5
Figure 6.2.4 Topographic factor, Kzt - Method 2
Enclosed, Partially Enclosed, and Open Buildings: Walls & Roofs
Enclosure Classification
GCpi
Notes:
1.  Plus and minus signs signify pressures acting
toward and away from the internal surfaces,
respectively.
2.  Values of GCpi shall be used with qz or qh as
specified in Sec 2.4.11.
3. Two cases shall be considered to determine the
critical load requirements for the appropriate
condition:
(i) a positive value of GCpi applied to all internal
surfaces
(ii) a negative value of GCpi applied to all internal
surfaces.
Open Building
0.00
Partially Enclosed Building  +0.55
-0.55
Enclosed Building
+0.18
-0.18
Figure 6.2.5  Internal pressure coefficient, GCpi main wind force resisting system
component and cladding - Method 2 (All Heights)
Chapter 2
Figure 6.2.6  External Pressure Coefficients, Cp main wind force resisting system -
Method 2 (All Heights)
Enclosed, Partially Enclosed Buildings: Walls & Roofs
Wall  Pressure Coefficients, Cp
Surface
L/B
Cp
Use With
Windward Wall
All values
0.8
qz
Leeward Wall
0-1
-0.5
qh
2
-0.3
> 4
-0.2
Side Wall
All values
-0.7
qh
Chapter 2
Roof Pressure Coefficients, Cp, for use with qh
Wind
Direction
Windward
Leeward
Angle, θ (degrees)
Angle, θ (degrees)
h/L
10
15
20
25
30
35
45
>60#
10
15
>20
Normal
To  ridge for
θ >100
<0.25
-0.7
-0.18
-0.5
0.0*
-0.3
0.2
-0.2
0.3
-0.2
0.3
0.0*
0.4
0.4
0.01θ
-0.3
-0.5
-0.6
0.5
-0.9
-0.18
-0.7
-0.18
-0.4
0.0*
-0.3
0.2
-0.2
0.2
-0.2
0.3
0.0*
0.4
0.01θ
-0.5
-0.5
-0.6
>1.0
-1.3**
-0.18
-1.0
-0.18
-0.7
-0.18
-0.5
0.0*
-0.3
0.2
-0.2
0.2
0.0*
0.3
0.01θ
-0.7
-0.6
-0.6
Normal
To ridge for
θ <10o and
Parallel to
ridge for all
θ
< 0.5
Horizontal distance
from Windward edge
Cp
* Value is provided for interpolation
purposes
** Value can be reduced linearly with area
over which it is applicable as follows
0 to h/2
-0.9, -0.18
h/2 to h
-0.9, -0.18
h to 2 h
-0.5, -0.18
> 2h
-0.3, -0.18
> 1.0
0 to h/2
-1.3**,-0.18
Area (m2)
Reduction Factor
< 9.3
1.0
> h/2
-0.7, -0.18
23.2
0.9
>  92.9
0.8
Notes:
1.  Plus and minus signs signify pressures acting toward and away from the surfaces, respectively.
2.  Linear interpolation is permitted for values of L/B, h/L and θ other than shown. Interpolation shall only be carried
out between values of the same sign. Where no value of the same sign is given, assume 0.0 for interpolation
purposes.
3.  Where two values of Cp are listed, this indicates that the windward roof slope is subjected to either positive or
negative pressures and the roof structure shall be designed for both conditions.  Interpolation for intermediate
ratios of h/L in this case shall only be carried out between Cp values of like sign.
4.  For monoslope roofs, entire roof surface is either a windward or leeward surface.
5. For flexible buildings use appropriate Gf as determined by Sec 2.4.8.
6. Refer to Figure 6.2.7 for domes and Figure 6.2.8 for arched roofs.
7. Notation:
B:
Horizontal dimension of building, in meter, measured normal to wind direction.
L:
Horizontal dimension of building, in meter, measured parallel to wind direction.
h:
Mean roof height in meters, except that eave height shall be used for e 10 degrees.
z:
Height above ground, in meters.
G:
Gust effect factor.
qz,qh:  Velocity pressure, in N/m2, evaluated at respective height.
θ:
Angle of plane of roof from horizontal, in degrees.
8.  For mansard roofs, the top horizontal surface and leeward inclined surface shall be treated as leeward surfaces
from the table
9.  Except for MWFRS's at the roof consisting of moment resisting frames, the total horizontal shear shall not  be less
than that determined by neglecting wind forces on roof surfaces.
$$#For roof slopes greater than 80°, use Cp = 0.8$$
Figure 6.2.6  (Contd.) External pressure coefficients, Cp main wind force resisting system -
Method 2 (All Heights)
Chapter 2
Enclosed, Partially Enclosed Buildings and Structures: Domed Roofs
Notes:
1. Two load cases shall be considered:
Case A. Cp values between A and B and between B and C shall be determined by linear
interpolation along arcs on the dome parallel to the wind direction;
Case B. Cp shall be the constant value of A for θ ≤ 25 degrees, and shall be determined by
linear interpolation from 25 degrees to B and from B to C.
2. Values denote Cp to be used with X3í³ where (hD + f) is the height at the top of the dome.
3. Plus and minus signs signify pressures acting toward and away from the surfaces,
respectively.
4. Cp is constant on the dome surface for arcs of circles perpendicular to the wind direction;
for example, the arc passing through B-B-B and all arcs parallel to B-B-B.
5. For values of hD/D between those listed on the graph curves, linear interpolation shall be
permitted.
6. 50 degrees on dome springline, θ590 degrees at dome center top point. f is measured
from springline to top.
7. The total horizontal shear shall not be less than that determined by neglecting wind forces
roof surfaces.
8. For f/D values less than 0.05, use Figure 6.2.6.
Figure 6.2.7   External pressure coefficients, Cp main wind force resisting system - Method 2
(All Heights)
Chapter 2
Enclosed, Partially Enclosed Buildings and Structures: Arched Roofs
Condition
Rise-to-span
ratio, r
Cp
Windward
quarter
Center
half
Leeward
quarter
Roof on elevated
structure
0 <  r < 0.2
-0.9
-0.7 - r
-0.5
0.2 ≤ r < 0.3*
l.5 r - 0.3
-0.7 - r
-0.5
0.3 ≤ r ≤ 0.6
2.75 r - 0.7
-0.7 - r
-0.5
Roof springing from
ground level
0 < r ≤ 0.6
1.4 r
-0.7 - r
-0.5
Notes:
*  When the rise-to-span ratio is 0.2 ≤ r ≤ 0.3, alternate coefficients given by
(6r- 2.1) shall also be used for the windward quarter.
1. Values listed are for the determination of average load on main wind force
resisting systems.
2. Plus and minus signs signify pressures acting toward and away from the surfaces,
respectively.
3. For wind directed parallel to the axis of the arch, use pressure coefficients from
Figure 6.2.6 with wind directed parallel to ridge.
4. For components and cladding: (1) At roof perimeter, use the external pressure
coefficients in Figure 6.2.11 with e based on spring-line slope and (2) for
remaining roof areas, use external pressure coefficients of this Table multiplied by
0.87.
Figure 6.2.8 External pressure coefficients, Cp main wind force resisting system component
and cladding - Method 2 (All Heights)
Chapter 2
Case 1.
Full design wind pressure acting on the projected area perpendicular to
each principal axis of the structure, considered separately along each
principal axis.
Case 2.
Three quarters of the design wind pressure acting on the projected area
perpendicular to each principal axis of the structure in conjunction with a
torsional moment as shown, considered separately for each principal axis.
Case 3.
Wind loading as defined in Case 1, but considered to act simultaneously at
75% of the specified value.
Case 4.
Wind loading as defined in Case 2, but considered to act simultaneously at
75% of the specified value.
Notes:
1. Design wind pressures for windward and leeward faces shall be determined in
accordance with the provisions of Sec 2.4.11 as applicable for building of all heights.
2. Diagrams show plan views of building.
3. Notation:
Pwx, PwY:  Windward face design pressure acting in the x, y principal axis,
respectively.
PLX, PLY:    Leeward face design pressure acting in the x, y principal axis,
respectively.
e(ex,  ey): Eccentricity for the x, y principal axis of the structure, respectively.
MT:
Torsional moment per unit height acting about a vertical axis of the
building.
Figure 6.2.9 Design wind load cases for main wind force resisting system-Method 2
(All Heights)
Chapter 2
Enclosed, Partially Enclosed Buildings: Low-rise Walls & Roofs
Figure 6.2.10  External pressure coefficients, GCpf for main wind force resisting
system- Method 2 (h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Low-rise Walls & Roofs
Notes:
1. Plus and minus signs signify pressures acting toward and away from the surfaces, respectively.
2. For values of θ other than those shown, linear interpolation is permitted.
3. The building must be designed for all wind directions using the 8 loading patterns shown. The load
patterns are applied to each building corner in turn as the Reference Corner.
4. Combinations of external and internal pressures (see Figure 6.2.5) shall be evaluated as required
to obtain the most severe loadings.
5. For the torsional load cases shown below, the pressures in zones designated with a “T” (1T, 2T, 3T,
4T) shall be 25% of the full design wind pressures (zones 1, 2, 3, 4).
Exception: One story buildings with h less than or equal to 9.1m, buildings two stories or less
framed with light frame construction, and buildings two stories or less designed with flexible
diaphragms need not be designed for the torsional load cases.
Torsional loading shall apply to all eight basic load patterns using the figures below applied at each
reference corner.
6. Except for moment-resisting frames, the total horizontal shear shall not be less than that
determined by neglecting wind forces on roof surfaces.
7. For the design of the MWFRS providing lateral resistance in a direction parallel to a ridge line or for flat
roofs, use θ 5 0° and locate the zone 2/3 boundary at the mid-length of the building.
8. The roof pressure coefficient GCpf, when negative in Zone 2 or 2E, shall be applied in Zone 2/2E for
a distance from the edge of roof equal to 0.5 times the horizontal dimension of the building parallel
to the direction of the MWFRS being designed or 2.5 times the eave height, he, at the windward
wall, whichever is less; the remainder of Zone 2/2E extending to the ridge line shall use the
pressure coefficient GCpf for Zone 3/3E.
9. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller, but not less than either
4% of least horizontal dimension or 0.9 m.
h: Mean roof height, in meters, except that eave height shall be used for θ ≤ 10°.
: Angle of plane of roof from horizontal, in degrees.
Roof
Angle θ
(degrees)
Building Surface
1
2
3
4
5
6
1E
2E
3E
4E
0-5
0.40 -0.69 -0.37
-0.29
-0.45
-0.45
0.61
-1.07
-0.53
-0.43
20
0.53 -0.69 -0.48
-0.43
-0.45
-0.45
0.80
-1.07
-0.69
-0.64
30-45
0.56
0.21 -0.43
-0.37
-0.45
-0.45
0.69
0.27
-0.53
-0.48
90
0.56
0.56 -0.37
-0.37
-0.45
-0.45
0.69
0.69
-0.48
-0.48
Figure 6.2.10 (Contd.) External pressure coefficients, GCpf for  main wind force
resisting system - Method 2 (h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Walls
Notes:
1. Vertical scale denotes GCP to be used with qh.
2. Horizontal scale denotes effective wind area, in square meters.
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. Values of GCP for walls shall be reduced by 10% when θ ≤ 100.
6. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller,
but not less than either 4% of least horizontal dimension or 0.9m.
h: Mean roof height, in meters, except that eave height shall be used for θ ≤ 100.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.11(a)  External pressure coefficients, GCp for components and cladding–Method
2 (h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Gable Roofs θ ≤ 70
Notes:
1. Vertical scale denotes GCP to be used with qh.
2. Horizontal scale denotes effective wind area, in square meters.
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. If a parapet equal to or higher than 0.9 m is provided around the perimeter of
the roof with θ ≤ 70, the negative values of GCp in Zone 3 shall be equal to
those for Zone 2 and positive values of GCP in Zones 2 and 4 shall be set
equal to those for wall Zones 4 and 5 respectively in Figure 6.2.11(a).
6. Values of GCP for roof overhangs include pressure contributions from both
upper and lower surfaces.
7. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller, but
not less than either 4% of least horizontal dimension or 0.9 m.
h: Eave height shall be used for θ ≤ 100.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.11(b)  External pressure coefficients, GCp for components and cladding–
Method 2 (h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Gable/Hip Roofs 70 < θ ≤ 270
Notes:
1. Vertical scale denotes GCP to be used with
.
h
q
2. Horizontal scale denotes effective wind area, in square feet (square
meters).
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. Values of GCP for roof overhangs include pressure contributions from
both upper and lower surfaces.
6. For hip roofs with 70 < θ ≤ 270, edge/ridge strips and pressure
coefficients for ridges of gabled roofs shall apply on each hip.
7. For hip roofs with 70 < θ ≤ 250, Zone 3 shall be treated as Zone 2.
8. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller,
but not less than either 4% of least horizontal dimension or 0.9 m.
h: Mean roof height, in meters, except that eave height shall be used for θ
≤ 100.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.11(c) External pressure coefficients, GCp for components and cladding–Method 2
(h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Gable Roofs 270 < θ ≤ 450
Notes:
1. Vertical scale denotes GCP to be used with qh.
2. Horizontal scale denotes effective wind area, in square feet (square
meters).
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. Values of GCP for roof overhangs include pressure contributions from
both upper and lower surfaces.
6. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller,
but not less than either 4% of least horizontal dimension or 0.9m.
h: Mean roof height, in meters.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.11(d) External pressure coefficients, GCp for components and cladding–Method 2
(h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Stepped Roofs
Notes:
On the lower level of flat, stepped roofs shown in Figure 6.2.12, the zone
designations and pressure coefficients shown in Figure 6.2.11(b) shall apply,
except that at the roof-upper wall intersection(s), Zone 3 shall be treated as
Zone 2 and Zone 2 shall be treated as Zone 1. Positive values of GCp equal to
those for walls in Figure 6.2.11(a) shall apply on the cross-hatched areas shown
in Figure 6.2.12.
Notation:
b: 1.5h1 in Figure 6.2.12, but not greater than 30.5 m.
h: Mean roof height, in meters.
hi: h1 or h2 in Figure 6.2.12; h 5 h1 + h2; h1≥ 3.1 m; hi/h 5 0.3 to 0.7.
W: Building width in Figure 6.2.12.
Wi: W1 or W2 or W3 in Figure 6.2.12. W5 W1 + W2 or W1 + W2 + W3; Wi/W5
0.25 to 0.75.
e: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.12  External pressure coefficients, GCp for components and cladding–Method 2
(h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Multispan Gable Roofs
Notes:
1. Vertical scale denotes GCP to be used with qh.
2. Horizontal scale denotes effective wind area, in square meters.
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. For θ ≤ 100 Values of GCP from Figure 6.2.11 shall be used.
6. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller, but
not less than either 4% of least horizontal dimension or 0.9 m.
h: Mean roof height, in feet (meters), except that eave height shall be used for
θ ≤ 100.
W: Building module width, in meters.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.13  External pressure coefficients, GCp for components and cladding–Method 2
(h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Monoslope Roofs 30 < θ ≤ 100z
Notes:
1. Vertical scale denotes GCP to be used with qh.
2. Horizontal scale denotes effective wind area A, in square meters.
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. For θ ≤ 30 Values of GCP from Figure 6.2.11(b) shall be used.
6. Notation:
a: 10 percent of least horizontal dimension or 0.4h, whichever is smaller,
but not less than either 4% of least horizontal dimension or 0.9 m.
h: Eave height shall be used for θ ≤ 100.
W: Building width, in meters.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.14(a)  External pressure coefficients, GCp for components and cladding–
Method 2 (h ≤ 18.3 m)
-3.0
Chapter 2
Enclosed, Partially Enclosed Buildings: Monoslope Roofs 100 < θ ≤ 300
Notes:
1. Vertical scale denotes GCP to be used with qh
2. Horizontal scale denotes effective wind area A, in square feet (square
meters).
3. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4. Each component shall be designed for maximum positive and negative
pressures.
5. Notation:
a:  10 percent of least horizontal dimension or 0.4h, whichever is smaller,
but not less than either 4% of least horizontal dimension or 0.9 m.
h:  Mean roof height in meters.
W: Building width, in meters.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.14(b)  External pressure coefficients, GCp for components and cladding–
Method 2 (h ≤ 18.3 m)
-3.0
Chapter 2
Enclosed, Partially Enclosed Buildings: Sawtooth Roofs
Notes:
1.
Vertical scale denotes GCP to be used with qh.
2.
Horizontal scale denotes effective wind area A, in square feet (square meters).
3.
Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
4.
Each component shall be designed for maximum positive and negative pressures.
5.
For ≤100 Values of GCP from Figure 6.2.11 shall be used.
6.
Notation:
a:  10 percent of least horizontal dimension or 0.4h, whichever is smaller, but
not less than either 4% of least horizontal dimension or 0.9 m.
h:  Mean roof height in meters except that eave height shall be used for θ  ≤ 100.
W: Building width, in meters.
θ: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.15
External pressure coefficients, GCp for components and cladding–
Method 2 (h ≤ 18.3 m)
Chapter 2
Enclosed, Partially Enclosed Buildings: Domed Roofs
External Pressure Coefficients for Domes with a circular Base
θ, degrees
Negative Pressures
Positive Pressures
Positive Pressures
0 – 90
0 – 60
61 – 90
GCp
-0.9
+0.9
+0.5
Notes:
1. Values denote Cp to be used with q(hD+f) where hD+f  is the height at the
top of the dome.
2. Plus and minus signs signify pressures acting toward and away from the
surfaces, respectively.
3. Each component shall be designed for maximum positive and negative
pressures.
4. Values apply to θ ≤ hDD ≤ 0.5, 0.2≤ f/D ≤0.5.
5.
θ 50o on dome springline, θ 5 90o at dome center top point. f is
measured from springline to top.
Figure 6.2.16  External pressure coefficients, GCp for components and cladding – Method 2
(All heights)
Chapter 2
Enclosed, Partially Enclosed Buildings: Walls & Roofs
Notes:
1. Vertical scale denotes GCp to be used with appropriate qz or qh.
2. Horizontal scale denotes effective wind area A, in square feet (square meters).
3. Plus and minus signs signify pressures acting toward and away from the surfaces,
respectively.
4. Use qz with positive values of GCp and qh with negative values of GCp
5. Each component shall be designed for maximum positive and negative pressures.
6. Coefficients are for roofs with angle ≤10°. For other roof angles and geometry, use
GCp values from Figure 6.2.11 and attendant qh based on exposure defined in Sec
2.4.6.
7. If a parapet equal to or higher than 0.9 m is provided around the perimeter of the
roof with  ≤10°  Zone 3 shall be treated as Zone 2.
8. Notation:
a:  10 percent of least horizontal dimension, but not less than 0.9 m.
h:  Mean roof height, in meters, except that eave height shall be used for ≤10o.
z: height above ground, in (meters).
: Angle of plane of roof from horizontal, in degrees.
Figure 6.2.17  External pressure coefficients, GCp for components and cladding – Method 2
(h ≤ 18.3 m)
Chapter 2
Open Buildings: Monoslope free roofs (q < 45,   = 0, 180)
Roof
Angle

Load
Case
Wind Direction,  = 0
Wind Direction,  = 180
Clear Wind
Flow
Obstructed
Wind Flow
Clear Wind
Flow
Obstructed Wind
Flow
CNW
CNL
CNW
CNL
CNW
CNL
CNW
CNL
0
A
1.2
0.3
-0.5
-1.2
1.2
0.3
-0.5
-1.2
B
-1.1
-0.1
-1.1
-0.6
-1.1
-0.1
-1.1
-0.6
7.5
A
-0.6
-1
-1
-1.5
0.9
1.5
-0.2
-1.2
B
-1.4
0
-1.7
-0.8
1.6
0.3
0.8
-0.3
15
A
-0.3
-1.3
-1.1
-1.5
1.3
1.6
0.4
-1.1
B
-1.9
0
-2.1
-0.6
1.8
0.6
1.2
-0.3
22.5
A
-1.5
-1.6
-1.5
-1.7
1.7
1.8
0.5
-1
B
-2.4
-0.3
-2.3
-0.9
2.2
0.7
1.3
0
30
A
-1.8
-1.8
-1.5
-1.8
2.1
2.1
0.6
-1
B
-2.5
-0.6
-2.3
-1.1
2.6
1
1.6
0.1
37.5
A
-1.8
-1.8
-1.5
-1.8
2.1
2.2
0.7
-0.9
B
-2.4
-0.6
-2.2
-1.1
2.7
1.1
1.9
0.3
45
A
-1.6
-1.8
-1.3
-1.8
2.2
2.5
0.8
-0.9
B
-2.3
-0.7
-1.9
-1.2
2.6
1.4
2.1
0.4
Notes:
1. CNW and CNL denote net pressures (contributions from top and bottom surfaces) for
windward and leeward half of roof surfaces, respectively.
2. Clear wind flow denotes relatively unobstructed wind flow with blockage less than or equal
to 50%. Obstructed wind flow denotes objects below roof inhibiting wind flow (>50%
blockage).
3. For values of e between 7.5° and 45°, linear interpolation is permitted. For values of e less
than 7.5°, use Monoslope roof load coefficients.
4. Plus and minus signs signify pressures acting towards and away from the top roof surface,
respectively.
5. All load cases shown for each roof angle shall be investigated.
6. Notation:
L :  horizontal dimension of roof, measured in the along wind direction, m
h :  mean roof height, m
 :  direction of wind, degrees
: angle of plane of roof from horizontal, degrees
Figure 6.2.18(a)
Net pressure coefficient, CN for main wind force resisting system
(0.25< h/L < 1.0)
Chapter 2
Open  Buildings: Pitched Free Roofs (  ≤ 45o, γ = 0o, 180o)
Roof
Angle, 
Load
Case
Wind Direction, ð 5 0o , 180o
Clear Wind Flow
Obstructed Wind Flow
CNW
CNL
CNW
CNL
7.5o
A
1.1
-0.3
-1.6
-1
B
0.2
-1.2
-0.9
-1.7
15o
A
1.1
-0.4
-1.2
-1
B
0.1
-1.1
-0.6
-1.6
22.5o
A
1.1
0.1
-1.2
-1.2
B
-0.1
-0.8
-0.8
-1.7
30o
A
1.3
0.3
-0.7
-0.7
B
-0.1
-0.9
-0.2
-1.1
37.5o
A
1.3
0.6
-0.6
-0.6
B
-0.2
-0.6
-0.3
-0.9
45o
A
1.1
0.9
-0.5
-0.5
B
-0.3
-0.5
-0.3
-0.7
Notes:
1. CNW and CNL denote net pressures (contributions from top and bottom surfaces) for
windward and leeward half of roof surfaces, respectively.
2. Clear wind flow denotes relatively unobstructed wind flow with blockage less than or
equal to 50%. Obstructed wind flow denotes objects below roof inhibiting wind flow
(>50% blockage).
3. For values of  between 7.5° and 45°, linear interpolation is permitted. For values of 
less than 7.5°, use monoslope roof load coefficients.
4. Plus and minus signs signify pressures acting towards and away from the top roof
surface, respectively.
5. All load cases shown for each roof angle shall be investigated.
6. Notation:
L :  horizontal dimension of roof, measured in the along wind direction, m
h :  mean roof height, m
γ : direction of wind, degrees
: angle of plane of roof from horizontal, degrees
Figure 6.2.18(b)  Net pressure coefficient, CN for main wind force resisting system (0.25<
h/L < 1.0)
Chapter 2
Open  Buildings: Troughed Free Roofs (  ≤ 45o, γ = 0o, 180o)
Roof
Angle, 
Load
Case
Wind Direction, γ=0o, 180o
Clear Wind Flow
Obstructed Wind Flow
CNW
CNL
CNW
CNL
7.5o
A
-1.1
0.3
-1.6
-0.5
B
-0.2
1.2
-0.9
-0.8
15o
A
-1.1
0.4
-1.2
-0.5
B
0.1
1.1
-0.6
-0.8
22.5o
A
-1.1
-0.1
-1.2
-0.6
B
-0.1
0.8
-0.8
-0.8
30o
A
-1.3
-0.3
-1.4
-0.4
B
-0.1
0.9
-0.2
-0.5
37.5o
A
-1.3
-0.6
-1.4
-0.3
B
0.2
0.6
-0.3
-0.4
45o
A
-1.1
-0.9
-1.2
-0.3
B
0.3
0.5
-0.3
-0.4
Notes:
1. CNW and CNL denote net pressures (contributions from top and bottom surfaces) for
windward and leeward half of roof surfaces, respectively.
2. Clear wind flow denotes relatively unobstructed wind flow with blockage less than or
equal to 50%. Obstructed wind flow denotes objects below roof inhibiting wind flow
(>50% blockage).
3. For values of  between 7.5° and 45°, linear interpolation is permitted. For values of 
less than 7.5°, use monoslope roof load coefficients.
4. Plus and minus signs signify pressures acting towards and away from the top roof
surface, respectively.
5. All load cases shown for each roof angle shall be investigated.
6. Notation:
L  : horizontal dimension of roof, measured in the along wind direction, m
h  : mean roof height, m
γ : direction of wind, degrees
: angle of plane of roof from horizontal, degrees
Figure 6.2.18(c) Net pressure coefficient, CN for main wind force resisting system (0.25< h/L < 1.0)
Chapter 2
Open  Buildings: Troughed Free Roofs ( ≤ 45o,  = 0o, 180o)
Horizontal
Distance from
Windward Edge
Roof
Angle 
Load Case
Clear
Wind Flow
Obstructed
Wind Flow
CN
CN
≤ h
All Shapes
A
-0.8
-1.2
 ≤ 45o
B
0.8
0.5
> h, ≤ 2h
All Shapes
A
-0.6
-0.9
 ≤ 45o
B
0.5
0.5
> 2h
All Shapes
A
-0.3
-0.6
 ≤ 45o
B
0.3
0.3
Notes:
1. CN denotes net pressures (contributions from top and bottom surfaces).
2. Clear wind flow denotes relatively unobstructed wind flow with blockage less than or
equal to 50%. Obstructed wind flow denotes objects below roof inhibiting wind flow
(>50% blockage).
3. Plus and minus signs signify pressures acting towards and away from the top roof
surface, respectively.
4. All load cases shown for each roof angle shall be investigated.
5. For monoslope roofs with theta less than 5 degrees, CN values shown apply also for
cases where gamma 5 0 degrees and 0.05 less than or equal to h/L less than or equal
to 0.25. See Figure 6.2.18(a) for other h/L values.
6. Notation:
L  : horizontal dimension of roof, measured in the along wind direction, m
h  : mean roof height, m
y : direction of wind, degrees
: angle of plane of roof from horizontal, degrees
Figure 6.2.18(d)
Net pressure coefficient, CN for main wind force resisting system
(0.25< h/L < 1.0)
Chapter 2
Open Buildings: Monoslope Free Roofs ( < 45)
Roof
Angle

Effective
Wind Area
CN
Clear Wind Flow
Obstructed Wind Flow
Zone 3
Zone 2
Zone 1
Zone 3
Zone 2
Zone 1
0
< a2
2.4
-3.3
1.8
-1.7
1.2
-1.1
1
-3.6
0.8
-1.8
0.5
-1.2
>a2, <4.0a2
1.8
-1.7
1.8
-1.7
1.2
-1.1
0.8
-1.8
0.8
-1.8
0.5
-1.2
>4.0a2
1.2
-1.1
1.2
-1.1
1.2
-1.1
0.5
-1.2
0.5
-1.2
0.5
-1.2
7.5
< a2
3.2
-4.2
2.4
-2.1
1.6
-1.4
1.6
-5.1
0.5
-2.6
0.8
-1.7
>a2, <4.0a2
2.4
-2.1
2.4
-2.1
1.6
-1.4
1.2
-2.6
1.2
-2.6
0.8
-1.7
>4.0a2
1.6
-1.4
1.6
-1.4
1.6
-1.4
0.8
-1.7
0.8
-1.7
0.8
-1.7
15
< a2
3.6
-3.8
2.7
-2.9
1.8
-1.9
2.4
-4.2
1.8
-3.2
1.2
-2.1
>a2, <4.0a2
2.7
-2.9
2.7
-2.9
1.8
-1.9
1.8
-3.2
1.8
-3.2
1.2
-2.1
>4.0a2
1.8
-1.9
1.8
-1.9
1.8
-1.9
1.2
-2.1
1.2
-2.1
1.2
-2.3
30
< a2
5.2
-5
3.9
-3.8
2.6
-2.5
3.2
-4.6
2.4
-3.5
1.6
-2.3
>a2, <4.0a2
3.9
-3.8
3.9
-3.8
2.6
-2.5
2.4
-3.5
2.4
-3.5
1.6
-2.3
>4.0a2
2.6
-2.5
2.6
-2.5
2.6
-2.5
1.6
-2.3
1.6
-2.3
1.6
-2.3
45
< a2
5.2
-4.6
3.9
-3.5
2.6
-2.3
4.2
-3.8
3.2
-2.9
2.1
-1.9
>a2, <4.0a2
3.9
-3.5
3.9
-3.5
2.6
-2.3
3.2
-2.9
3.2
-2.9
2.1
-1.9
>4.0a2
2.6
-2.3
2.6
-2.3
2.6
-2.3
2.1
-1.9
2.1
-1.9
2.1
-1.9
Notes:
1.  CN denotes net pressures (contributions from top and bottom surfaces).
2.  Clear wind flow denotes relatively unobstructed wind flow with blockage less than or
equal to 50% wind flow denotes objects below roof inhibiting wind flow (>50%
blockage).
3.  For values of e other than those shown, linear interpolation is permitted.
4.  Plus and minus signs signify pressures acting towards and away from the top roof
surface, respectively.
5.  Components and cladding elements shall be designed for positive and negative
pressure coefficients shown.
6.  Notation:
 : 10% of least horizontal dimension or 0.4h, whichever is smaller but not less than
4% of least horizontal dimension or 0.9 m
h : mean roof height, m
L : horizontal dimension of building, measured in along wind direction, m
: angle of plane of roof from horizontal, degrees
Figure 6.2.19(a) Net pressure coefficient, CN for components and cladding (0.25< h/L < 1.0)
Chapter 2
Open  Buildings: Monoslope Free Roofs ( ≤ 45o)
Roof
Angle

Effective
Wind Area
CN
Clear Wind Flow
Obstructed Wind Flow
Zone 3
Zone 2
Zone 1
Zone 3
Zone 2
Zone 1
0o
≤a2
2.4
-3.3
1.8
-1.7
1.2
-1.1
1
-3.6 0.8
-1.8
0.5
-1.2
>a2, ≤4.0a2
1.8
-1.7
1.8
-1.7
1.2
-1.1
08
-1.8 0.8
-1.8
0.5
-1.2
>4.0a2
1.2
-1.1
1.2
-1.1
1.2
-1.1
0.5 -1.2 0.5
-1.2
0.5
-1.2
7.5o
≤a2
2.2
-3.6
1.7
-1.8
1.1
-1.2
1
-5.1 0.8
-26
0.5
-1.7
>a2, ≤4.0a2
1.7
-1.8
1.7
-1.8
1.1
-1.2
0.8 -2.6 0.8
·26
0.5
-1.7
>4.0a2
1.1
-1.2
1.1
-1.2
1.1
-1.2
0.5 -1.7 0.5
-1.7
as
-1.7
15o
≤a2
2.2
-2.2
1.7
-1.7
1.1
-1.1
1
-3.2 0.8
-2.4
0.5
-1.6
>a2, ≤4.0a2
1.7
-1.7
1.7
-1.7
1.1
-1.1
0.8 -2.4 0.8
-2.4
0.5
-1.6
>4.0a2
1.1
-1.1
1.1
-1.1
1.1
-1.1
0.5 -1.6 0.5
-1.6
0.5
-1.6
30o
≤a2
2.6
-1.8
2
-1.4
1.3
-0.9
1
-2.4 0.8
-1.8
0.5
-1.2
>a2, ≤4.0a2
2
-1.4
2
-1.4
1.3
-0.9
0.8 -1.8 0.8
-1.8
0.5
-1.2
>4.0a2
1.3
-0.9
1.3
-0.9
1.3
-0.9
0.5 -1.2 0.5
.1.2 0.5
-1.2
45o
≤a2
2.2
-1.6
1.7
-1.2
1.1
-0.8
1
-2.4 0.8
-1.8
0.5
-1.2
>a2, ≤4.0a2
1.7
-1.2
1.7
-1.2
1.1
-0.8
0.8 -1.8 0.8
-1.8
0.5
-1.2
>4.0a2
1.1
-0.8
1.1
-0.8
1.1
-0.8
0.5 -1.2 0.5
-1.2
0.5
-1.2
Notes:
1. CN denotes net pressures (contributions from top and bottom surfaces).
2. Clear wind flow denotes relatively unobstructed wind flow with blockage less than or
equal to 50%. Obstructed wind flow denotes objects below roof inhibiting wind flow
(>50% blockage).
3. For values of  other than those shown, linear interpolation is permitted.
4. Plus and minus signs signify pressures acting towards and away from the top roof
surface, respectively.
5. Components and cladding elements shall be designed for positive and negative
pressure coefficients shown.
6. Notation:
 : 10% of least horizontal dimension or 0.411, whichever is smaller but not less than
4%  of least horizontal dimension or 0.9 m
h : mean roof height, m
L : horizontal dimension of building, measured in along wind direction, m
: angle of plane of roof from horizontal, degrees
Figure 6.2.19(b) Net pressure coefficient, CN for components and cladding (0.25< h/L < 1.0)
Chapter 2
Open  Buildings: Troughed Free Roofs (  ≤ 45o)
Roof
Angle

Effective Wind
Area
CN
Clear Wind Flow
Obstructed Wind Flow
Zone 3
Zone 2
Zone 1
Zone 3
Zone 2
Zone 1
0o
≤a2
2.4
-3.3 1.8 -1.7
1.2 -1.1
1
-3.6 0.8 -1.8 0.5 -1.2
>a2, ≤4.0a2
1.8
-1.7 1.8 -1.7
1.1 -1.1
0.8 -1.8 0.8 -1.8 0.5 -1.2
>4.0a2
1.2
-1.1 1.2 -1.1
1.2 -1.1
0.5 -1.2 0.5 -1.2 0.5 -1.2
7.5o
≤a2
2.4
-3.3 1.8 -1.7
1.2 -1.1
1
-4.8 0.8 -2.4 0.5 -1.6
>a2, ≤4.0a2
1.8
-1.7 1.8 -1.7
1.2 -1.1
0.8 -2.4 0.8 -2.4 0.5 -1.6
>4.0a2
1.2
-1.1 1.2 -1.1
1.2 -1.1
0.5 -1.6 0.5 -1.6 0.5 -1.6
15o
≤a2
2.2
-2.2 1.7 -1.7
1.1 -1.1
1
-2.4 0.8 -1.8 0.5 -1.2
>a2, ≤4.0a2
1.7
-1.7 1.7 -1.7
1.1 -1.1
0.8 -1.8 0.8 -1.8 0.5 -1.2
>4.0a2
1.1
-1.1 1.1 -1.1
1.1 -1.1
0.5 -1.2 0.5 -12
0.5 -1.2
30o
≤a2
1.8
-2.6 1.4
-2
0.9 -1.3
1
-2.8 0.8 -2.1 0.5 -1.4
>a2, ≤4.0a2
1.4
-2
1.4
-2
0.9 -1.3
0.8 -2.1 0.8 -2.1 0.5 -1.4
>4.0a2
0.9
-1.3 1.9 -1.3
0.9 -1.3
0.5 -1.4 0.5 -1.4 0.5 -1.4
45o
≤a2
1.6
-2.2 1.2 -1.7
0.8 -1.1
1
-2.4 0.8 -1.8 0.5 -1.2
>a2, ≤4.0a2
1.2
-1.7 1.2 -1.7
0.8 -1.1
0.8 -1.8 0.8 -1.8 0.5 -1.2
>4.0a2
0.8
-1.1 1.8 -1.1
0.8 -1.1
0.5 -1.2 0.5 -1.2 0.5 -1.2
Notes:
1. CN denotes net pressures (contributions from top and bottom surfaces).
2. Clear wind flow denotes relatively unobstructed wind flow with blockage less than or
equal to 50%. Obstructed wind flow denotes objects below roof inhibiting wind flow
(>50% blockage).
3. For values of  other than those shown, linear interpolation is permitted.
4. Plus and minus signs signify pressures acting towards and away from the top roof
surface, respectively.
5. Components and cladding elements shall be designed for positive and negative
pressure coefficients shown.
6. Notation:
 : 10% of least horizontal dimension or 0.411, whichever is smaller but not less than
4%  of least horizontal dimension or 0.9 m
h : mean roof height, m
L : horizontal dimension of building, measured in along wind direction, m
: angle of plane of roof from horizontal, degrees
Figure 6.2.19(c) Net pressure coefficient, CN for components and cladding (0.25< h/L < 1.0)
Chapter 2
Solid Freestanding Walls & Solid Signs
Cf  , CASE A & CASE B
Clearance
Ratio, s/h
Aspect Ratio, B/s
≤0.05
0.1
0.2
0.5
1
2
4
5
10
20
30
≥45
1
1.80
1.70
1.65
1.55 1.45 1.40
1.35 1.35 1.30
1.30
1.30
1.30
0.9
1.85
1.75
1.70
1.60 1.55 1.50
1.45 1.45 1.40
1.40
1.40
1.40
0.7
1.90
1.85
1.75
1.70 1.65 1.60
1.60 1.55 1.55
1.55
1.55
1.55
0.5
1.95
1.85
1.80
1.75 1.75 1.70
1.70 1.70 1.70
1.70
1.70
1.75
0.3
1.95
1.90
1.85
1.80 1.80 1.80
1.80 1.80 1.80
1.85
1.85
1.85
0.2
1.95
1.90
1.85
1.80 1.80 1.80
1.80 1.80 1.85
1.90
1.90
1.95
≤0.16
1.95
1.90
1.85
1.85 1.80 1.80
1.85 1.85 1.85
1.90
1.90
1.95
Cf, CASE C
Region
(horizontal
distance from
windward
edge)
Aspect Ratio, B/s
Region
(horizontal
distance from
windward
edge)
Aspect
Ratio, B/s
2
3
4
5
6
7
8
9
10
13
≥45
0 to s
2.25 2.60 2.90 3.10* 3.30* 3.40* 3.55* 3.65*
3.75*
0 to s
4.00* 4.30*
s to 2s
1.50 1.70 1.90
2.00
2.15
2.25
2.30
2.35
2.45
s to 2s
2.60
2.55
2s to 3s
1.15 1.30
1.45
1.55
1.65
1.70
1.75
1.85
2s to 3s
2.00
1.95
3s to 10s
1.10
1.05
1.05
1.05
1.05
1.00
0.95
3s to 4s
1.50
1.85
*Values shall be
multiplied by the
following reduction
factor when a return
corner is present:
Lr/s
Reduction
Factor
0.3
0.9
1.0
0.75
≥2
0.60
4s to 5s
1.35
1.85
5s to 10s
0.90
1.10
>10s
0.55
0.55
Chapter 2
Notes:
1.  The term "signs" in notes below also applies to "freestanding walls".
2.  Signs with openings comprising less than 30% of the gross area
are classified as solid signs. Force coefficients for solid signs with
openings shall be permitted to be multiplied by the reduction factor
(1 - (1 - )1.5).
3.  To allow for both normal and oblique wind directions, the following
cases shall be considered:
For s/h < 1:
CASE A: resultant force acts normal to the face of the sign through the
geometric center.
CASE B: resultant force acts normal to the face of the sign at a distance
from the geometric center toward the windward edge equal to
0.2 times the average width of the sign.
For B/s ≥ 2, CASE C must also be considered:
CASE C: resultant forces act normal to the face of the sign through the
geometric centers of each region.
For s/h 5 1:
The same cases as above except that the vertical locations of the
resultant forces occur at a distance above the geometric center equal
to 0.05 times the average height of the sign.
4.  For CASE C where s/h > 0.8, force coefficients shall be multiplied by
the reduction factor (1.8 - s/h).
5.  Linear interpolation is permitted for values of s/h, B/s and Lr/s other
than shown.
6.  Notation:  B: horizontal dimension of sign, in meters;
h : height of the sign, in meters;
s:  vertical dimension of the sign, in meters;
: ratio of solid area to gross area;
Lr: horizontal dimension of return corner, in meters
Figure 6.2.20 Force Coefficient, Cf for other structures - Method 2 (All heights)
Chapter 2
Chimneys, Tanks, Rooftop Equipment, & Similar Structures
Cross-Section
Type of Surface
h/D
1
7
25
Square (wind normal to face)
All
1.3
1.4
2.0
Square (wind along diagomal)
All
1.0
1.1
1.5
Hexagonal or octagonal
All
1.0
1.2
1.4
Round
#tX/ > 5.3, # in m,
X/ in N m
⁄
Moderately smooth
0.5
0.6
0.7
Rough (D’/D50.02)
0.7
0.8
0.9
Very rough
(D’/D50.08)
0.8
1.0
0.2
Round
#tX/ ≤5.3, # in m,
X/ in N m
⁄
All
0.7
0.8
1.2
Notes:
1. The design wind force shall be calculated based on the area of the structure
projected on a plane normal to the wind direction. The force shall be assumed
to act parallel to the wind direction.
2. Linear interpolation is permitted for h/D values other than shown.
3. Notation:
D :  diameter of circular cross-section and least horizontal dimension of
square, hexagonal or octagonal cross-section at elevation under
consideration, in meters;
D’:  depth of protruding element such as ribs and spoilers, in meters;
H:  height of structure,   meters and
qz: velocity pressure evaluated at height z above ground, in N/m2
Figure 6.2.21 Force coefficient, Cf for other structures - Method 2 (All heights)
Chapter 2
Open Signs & Lattice Frameworks

Flat-Sided Members
Rounded Members
Ôôtõö > ÷. æ, Õ
<0.1
2.0
1.2
0.8
0.1 to 0.29
1.8
1.3
0.9
0.3 to 0.7
1.6
1.5
1.1
Notes:
1. Signs with openings comprising 30% or more of the gross area are classified as
open signs.
2. The calculation of the design wind forces shall be based on the area of all
exposed members and elements projected on a plane normal to the wind
direction. Forces shall be assumed to act parallel to the wind.
3. The area Af consistent with these force coefficients is the solid area projected
normal the wind direction.
4. Notation:
 : ratio of solid area to gross area;
D: diameter of a typical round number, in meters
qz: velocity pressure evaluated at height z above ground in N/m2.
Figure 6.2.22 Force coefficient, Cf for other structures - Method 2 (All heights)
Chapter 2
Table 6.2.8: Basic Wind Speeds, V, for Selected Locations in Bangladesh
Location
Basic Wind
Speed (m/s)
Location
Basic Wind
Speed (m/s)
Angarpota
47.8
Lalmonirhat
63.7
Bagerhat
77.5
Madaripur
68.1
Bandarban
62.5
Magura
65.0
Barguna
80.0
Manikganj
58.2
Barisal
78.7
Meherpur
58.2
Bhola
69.5
Maheshkhali
80.0
Bogra
61.9
Moulvibazar
53.0
Brahmanbaria
56.7
Munshiganj
57.1
Chandpur
50.6
Mymensingh
67.4
Chapai Nawabganj
41.4
Naogaon
55.2
Chittagong
80.0
Narail
68.6
Chuadanga
61.9
Narayanganj
61.1
Comilla
61.4
Narsinghdi
59.7
Cox’s Bazar
80.0
Natore
61.9
Dahagram
47.8
Netrokona
65.6
Dhaka
65.7
Nilphamari
44.7
Dinajpur
41.4
Noakhali
57.1
Faridpur
63.1
Pabna
63.1
Feni
64.1
Panchagarh
41.4
Gaibandha
65.6
Patuakhali
80.0
Gazipur
66.5
Pirojpur
80.0
Gopalganj
74.5
Rajbari
59.1
Habiganj
54.2
Rajshahi
49.2
Hatiya
80.0
Rangamati
56.7
Ishurdi
69.5
Rangpur
65.3
Joypurhat
56.7
Satkhira
57.6
Jamalpur
56.7
Shariatpur
61.9
Jessore
64.1
Sherpur
62.5
Jhalakati
80.0
Sirajganj
50.6
Jhenaidah
65.0
Srimangal
50.6
Khagrachhari
56.7
St. Martin’s Island
80.0
Khulna
73.3
Sunamganj
61.1
Kutubdia
80.0
Sylhet
61.1
Kishoreganj
64.7
Sandwip
80.0
Kurigram
65.6
Tangail
50.6
Kushtia
66.9
Teknaf
80.0
Lakshmipur
51.2
Thakurgaon
41.4
Chapter 2
Open Structures: Trussed Tower
Tower Cross Section
Cf
Square
4.0 2 - 5.9 + 4.0
Triangle
3.4 2 - 4.7 + 3.4
Notes:
1.
For all wind directions considered, the area Af consistent with the specified
force coefficients shall be the solid area of a tower face projected on the plane
of that face for the tower segment under consideration.
2.
The specified force coefficients are for towers with structural angles or
similar flat-sided members.
3.
For towers containing rounded members, it is acceptable to multiply the
specified force coefficients by the following factor when determining wind
forces on such members: 0.51 2  + 0.57   1.0
4.
Wind forces shall be applied in the directions resulting in maximum member
forces and reactions. For towers with square cross-sections, wind forces shall
be multiplied by the following factor when the wind is directed along a tower
diagonal:
1 + 0.75   1.2
5.
Wind forces on tower appurtenances such as ladders, conduits, lights,
elevators, etc., shall be calculated using appropriate force coefficients for
these elements.
6.  Notation:
: ratio of solid area to gross area of one tower face for the segment under
consideration.
Figure 6.2.23 Force coefficient, Cf for other structures - Method 2 (All heights)
Table 6.2.9: Importance Factor, I (Wind Loads)
Occupancy Category1
or
Importance Class
Non-Cyclone Prone
Regions and Cyclone Prone
Regions with
V 5 38-44 m/s
Cyclone Prone Regions with
V > 44 m/s
I
0.87
0.77
II
1.0
1.00
III
1.15
1.15
IV
1.15
1.15
1 The building and structure classification categories are listed in Table 6.1.1
Chapter 2
Table 6.2.10: Terrain Exposure Constants
Exposure
ø
öù (m)
úû
üý
þ_
ü_
c
 (m)
_
ö (m)*
A
7.0
365.76
1/7
0.84
1/4.0
0.45
0.30 97.54 1/3.0
9.14
B
9.5
274.32 1/9.5
1.00
1/6.5
0.65
0.20 152.4 1/5.0
4.57
C
11.5 213.36 1/11.5
1.07
1/9.0
0.80
0.15 198.12 1/8.0
2.13
*4\)5 Minimum height used to ensure that the equivalent height z is greater of
0.6h or 4\).
For buildings with h ≤4\),  4̅  shall be taken as 4\).
Table 6.2.11: Velocity Pressure Exposure Coefficients, }ã and }ö
Height above
ground level, z
Exposure (Note 1)
A
B
C
(m)
Case 1
Case 2
Case 1 & 2
Case 1 & 2
0-4.6
0.70
0.57
0.85
1.03
6.1
0.70
0.62
0.90
1.08
7.6
0.70
0.66
0.94
1.12
9.1
0.70
0.70
0.98
1.16
12.2
0.76
0.76
1.04
1.22
15.2
0.81
0.81
1.09
1.27
18
0.85
0.85
1.13
1.31
21.3
0.89
0.89
1.17
1.34
24.4
0.93
0.93
1.21
1.38
27.41
0.96
0.96
1.24
1.40
30.5
0.99
0.99
1.26
1.43
36.6
1.04
1.04
1.31
1.48
42.7
1.09
1.09
1.36
1.52
48.8
1.13
1.13
1.39
1.55
54.9
1.17
1.17
1.43
1.58
61.0
1.20
1.20
1.46
1.61
76.2
1.28
1.28
1.53
1.68
91.4
1.35
1.35
1.59
1.73
106.7
1.41
1.41
1.64
1.78
121.9
1.47
1.47
1.69
1.82
137.2
1.52
1.52
1.73
1.86
152.4
1.56
1.56
1.77
1.89
Chapter 2
Notes:
1. Case 1:
(a) All components and cladding.
(b) Main wind force resisting system in low-rise buildings designed using
Figure 6.2.10.
Case 2:
(a) All main wind force resisting systems in buildings except those in low-
rise buildings designed using Figure 6.2.10.
(b) All main wind force resisting systems in other structures.
2. The velocity pressure exposure coefficient Kz may be determined from the
following formula:
For 4.57 m ≤ z ≤ zg:
Kz 5 2.01 (z/zg)2/α
For z < 4.57 m:
Kz 5 2.01 (4.57/zg)2/α
Note: z shall not be taken less than 9.1 m for Case 1 in exposure A.
3. α and zg are tabulated in Table 6.2.10.
4. Linear interpolation for intermediate values of height z is acceptable.
5. Exposure categories are defined in Sec 2.4.6.3.
Table 6.2.12: Wind Directionality Factor, }
Structure Type
Directionality
Factor
0*
Structure Type
Directionality
Factor
0*
Buildings
Main Wind Force
Resisting System
Components and
Cladding
Arched Roofs
Chimneys, Tanks, and
Similar    Structures
Square
Hexagonal
Round
0.85
0.85
0.85
0.90
0.95
0.95
Solid Signs
Open Signs and Lattice
Framework
Trussed Towers
Triangular, square,
rectangular
All other cross section
0.85
0.85
0.85
0.95
* Directionality Factor 0 has been calibrated with combinations of loads
specified in Sec 2.7. This factor shall only be applied when used in conjunction
with load combinations specified in Sections 2.7.2 and 2.7.3.
Chapter 2
2.5
Earthquake Loads
2.5.1
General
Minimum design earthquake forces for buildings, structures or components
thereof shall be determined in accordance with the provisions of Sec 2.5. Some
definitions and symbols relevant for earthquake resistant design for buildings
are provided in Sections 2.1.3 and 2.1.4. Section 2.5.2 presents basic earthquake
resistant design concepts. Section 2.5.3 describes procedures for soil
investigations, while Sec 2.5.4 describes procedures for determining earthquake
ground motion for design. Section 2.5.5 describes different types of buildings
and structural systems which possess different earthquake resistant
characteristics. Static analysis procedures for design are described in Sections
2.5.6, 2.5.7 and 2.5.12. Dynamic analysis procedures are dealt with in Sections
2.5.8 to 2.5.11. Section 2.5.13 presents how seismic effects are accounted in the
design and combination of earthquake loading effects in different directions and
with other loading effects. Section 2.5.14 deals with allowable drift and
deformation limits. Section 2.5.15 addresses design of non-structural
components in buildings. Section 2.5.16 presents design considerations for
buildings with seismic isolation systems. Design for soft storey condition in
buildings is addressed in Sec 2.5.17.
2.5.2
Earthquake Resistant Design – Basic Concepts