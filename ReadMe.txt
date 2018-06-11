J/AJ/138/159   NGC 6819 stellar radial-velocity and photometry    (Hole+, 2009)
================================================================================
WIYN open cluster study.
XXIV. Stellar radial-velocity measurements in NGC 6819.
    Hole K.T., Geller A.M., Mathieu R.D., Platais I., Meibom S., Latham D.W.
   <Astron. J., 138, 159-168 (2009)>
   =2009AJ....138..159H
================================================================================
ADC_Keywords: Clusters, open ; Radial velocities ; Photometry, CCD ;
              Photometry, UBVRI ; Photometry, infrared
Keywords: open clusters and associations: individual (NGC 6819) -
          techniques: radial velocities

Abstract:
    We present the current results from our ongoing radial-velocity (RV)
    survey of the intermediate-age (2.4Gyr) open cluster NGC 6819. Using
    both newly observed and other available photometry and astrometry, we
    define a primary target sample of 1454 stars that includes
    main-sequence, subgiant, giant, and blue straggler stars, spanning a
    magnitude range of 11<=V<=16.5 and an approximate mass range of
    1.1-1.6M_{sun}_. Our sample covers a 23 arcminute (13pc) square field
    of view centered on the cluster. We have measured 6571 radial
    velocities for an unbiased sample of 1207 stars in the direction of
    the open cluster NGC 6819, with a single-measurement precision of
    0.4km/s for most narrow-lined stars. We use our RV data to calculate
    membership probabilities for stars with >=3 measurements, providing
    the first comprehensive membership study of the cluster core that
    includes stars from the giant branch through the upper main sequence.
    We identify 480 cluster members. Additionally, we identify
    velocity-variable systems, all of which are likely hard binaries that
    dynamically power the cluster.

