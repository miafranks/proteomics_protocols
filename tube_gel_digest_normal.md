# Tube gel digestion
### Developed in the Saito Lab by Vladimir Bulygin and Dawn Moran; adapted here by Noelle Held. See also Lu and Zhu Mol Cel Proteomics 2005

### Materials
* Use protein low bind plastics OR you can use ethanol washed 0.5mL and 2mL tubes, one each per sample. To wash - rinse 1x in clean ethanol, allow to air dry in a dust free environment such as a fume hood. This reduces contamination by plasticizers. <br>
* At least 25ug sample protein (can be less, but more difficult)<br>
* Shaker <br>
* Centrifuge <br>
* Nanodrop <br>

### Chemicals
Make everything in LCMS grade H2O, use only LCMS grade solvents<br>
* 1M Tris HCL, pH 7.5<br> 
* 40% Bis-acrylmide L 29:1<br>
* Ambic 25 (25mM ammonium bicarbonate)<br>
* TE buffer (10mM tris HCL, 1mM EDTA in water)<br>
* gel fix solution (50% Ethanol, 10 acetic acid in LC water) - shared shelf stable<br>
* gel destain solution (50% methanol, 10% acetic acid in LC water) - shared shelf stable<br>
* 50/50 wash (50% ACN:50% 25mM ammonium bicarbonate) - shared shelf stable<br>
* LCMS grade acetonitrile - we have a small bottle of decanted shared shelf stable<br>
* 10mM dithiothreitol (DTT) in ambic25 (make fresh solution) (1.55mg/mL) - DTT powder is in the freezer <br>
* Ammonium bicarbonate solution 25mM, referred to as Ambic25. We usually make this by diluting an Ambic 100mM solution as needed. shared 4C stable <br>
* 55mM iodacetamide (IODA) in ambic 25 (9.3mg/mL) - protect from heat and light - IODA powder is in the freezer <br>
* TEMED (full concentration) - in corrosive cabinet <br>
* 1% ammonium persulfate (10mg/mL) - made fresh, usually we make 1mL even though it is often too much. <br>
* Peptide extraction buffer: 50% LCMS Acetonitrile, 5% formic acid in water (LCMS grade) - shared shelf stable 

### Preparation
## Day 1
1. Prepare premix on ice: 1 part Tris HCL, 3 parts 40% Bis-acryl L (typically 252uL Tris HCL, 736.5uL Bis-acryl L which makes enough for 9 samples). To calculate excess premix for your samples: 110ul * number of samples / 1000 = _______________ mL of premix that you need. Round up to nearest mL: ___________________ mL. Multiply nearest mL by 252 = _________________ uL Tris HCl, multiply by 736.5 = __________________ uL Bis-acryl L. <br>
2. Prepare Ambic 25: 

## Day 2
2. Prepare fresh DTT and IODA solutions (or use previously frozen but be suspicious of solutions that underwent more than 1 freeze/thaw cycle). You will need about 600ul of each per sample. DTT is 1.55mg/mL. mL DTT needed = 600 x number of samples/ 1000 = __________________ mL (add a few mL for safety) x 1.55mg = _______________ mg in ambic25 and IODA needed = 600 x number of samples/ 1000 = __________________ mL (add a few mL for safety) x 9.3 mg = _______________ mg in ambic25.
3. Decide amount of protein to digest (An ideal goal is 25-50ug and up to 100ug digestions; we have digested as little as 10ug very reliably, and 1ug successfully). Note trade off between digesting a lot (need lots of expensive trypsin). 
4. Fill out the following table adjusting the final volume of TE buffer to equal a 200uL final gel volume given the volume of sample solution you need to add to equal the desired amount of protein digested (ug). 

| Sample  | Sample  conc | Vol to Digest | Premix | TE   | APS | TEMED | Final Vol |
|-------- |--------------|---------------|--------|------|-----|-------|-----------|
|         |              |               | 103    |      | 7   |   3   | 200       |
|         |              |               | 103    |      | 7   |   3   | 200       |
|         |              |               | 103    |      | 7   |   3   | 200       |
|         |              |               | 103    |      | 7   |   3   | 200       |
|         |              |               | 103    |      | 7   |   3   | 200       |
|         |              |               | 103    |      | 7   |   3   | 200       |
|         |              |               | 103    |      | 7   |   3   | 200       | <br>


