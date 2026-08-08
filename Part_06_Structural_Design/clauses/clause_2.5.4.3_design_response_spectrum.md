---
clause: "2.5.4.3"
title: "Design response spectrum"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: ["../json/table_06_6.2.19..json", "../json/table_06_6.2.16.json", "../json/table_06_6.2.14.json", "../json/table_06_6.2.15.json"]
related_diagrams: ["../webp/fig_06_6.2.25.webp", "../webp/fig_06_6.2.26.webp", "../webp/fig_06_6.2.24.webp"]
related_flowcharts: []
---
# Section 2.5.4.3: Design response spectrum

2.5.4.3 Design response spectrum
The earthquake ground motion for which the building has to be designed is
represented by the design response spectrum. Both static and dynamic analysis
methods are based on this response spectrum. This spectrum represents the
spectral acceleration for which the building has to be designed as a function of
the building period, taking into account the ground motion intensity. The
spectrum is based on elastic analysis but in order to account for energy
dissipation due to inelastic deformation and benefits of structural redundancy,
the spectral accelerations are reduced by the response modification factor R.
For important structures, the spectral accelerations are increased by the
importance factor I. The design basis earthquake (DBE) ground motion is
Chapter 2
selected at a ground shaking level that is 2/3 of the maximum considered
earthquake (MCE) ground motion. The effect of local soil conditions on the
response spectrum is incorporated in the normalized acceleration response
spectrum Cs. The spectral acceleration for the design earthquake is given by the
following equation:
s
a
C
R
ZI
S
3
2

(6.2.34)
Where,
C' 5  Design spectral acceleration (in units of Q) which shall not be less
than 0.67cK.C
c 5
Coefficient used to calculate lower bound for C'. Recommended
value for c is 0.11
K 5
Seismic zone coefficient, as defined in Sec 2.5.4.2
. 5  Structure importance factor, as defined in Sec 2.5.5.1
@ 5  Response reduction factor which depends on the type of
structural system given in Table 6.2.19. The ratio
µ
S cannot be
greater than one.
 5  Normalized acceleration response spectrum, which is a function
of structure (building) period and soil type (site class) as defined
by Equations 6.2.35a to 6.2.35d.


B
T
T
η
B
T
T
S
s
C











0
for
1
2.5
1
(6.2.35a)
C
T
T
B
T
Sη
s
C



for
2.5
(6.2.35b)
D
T
T
C
T
T
C
T
Sη
s
C









for
2.5
(6.2.35c)
sec
T
D
T
2
T
D
T
C
T
S η
s
C
4
for
2.5









(6.2.35d)
 depends on S and values of TB, TC and TD, (Figure 6.2.25) which are all
