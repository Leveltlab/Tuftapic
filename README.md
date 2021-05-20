# Tuftapic

## Simultaneous 2-photon calcium imaging in dendritic tufts & cell bodies of single pyramidal neurons in mouse V1

AUTHORS

Koen Seignette1, Leander de Kraker1, Chris van der Togt1, Christiaan Levelt1
AFFILIATIONS*

1. Netherlands Institute for Neuroscience, Meibergdreef 47, 1105 BA Amsterdam

corresponding author(s): Christiaan Levelt (c.levelt@nin.knaw.nl)
ABSTRACT*

Although it is thought that cortical feedback is crucial for accurate sensory perception and awareness, it remains unclear how feedforward and feedback information is integrated at the level of individual neurons. It is believed that feedforward sensory information inputs mostly enter dendrites near the cell body, while feedback information about what is to be expected would enter at the dendritic tufts. In this project, we try to understand the integration of feedforward and feedback streams at the level of the individual cell. In one group of mice, we use two-photon calcium imaging of layer ⅔ soma, while in another group of mice we use semi-simultaneous calcium imaging in layer 5 pyramidal somata (in layer 5) as well as their dendritic tufts (layer 1) and apical dendrites (layer ⅔). First, we present awake mice with natural images. In a subset of trials, we occlude either the half of the image that matched the receptive fields of the imaged neurons in V1, or the other half that was outside of their receptive fields. Occluding the half within the receptive field blocks feedforward inputs and allows us to measure feedback inputs. Second, we train the mice to detect a subset of the natural images for milk rewards. We then record the same cells as before training to understand how they change their responses to the natural (occluded) images. The resulting data can be used to decode the stimulus identity of presented natural images to study feedforward and feedback processing.


#### METHODS

Viral injections

For all experiments we used rpb4-cre mice, in which cre is specifically expressed in layer 5 principal neurons. Mice were anesthetized with 5% isoflurane (induction) and 1.6% isoflurane (maintenance) in Oxygen (0.5L/min flow rate) and head-fixed on a stereotax. For layer 5 experiments, we injected cre-dependent AAV1-CAG-dlox-mRuby2-GCaMP6f-dlox (Addgene, final titer ~10E12) at 3 locations in V1 (500 um depth, ~50 nl/location). For layer ⅔ experiments, we injected cre-independent AAV1-hSyn-GCaMP6f (Addgene, final titer ~10E12) at 3 locations in V1 (300 um depth, ~50 nl/location).



Cranial window surgery

A minimum of one week after injection, mice were anesthetized with 4% isoflurane (induction) and 1.6% isoflurane (maintenance) in Oxygen (0.5L/min flow rate). Mice were peri-operatively administered with Metacam (1mg/kg s.c., for analgesia) and dexamethasone (8 mg/kg s.c., to prevent cerebral oedema/inflammation). Mice were head-fixed on a stereotaxic frame and the scalp and soft tissue overlying V1 is incised and the skull was exposed. We fixed a custom-made metal ring (5mm inner diameter) on the centre of V1 using dental cement. A cranial window was made above the right V1 and the dura was exposed. The cranial window was then covered with a double (3+4 mm diameter) glass coverslip and fixed to the metal ring using dental cement (superbond).



Two-photon imaging

Before two-photon imaging, mice were trained to be head-fixed in our setup for a minimum of 3 days (5-30 min per day), during which we presented some visual stimuli (e.g. full screen drifting gratings) to habituate mice to visual stimulation. During two-photon imaging, mice were allowed to freely run on a treadmill. We tracked running speed as well as pupil size and location throughout all recordings.

Imaging was carried out using a two-photon microscope (Neurolabware) controlled by scanbox software running on Matlab. The microscope was equipped with a Ti-sapphire laser (Mai-Tai ‘Deepsee’, Spectraphysics, tuned to 920 nm) and a water immersion Nikon objective (16x zoom (with an imaging zoom of 2.5x), 0.8NA). Semi-simultaneous double-plane imaging was performed with an electrically tunable lens (optotune) with a plane size of 796 x 512 pixels. For layer 5 experiments, imaging was performed at 31Hz per plane, at two planes at a time (15Hz/plane). We first imaged the tufts and apical dendrites simultaneously, followed by the apical dendrites and somas 1 or 2 days later, as our optotune had a maximum range of ~300 um. For layer ⅔ experiments, imaging was performed at 15Hz at a single plane.



Visual stimulation

Visual stimuli were presented on a gamma-corrected Dell monitor using psychophysics toolbox 3 for Matlab. The monitor covered 120 visual degrees in azimuth and 90 in elevation and was placed such that we mostly stimulated the right monocular V1.

RF mapping

Receptive field mapping was performed using 16x12 white and black squares (7.5 degrees size) on a gray background. We presented 3 white and 3 black squares at the same time in random combinations. Stimuli were presented for 0.5 seconds followed by a 1.5 second inter-trial-interval. Each location on the screen was presented 12x with a white and 12x with a black square. Stimuli were warped to correct for distance of the mouse to each pixel on the screen. RFs were mapped online by reverse correlating the activity of a manually drawn region-of-interest over the entire field of view with the RF stimuli. The square eliciting the highest neuronal response was considered the center of the RF.