### Protocol
## Day 1
* Place sample in clean 0.5mL tube, then add TE buffer in volume recorded above (calculate such that final volume is 200uL)
* Add 103uL Premix to each sample
* Add 3uL TEMED, and then 7uL APS and vortex. Work quickly. I usually add TEMED to all samples, then vortex, then add APS one by one vortexing each as I go. Volumes and concentrations are critical at this stage. Be sure the APS and TEMED both make their way into solution. If the gels do not cure, usually it means either the APS or TEMED concentrations are incorrect or the solution was not properly mixed. If the sample is precious, you can add a small amount of TEMED and APS, vortex, and see if the gels will cure. However, this will result in different crosslinking across samples which may affect digestion efficiency, so avoid this if possible (e.g. start over if there is enough sample).
* Allow to polymerize in thermomixer 1hr at 20C with no shaking START:
* Add 200uL gel fix solution to gels, incubate RT 20min
* Remove liquid, transfer gels to 2mL tubes (use a 200mL pipette tip to unstick the gels from the tubes)
* fix in 1200-1600uL gel fix solution (enough to cover) at RT 350RPM for 30 min. START:
* Remove liquid, add 1600uL destain solution and incubate 30 min RT 350RPM. This is not necessary if your gel was not stained (in this protocol, there is no stain so you can skip this step) START:
* Remove liquid, decant gels onto a clean surface and cut into 1mm cubes with a clean scalpel or razor blade, return to tube. <u> Note that here we have been experimenting with gel crushers in the centrifuge for higher throughput.</u> 
* Add 1mL 50:50 wash, shake 350RPM for 1hr. 
<u> Note: This is a good place to break, gels can remain in incubator over night in the 50/50 wash if needed </u>
<u> Note: This may be an opportunity to transfer gels to a well-plate format (e.g. 96 deep well plates) allowing use of a multichannel pipette for the remaining steps. </u>

## Day 2
* Remove first 50:50 wash solution, repeat wash step for 1 hour
* Dehydrate gels by adding 0.8mL acetonitrile, vortex, incubate RT 5-10min and remove supernatant. Repeat 2x until gels pieces are hard, crunchy, and white. 
* Add 600uL DTT solution, mix 1hr 56C 350RPM
* Remove liquid with a pipette tip, and note how much liquid absorbed by the gels (to calculate hydrated gel volume)
* Add 600uL Ambic 25, vortex, and remove (rinse step)
* Add 600uL Ioda solution, incubate 1hr RT 350RPM in the dark (cover with foil)
* Remove any remaining Ioda, add 1mL ambic25, vortex, incubate 5-10min RT 350RPM until hydrated and remove solution
* Dehydrate with 0.8mL ACN, 10min room temperature and remove solution, repeat 2x as before until hard and crunchy. 
* Meanwhile, resuspend 100ug promega trypsin gold in 1000uL ambic on ice, allow to sit at least 30 mins to dissolve fully with very gentle vortexing OR use previously reconstituted trypsin, be sure you are using the correct concentrations as we have different protocols with different trypsin solutions. 
* The desired trypsin:protein ratio in the digestion solution is 1:20 ug:ug. Calculate the desired concentration of trypsin based on the amoint of your protein to reach this amount below:

| Sample | ug protein | ug trypsin 1:20 | volume pellet | ug trypsin/ vol pellet |   | vol  trypsin | vol ambic |
|--------|------------|-----------------|---------------|------------------------|---|--------------|-----------|
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |
|        |            |                 |               |                        |   |              |           |

* Add trypsin to reach the desired ug of trypsin (1 ug trypsin enzyme per 20ug of experimental protein). Then add ambic25 to cover the gels. Spot check the pH of the solutions in a few samples using a pH strip (drop 5uL of solution onto the strip). The pH should be ~8, if not adjust it.
* Incubate at 37C for 20mins. Then, check that the gels are completely covered (but avoid having excess liquid, you want the gels to be just about hydrated and covered). Add minimal amount of Ambic 25 to ensure rehydrated gels are covered with liquid if needed.
* If new trypsin was reconstituted, freeze any extra trypsin at -80C in small aliquots to be used later and LABEL VERY WELL.
* Vortex, briefly spin down and incubate 37C 350RPM overnight. Spot check the pH of the solutions in a few samples using a pH strip (drop 5uL of solution onto the strip). The pH should be ~8, if not adjust it. 

## Day 3
* END of digestion period:
* Spin down, collect liquid supernatant into clean 1.5mL tubes
* Add 50uL peptide extraction buffer, vortex, incubate 20mins RT
* Spin down and collect suspension, combine with liquid supernatant from above
* Repeat extraction step, combining the suspensions
* Spin the samples (supernatant) 20mins at high speed to remove any remaining debris
* Collect the top 90% off the centrifuged samples and concentrate on speed vac on low (as needed). Note the volumes and calculate the final estimated concentration of protein. Typically we seek 1ug/uL mixtures that are later diluted to 0.1ug/uL in Buffer B and acidified to pH 4 for LC-MS/MS analysis. 
    * If speedvac unavailable, store in -80 after collecting 90%


| Sample | ug protein digested | Volume of sample after concentrating | Final concentration |
|--------|---------------------|------------------------------------- |---------------------|
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |
|        |                     |                                      |                     |


### Waste 
## Chemicals 

## Others 