functions of the site class. Constant Cs value between periods TB and TC
represents constant spectral acceleration.
S 5  Soil factor which depends on site class and is given in Table 6.2.16
T 5  Structure (building) period as defined in Sec 2.5.7.2
TB 5  Lower limit of the period of the constant spectral acceleration
branch given in Table 6.2.16 as a function of site class.
TC 5  Upper limit of the period of the constant spectral acceleration
branch given in Table 6.2.16 as a function of site class
Chapter 2
TD 5  Lower limit of the period of the constant spectral displacement
branch given in Table 6.2.16 as a function of site class
η 5  Damping correction factor as a function of damping with a
reference value of η51 for 5% viscous damping. It is given by the
following expression:
55
0
5
10
.
)
/(





(6.2.36)
Where, ξ is the viscous damping ratio of the structure, expressed as a percentage
of critical damping. The value of η cannot be smaller than 0.55.
The anticipated (design basis earthquake) peak ground acceleration (PGA) for
rock or very stiff soil (site class SA) is

2 K. However, for design, the ground
motion is modified through the use of response reduction factor R and
importance factor I, resulting in ;,7+l 5

2 ¸
µ
S ¹. Figure 6.2.26 shows the
normalized acceleration response spectrum Cs for 5% damping, which may be
defined as the 5% damped spectral acceleration (obtained by Eq. 6.2.34)
normalized with respect to ;,7+l . This Figure demonstrates the significant
influence of site class on the response spectrum.
Design Spectrum for Elastic Analysis
For site classes SA to SE, the design acceleration response spectrum for elastic
analysis methods is obtained using Eq. 6.2.34 to compute Sa (in units of g) as a
function of period T. The design acceleration response spectrum represents the
expected ground motion (Design Basis Earthquake) divided by the factor R/I.
Design Spectrum for Inelastic Analysis
For inelastic analysis methods, the anticipated ground motion (Design Basis
Earthquake) is directly used. Corresponding real design acceleration response
spectrum is used, which is obtained by using R51 and I51 in Eq. 6.2.34. The
‘real design acceleration response spectrum’ is equal to ‘design acceleration
response spectrum’ multiplied by R/I.
Site-Specific Design Spectrum
For site class S1 and S2, site-specific studies are needed to obtain design
response spectrum. For important projects, site-specific studies may also be
carried out to determine spectrum instead of using Eq. 6.2.34. The objective of
such site-specific ground-motion analysis is to determine ground motions for
local seismic and site conditions with higher confidence than is possible using
simplified equations.
Chapter 2
Figure 6.2.24 Seismic zoning map of Bangladesh
Chapter 2
Table 6.2.14: Description of Seismic Zones
Seismic
Zone
Location
Seismic
Intensity
Seismic  Zone
Coefficient, Z
1
Southwestern part including Barisal, Khulna,
Jessore, Rajshahi
Low
0.12
2
Lower Central and Northwestern part including
Noakhali, Dhaka, Pabna, Dinajpur, as well as
Southwestern corner including Sundarbans
Moderate
0.20
3
Upper Central and Northwestern part including
Brahmanbaria, Sirajganj, Rangpur
Severe
0.28
4
Northeastern part including Sylhet,
Mymensingh, Kurigram
Very Severe
0.36
Table 6.2.15:  Seismic Zone Coefficient Z  for Some Important Towns of Bangladesh
Town
Z
Town
Z
Town
Z
Town
Z
Bagerhat
0.12
Gaibandha
0.28 Magura
0.12
Patuakhali
0.12
Bandarban
0.28
Gazipur
0.20 Manikganj
0.20
Pirojpur
0.12
Barguna
0.12
Gopalganj
0.12 Maulvibazar
0.36
Rajbari
0.20
Barisal
0.12
Habiganj
0.36 Meherpur
0.12
Rajshahi
0.12
Bhola
0.12
Jaipurhat
0.20 Mongla
0.12
Rangamati
0.28
Bogra
0.28
Jamalpur
0.36 Munshiganj
0.20
Rangpur
0.28
Brahmanbaria
0.28
Jessore
0.12 Mymensingh
0.36
Satkhira
0.12
Chandpur
0.20
Jhalokati
0.12 Narail
0.12
Shariatpur
0.20
Chapainababganj
0.12
Jhenaidah
0.12 Narayanganj
0.20
Sherpur
0.36
Chittagong
0.28
Khagrachari
0.28 Narsingdi
0.28
Sirajganj
0.28
Chuadanga
0.12
Khulna
0.12 Natore
0.20
Srimangal
0.36
Comilla
0.20
Kishoreganj
0.36 Naogaon
0.20
Sunamganj
0.36
Cox's Bazar
0.28
Kurigram
0.36 Netrakona
0.36
Sylhet
0.36
Dhaka
0.20
Kushtia
0.20 Nilphamari
0.12
Tangail
0.28
Dinajpur
0.20
Lakshmipur
0.20 Noakhali
0.20
Thakurgaon
0.20
Faridpur
0.20
Lalmanirhat
0.28 Pabna
0.20
Feni
0.20
Madaripur
0.20 Panchagarh
0.20
Figure 6.2.25 Typical shape of the elastic response spectrum coefficient Cs
Chapter 2
Table 6.2.16: Site Dependent Soil Factor and Other Parameters Defining Elastic Response
Spectrum
Soil type
S
TB(s)
TC (s)
TD (s)
SA
1.0
0.15
0.40
2.0
SB
1.2
0.15
0.50
2.0
SC
1.15
0.20
0.60
2.0
SD
1.35
0.20
0.80
2.0
SE
1.4
0.15
0.50
2.0
Figure 6.2.26 Normalized design acceleration response spectrum for different site classes.
2.5.5
Building Categories