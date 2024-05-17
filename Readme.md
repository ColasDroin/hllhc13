## Fork update (ColasDroin)

This branch is completely identical to the one it's been forked from, except for adding the ```lhc.madx``` and ```lhcb4.madx``` sequences, for convenience. These files can be found as well (locally) on CERN afs at ```/afs/cern.ch/eng/lhc/optics/runIII/```.

## Original readme

Optics files are named:

opt_<betxip1>_<betyip1>_<betxip5>_<betyip5>.madx

where the values of beta are in [mm].

The latest round squeeze files are in `squeeze2`.

The following directories contain:
-  squeeze2: production version of the round squeeze
-  squeeze: legacy version of the round squeeze
-  squeeze2_highq7: optics with large Q7 strength
-  squeeze2_lowd2: optics with low beta function in D2
-  squeeze2_lhcb: version of squeeze2 with beta* in IP8
-  squeeze2_nomqw: version of squeeze2 without one MQW in IR7
-  squeeze2_noms14f: version of squeeze2 without sextupole in Q10 and 14F
-  squeeze_flatvh: flat squeeze version
-  squeeze_flatvh2: flat squeeze version2
-  squeeze2old: deprecated version of squeeze2
-  squeeze3_lhcb: updated version of squeeze2_lhcb
-  squeeze4_lhcb: updated version of squeeze2_lhcb
-  squeeze5_lhcb: updated version of squeeze2_lhcb
-  squeeze6_lhcb: updated version of squeeze2_lhcb
-  squeeze_lhcb: deprecated version of squeeze2_lhcb
-  squeeze_noms10: deprecated version of squeeze2_noms10
-  squeeze_noms14f: deprecated version of squeeze2_noms14f
-  squeeze_tables: strength tables for different squeeze
-  presqueeze3: newer version of the presqueeze
-  base2: alternative layout under study
-  aperture: tools and data for apeture files
-  errors: tools related to magnetic imperfection models
-  beambeam: legacy tools related to beam-beam models for MadX and SixTrack
-  beambeam2: newer version of beam-beam tools relying on the SixTrack Beam-Beam expert interface
-  toolkit: general purpose madx script
-  build: tools related to optics matching
-  examples: madx examples
-  arcs: strength definitions related to the arcs
-  ir*: strength definitions related to the different irs
-  deprecated and old: old version of files not to be used
