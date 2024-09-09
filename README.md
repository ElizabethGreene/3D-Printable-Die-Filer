# 3D-Printable-Die-Filer
An open source 3d printable die filer v0.1 alpha

A die filer is a very old tool that uses an external power source to create reciprocating motion for a file.  This allows material removal that is faster and more controlled than hand filing.  It can remove material similar to Side Milling or Slot Milling in a milling machine.  Additionally, when equipped with square or triangular file, it can file a sharp corner e.g. for keyways or gear teeth.

This is an alpha release, and is *not* a production quality tool.  In this state it will cut metal. A demo video in the images folder shows it cutting brass, and I successfully filed a keyway in a steel gear with it.  That said, there is significant room for improvement.

# Danger
 There is a pinch hazard between the bottom of the flexure and the base.  It *_hurts_*. This tool is "only" plastic, but it can still cause painful injuries. This should be covered or corrected in future development.

# Request for feedback
Please open issues or contact the author with feedback, positive or negative.  

# Features
This was specifically designed to use as few non-printed components as possible.  This is accomplished with a compliant mechanism for the linear stage, and using a drill as the power source.  The only hardware required to assemble it are M3 screws, nuts, a washer, and one 608z skate bearing

# Problems/disadvantages and Opportunities for future work
* There are pinch hazards as mentioned in the Danger section.
* The flexure is insufficiently stiff against off-axis forces. Machine filing uses low tool pressure, so it's still usable, but I'd like it to be stiffer.
* The base and worktable can flex under heavy workpieces.
* Supporting the drill works, but is dodgy. A better way to mount that is critical.
* A zip-tie to hold down the drill trigger works, but is dodgy. A clamp would be a better solution.
* * Forking the design to use a dedicated motor merits consideration
* Increase the overall stroke length from 25mm to 35-40
* Adapt an adjustable stroke length mechanism https://youtube.com/shorts/UjDqezJ2Gh0?si=csQhwm905_5Tf_nh
* Increase the flexure linear throw and then pre-stress half of it  at assembly to reduce the inherent stiffness at the center position.
* Add an overarm support
* * This would allow the unit to be used as a scroll saw, an extremely useful tool
* Add work hold-downs
* Consider forking and stretching the design for a power hacksaw
* Edit this documentation to include pictures
* A tilting worktable would be nice.

# Bill of Materials
* 9 M3x30mm Socket Head Cap screws - Flexure to Support Mount screws and Crankshaft reinforcement
* * Designed for DIN 912 spec. socket head cap screws
* * The original was assembled with this Iexcell M3 screw assortment kit from Amazon.
* 8 M3x14mm Socket Head Cap screws - Base to Support and Worktable to Support Mount screws
* 1 M3x5mm Socket Head Cap screw - Bearing Retainer
* 1 M3 washer - Bearing Retainer
* 1 608z Skate Bearing 
* 2 M3x12mm Socket Head Cap screw for File Clamp
* A suitable glue for your filament
* * I used Gorilla SuperGlue
* White Lithium Grease
* * I used "Sta-Lube Multi-Purpose Super White Lithium Grease"
* Files (See Below)

# Files
The file holder is designed to accommodate a variety of different files with shaft diameters from 1/4" to 1/8", down to 2.8mm.
* Harbor Freight "Pittsburgh Needle File Set" or "Central Forge Precision Needle file Set" both work.
* Commercial Die filer files (obsolete and very rare) have a 1/4" round shank and will work.
* Larger files can be made to work by grinding the shank to fit.
* Some files may require enlarging the hole in the work surface 

# Assembly
* Print all parts in the orientations shown in the picture below.
* * The original was printed in Hatchbox PETG on a Prusa Mk3S using the Draft 0.3mm preset
* Bearing
* * Press the bearing into the support
* * Secure the bearing in the support with a M3x5mm screw and washer
* Crankshaft
* * Glue the crank pin into the crankshaft with superglue.
* * Place the crankshaft through the bearing, and secure with the circular clip (circlip)
* * * Note, the circlip groove is chamfered to enable printing.  The angle in the circlip needs to match this chamfer.
* * * A large pair of pliers is helpful installing this clip
* * Drive an M3x30mm screw fully into the crankshaft
* * * This screw reinforces the crankshaft to help prevent failure between layers.
* * * This screw slightly expands the shaft, so it needs to be installed *after* the shaft is installed in the bearing.
* Base
* * Attach the base to the support with 4 M3x14mm screws
* * * The shortest side of the base faces toward the rear, the side that has the circlip and bearing retainer screw.
* Worktop
* * Attach the worktop to the support with 4 M3x14mm screws
* * * The shortest side of the worktop faces toward the rear, the side that has the circlip and bearing retainer screw.
* File Holder clamp
* * Press in two M3 nuts into the back of the Flexure.  This is a tight fit, and pliers may help.
* * Attach the file holder clamp to the flexure with 2 M3x12mm screws.
* * The file holder clamp is reversible.
* * * For large shank files, the concave side should face the flexure.
* * * For small shank files, the convex side should face the flexure.
* Flexure
* * Using 8 M3x30mm screws and nuts, attach the flexure to the support.
* * The file holder clamp should facing forward/out so they are easily removable to change files.
* * The crankshaft pin should engage the slot in the flexure.
* Lubrication
* * Apply a small dot of grease in the crankshaft pin slot in the flexure.

# Usage
* Install a file. 
* Grip the crankshaft with the chuck of a drill.
* * Optional and highly recommended, support the drill so the weight isn't hanging on the crankshaft.
* Optional, clamp the base to a worksurface.
* Using a zip-tie or clamp, turn on the drill.
* Press the work into the moving file.
* If it's making a high pitched chirping sound when cutting, you are pressing too hard.