Description:
    There are four sources of CCD BV photometry available to us for the
    cluster: RV98, Kalirai et al. (2001AJ....122..266K, hereafter K01),
    and two unpublished sets taken by members of the WOCS (WIYN Open
    Cluster Study) collaboration.

    The two sets of WOCS photometry were obtained at what was the KPNO and
    is now the WIYN7 0.9m telescope. In 1998 March, C. Dolan & R. Mathieu
    took BV CCD images to begin this RV project, hereafter called Phot98.
    These observations used the Tektronics CCD (T2KA) at f/7.5.

    The WOCS UBVRI study (hereafter Phot03) is based on images obtained
    with the SITe S2KB CCD camera (pixel size 0.60"), yielding an FOV
    of 20'.

    In total, we have observed 90 pointings on NGC 6819 over 35 separate
    observing runs on the WIYN 3.5m.

    The CfA RV measurements were obtained with two nearly identical
    instruments on the Multiple Mirror Telescope and the 1.5m
    Tillinghast Reflector at the Whipple Observatory atop Mt. Hopkins,
    Arizona.

File Summary:
--------------------------------------------------------------------------------
 FileName   Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe         80        .   This file
table1.dat    108     1305   The NGC 6819 WOCS photometry database
table2.dat    102     1207   The NGC 6819 WOCS radial-velocity database
--------------------------------------------------------------------------------

See also:
    J/MNRAS/358/795 : Variable stars in NGC 6819 field (Street+, 2005)

Byte-by-byte Description of file: table1.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label    Explanations
--------------------------------------------------------------------------------
   1-  6  I06   ---     WOCS     [1001/115030] WIYN Open Cluster Study
                                 identification (G1)
   9- 14  F6.3  mag     Vmag     ? Phot98 project V band magnitude
  16- 21  F6.3  mag     B-V      ? Phot98 project (B-V) color index
  23- 28  F6.3  mag     V-R      ? Phot98 project (V-R) color index
  30- 35  F6.3  mag     V-I      ? Phot98 project (V-I) color index
  38- 43  F6.3  mag     Vmag1    ? Phot03 project V band magnitude
  45- 50  F6.3  mag     B-V1     ? Phot03 project (B-V) color index
  53- 58  F6.3  mag     Vmag2    ? Rosvick & Vandenberg (1998AJ....115.1516R)
                                   V band magnitude
  60- 65  F6.3  mag     B-V2     ? Rosvick & Vandenberg (1998AJ....115.1516R)
                                   (B-V) color index
  68- 73  F6.3  mag     Vmag3    ? Kalirai et al. (2001AJ....122..266K)
                                   V band magnitude
  75- 80  F6.3  mag     B-V3     ? Kalirai et al. (2001AJ....122..266K)
                                   (B-V) color index
  83- 88  F6.3  mag     Jmag     ? 2MASS J band magnitude
  90- 95  F6.3  mag     J-Ks     ? 2MASS (J-Ks) color index
  99-102  I4    ---     A74      ? Auner (1974A&AS...13..143A) identification,
                                   <NGC 6819 NNN> in Simbad
 106-108  I3    ---     S72      ? Sanders (1972A&A....19..155S) identification,
                                   <[S72b] NGC 6819 NNN> in Simbad
--------------------------------------------------------------------------------

Byte-by-byte Description of file: table2.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  6  I06   ---     WOCS      WIYN Open Cluster Study identification (G1)
   8-  9  I2    h       RAh       Hour of Right Ascension (J2000)
  11- 12  I2    min     RAm       Minute of Right Ascension (J2000)
  14- 18  F5.2  s       RAs       Second of Right Ascension (J2000)
      19  A1    ---     DE-       Declination sign
  20- 21  I2    deg     DEd       Degree of Declination (J2000)
  23- 24  I2    arcmin  DEm       Arcminute of Declination (J2000)
  26- 29  F4.1  arcsec  DEs       Arcsecond of Declination (J2000)
  31- 35  F5.2  mag     Vmag      Averaged V band magnitude
  37- 40  F4.2  mag     B-V       Averaged B-V color index
  42- 43  I2    ---     N1        Number of WIYN RV measurements
  45- 46  I2    ---     N2        Number of CfA RV measurements
  48- 54  F7.2  km/s    RV        Mean radial velocity
  56- 60  F5.2  km/s  e_RV        Standard error of RV (1)
  62- 67  F6.2  ---     e/i       ? external/internal error ratio (2)
  69- 70  I2    %       Mmb       ? Calculated RV membership probability
  72- 74  A3    ---     bin       Binarity classification (3)
  76- 82  F7.3  km/s    gamma     ? Center-of-mass radial velocity {gamma}
  84-102  A19   ---     Com       Additional comment
--------------------------------------------------------------------------------
Note (1): If we only have a single measurement, the WIYN or CfA measurement
     precision is given instead, as appropriate. For binaries with orbital
     solutions, we provide the error on {gamma} from the orbital fit in
     this column instead.
Note (2): Where "e" is the standard deviation of the RV measurements for
     the star, and "i" is our measurement precision.
Note (3): classifications codes as follows (section 6.3):
   SM = single member
   SN = single non-member
   BM = binary member
   BN = binary non-member
  BLM = binary likely member
  BLN = binary likely non-member
   BU = binary with unknown membership
    U = unknown
--------------------------------------------------------------------------------

Global notes:
Note (G1): Here, we introduce the WOCS numbering system, based on V magnitude
   and radial distance from the cluster center. Separate one-dimensional
   Gaussian fits in right ascension (RA) and declination (DE) to the cluster's
   apparent density profile (for stars with membership probability p>50%)
   provides the following new J2000 center 19:41:17.5+40:11:47.
   Around this center, annuli of 30" width are drawn, and in each ring the stars
   are sorted in increasing order of their V magnitudes (i.e., the brightest
   stars have the lowest numbers). If a star is missing a measurement of its V
   magnitude, it is estimated from the 2MASS catalog using the empirical
   relationship defined above. The WOCS identification number is the three digit
   star number followed by the three digit annulus number (e.g., the star 001003
   is the brightest star in the third annulus).
   Sources are identified as <[HGM2009b] WOCS NNNFFF> in Simbad.
--------------------------------------------------------------------------------

History:
    From electronic version of the journal

References:
 von Hippel et al.,       Pap I       1998AJ....116.1789V
 Sarajedini, et al.,      Pap II      1999AJ....118.2894S
 Sarajedini,              Pap III     1999AJ....118.2321S
 Sarajedini et al.,       Pap IV      1999AJ....118.2894S
 Barrado                  Pap V       2001ApJ...549..452B
 Sills & Deliyannis,      Pap VI      2000ApJ...544..944S
 Platais et al.,          Pap VII     2001AJ....122.1486P, Cat. J/AJ/122/1486
 Platais et al.,          Pap VIII    2002AJ....124..601P, Cat. J/AJ/124/601
 Stassun et al.,          Pap IX      2002A&A...382..899S, Cat. J/A+A/382/899
 Grocholski & Sarajedini, Pap X       2002AJ....123.1603G
 von Hippel et al.,       Pap XI      2002AJ....124.1555V
 Deliyannis et al.,       Pap XII     2002ApJ...577L..39D
 Barnes                   Pap XIII    2003ApJ...586..464B
 Barnes                   Pap XIV     2003ApJ...586L.145B
 Kafka & Honeycutt,       Pap XV      2003AJ....126..276K
 Grocholski & Sarajedini, Pap XVI     2003MNRAS.345.1015G
 Platais et al.,          Pap XVII    2003AJ....126.2922P, Cat. J/AJ/126/2922
 Mathieu et al.,          Pap XVIII   2004ApJ...602L.121M
 Sarajedini, et al.,      Pap XIX     2004AJ....127..991S
 Kafka et al.,            Pap XX      2004AJ....127.1622K
 Steinhauer & Deliyannis, Pap XXI     2004ApJ...614L..65S
 Meibom & Mathieu,        Pap XXII    2005ApJ...620..970M
 von Hippel et al.,       Pap XXIII   2006ApJ...645.1436V
 James et al.,            Pap XXV
 Platais et al.,          Pap XXVI    2007A&A...461..509P, Cat. J/A+A/461/509
 Kafka et al.,            Pap XXVII
 Giampapa et al.,         Pap XXVIII  2006ApJ...651..444G
 Meibom et al.,           Pap XXIX    2006ApJ...653..621M
 Jeffery et al.,          Pap XXX     2007ApJ...658..391J
 Meibom et al.,           Pap XXXI    2007ApJ...665L.155M
 Geller et al.,           Pap XXXII   2008AJ....135.2264G, Cat. J/AJ/135/2264
 Yadav et al.,            Pap XXXIII  2008A&A...484..609Y, Cat. J/A+A/484/609
 Meibom et al.,           Pap XXXIV   2009ApJ...695..679M, Cat. J/ApJ/695/679
 Platais et al.,          Pap XXXV    2008MNRAS.391.1482P, Cat. J/MNRAS/391/1482
 Geller et al.,           Pap XXXVI   2009AJ....137.3743G, Cat. J/AJ/137/3743
 Meibom et al.,           Pap XXXVII  2009AJ....137.5086M, Cat. J/AJ/137/5086
 Geller et al.,           Pap XXXVIII 2010AJ....139.1383G, Cat. J/AJ/139/1383
 Anthony-Twarog et al.,   Pap XXXIX   2010AJ....139.2034A, Cat. J/AJ/139/2034
 Sarajedini et al.,       Pap XL      2009ApJ...698.1872S
 Chumak et al.,           Pap XLI     2010MNRAS.402.1841C
 Casetti-Dinescu et al.,  Pap XLII    2010AJ....139.1889C
 James et al.,            Pap XLIII   2010A&A...515A.100J, Cat. J/A+A/515/A100
 Platais et al.,          Pap XLIV    2011MNRAS.413.1024P, Cat. J/MNRAS/413/1024
 Meibom et al.,           Pap XLV     2011ApJ...733..115M, Cat. J/ApJ/733/115
 Platais et al.,          Pap XLVI    2011ApJ...733L...1P
 Gosnell et al.,          Pap XLVII   2012ApJ...745...57G
 Geller & Mathieu ,       Pap XLVIII  2012AJ....144...54G
 Platais et al.,          Pap XLIX    2012ApJ...751L...8P
 Cummings et al.,         Pap L       2012AJ....144..137C
 Geller et al.,           Pap LI      2013AJ....145....8G
 Yang et al.,             Pap LII     2013ApJ...762....3Y
 Sandquist et al.,        Pap LIII    2013ApJ...762...58S
 Anthony-Twarog,          Pap LIV     2013ApJ...767L..19A
 Platais et al.,          Pap LV      2013AJ....146...43P, Cat. J/AJ/146/43
                          Pap LVI
 Maderak et al.,          Pap LVII    2013AJ....146..143M
                          Pap LVIII
 Tofflemire et al.,       Pap LIX     2014AJ....148...61T, Cat. J/AJ/148/61
 Milliman et al.,         Pap LX      2014AJ....148...38M, Cat. J/AJ/148/38
 Anthony-Twarog et al.,   Pap LXI     2014AJ....148...51A, Cat. J/AJ/148/51
 Thompson et al.,         Pap LXII    2014AJ....148...85T, Cat. J/AJ/148/85
 Maderak et al.,          Pap LXIII   2015AJ....149..141M
                          Pap LXIV
 Lee-Brown et al.,        Pap LXV     2015AJ....149..121L, Cat. J/AJ/149/121
 Leiner et al.,           Pap LXVI    2015AJ....150...10L, Cat. J/AJ/150/10
 Geller et al.            Pap LXVII   2015AJ....150...97G, cat. J/AJ/150/97
                          Pap LXVIII
                          Pap LXIX
                          Pap LXX
 Milliman et al.,         Pap LXXI    2016AJ....151..152M, cat. J/AJ/151/152
 Anthony-Twarog et al.,   Pap LXXII   2016AJ....152..192A, cat. J/AJ/152/192
                          Pap LXXIII
                          Pap LXXIV
 Cummings et al.,         Pap LXXV    2017AJ....153..128C
 Anthony-Twarog et al.,   Pap LXXVI   2018AJ....155..138A

History:
  * 28-Dec-2011: First online-version
  * 28-Jan-2016: One sequential number corrected in table2

================================================================================
(End)                  Greg Schwarz [AAS], Patricia Vannier [CDS]    15-Nov-2011
