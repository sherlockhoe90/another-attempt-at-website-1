---
layout: about
title: about
permalink: /
subtitle: Hello Internet, welcome to my web page!

profile:
  align: right
  image: about/me_night.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p align="center">This is me</p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---


My name is Nehansh and not Andrey, and I am a member of the CMS experiment at the LHC
since 2006, when I started working on my master’s degree at Moscow
Institute of Physics and Technology (Russia). After that I joined a
PhD program at Northwestern University (US) and defended my PhD thesis
[[1](#ref)] in 2015. Then I moved to a postdoc position at National
Central University (Taiwan), based at CERN, where I was involved in
multiple projects and data analyses. After 3 years, I moved to my
second postdoc position at RWTH Aachen University (Germany), where I
continue my research at CMS experiment. To get an idea about some of
the work I've done read below.

At an early stage of the LHC operation, at *√s = 0.9* and *7 TeV*, I
performed the measurement of charged tracks multiplicity
(a.k.a. *dN∕dη*) [[2](#ref)], which was important for tuning the minimum
bias process in event generators and for the purpose of
cross-calibration between CMS, ATLAS and Alice experiments
[[3](#ref)]. Related to that study was the one, which involved
counting charged tracks and measuring the event rate with one or more
tracks in the central region of the detector. It was used as an
alternative method to determine the luminosity in pp collisions. The
same method was also implemented by ATLAS and Alice experiments thus
allowing for cross comparison between experiments [[4](#ref)].

At the beginning of the CMS operation I also helped to perform
calibration of the Hadronic Calorimeter (HCAL) with isolated tracks
[[9](#ref)]. I wrote a piece of code that collected information of the
tracks and HCAL hits needed as input to the minimization algorithm. I
was also an expert for the HCAL conditions monitoring and maintaining
its database.

When more data was collected, I started to work on some of the most
interesting analyses at CMS – searching for the Higgs boson!

The discovery of the Higgs boson was announced in 2012 using the two
golden channels: *H → ZZ → 4ℓ* and *H → γγ*. Unfortunately, I was not
personally working on those two analysis at the time. Instead, I was
involved in *H → ZZ → 2ℓ2ν* analysis [[5](#ref), [11](#ref)], where I
contributed to data-driven methods for *tt* background estimation, a
clean-up procedure of the detector noise events, the performance study
of various missing energy variable definitions and optimization of the
analysis selection. I then also worked on *H → ZZ → 4ℓ* decay and
explored the multi-class MVA tools in TMVA package for the purpose of
spin/parity hypothesis separation of the newly discovered Higgs boson
[[10](#ref)].

In the next stage of the LHC operation at *√s = 8 TeV* I started to
work on a new channel of the Higgs boson decay: *H → γ*γ → ℓℓγ*
(referred to as *Dalitz* decay), which lead to the paper publication
[[8](#ref)] and my PhD thesis [[1](#ref)]. This channel has a small
branching fraction in the Standard Model (SM), such that we do not
expect to observe it with the current data. However, an enhancement of
the production in the theories beyond the Standard Model (BSM) is
possible. In the analysis we set an upper limit on the decay rate of
this channel at about 6 times the SM prediction for *m<sub>H</sub> =
125 GeV*, at *√s = 8 TeV*, see Figure **1**. A couple years after that
we also released the same analysis of the data set at *√s = 13 TeV*. I
was involved in that analysis as well, helping NCU students to perform
the study. This time it was combined with a related *H → Zγ* search
and the combined upper limit is now about 2 times the SM prediction
[[7](#ref)]. 

<div class="row">
	<div class="col"></div>
	<div class="col-sm-0 mt-3 mt-md-0 px-sm-4">
	{% include figure.html path="assets/img/about/hllg_limits.png" title="The upper limit of the Higgs boson Dalitz decay branching fraction" class="img-fluid rounded z-depth-1" %}
    </div>	
</div>

<div class="caption-right">
Figure 1: The upper limit of the Higgs boson Dalitz decay branching fraction, relative to its SM prediction at 8 TeV.
</div>


Starting my postdoc position at NCU I also joined another analysis: a
search for the pair production of the Higgs bosons at the LHC. I was
one of the main contributor to the di-Higgs search in the decay mode
to two b-quarks and two photons, *HH → bbγγ*, at 13 TeV. Similarly to
the *H → ℓℓγ* analysis, the Higgs boson pair production cross section
is too small to be measured during the LHC Run-2. Nevertheless, this
cross section can be enhanced in many BSM scenarios through both
resonant and non-resonant production mechanisms. The case of the
resonant production, *pp → X → HH*, where X represents the Graviton or
Radion particles, is a powerful way to probe some of the most
interesting BSM models with warped extra dimensions. The *HH → bbγγ*
decay channel has the best sensitivity of the non-resonant searches
and the resonant searches at low masses (*m<sub>X</sub> = 250 - 400
GeV*). Our recent results [[6](#ref)] set a limit at about 20 times
the SM prediction on the di-Higgs production in this decay channel. As
a part of this analysis we have also performed a scan over trilinear
Higgs coupling, *κ<sub>λ</sub>*, shown in Figure **2**.

<div class="row">
	<div class="col"></div>
	<div class="col-sm-0 mt-3 mt-md-0 px-sm-4">
	{% include figure.html path="assets/img/about/KLscanResult.png" title="The upper limit on pp → HH → bbγγ process, depending on the trilinear Higgs boson coupling" class="img-fluid rounded z-depth-1" %}
    </div>	
</div>

<div class="caption-right">
Figure 2: The upper limit on *pp → HH → bbγγ* process, depending on the trilinear Higgs boson coupling κ<sub>λ</sub>.
</div>


Besides the physics analyses I did service work for the CMS Beam
Radiation Instrumentation and Luminosity group (BRIL). Within this
group, from 2011 until 2018, I was responsible for the operation of
the Beam Pickup Timing system (BPTX), which provides beam trigger
signals to the Level-1 trigger system and subsystems of the BRIL
group. I commissioned BPTX subsystem in Run-1 and Run-2 data-taking
periods, and supported it throughout the whole CMS operation during
that time.  In addition to the beam triggers, the BPTX system provides
a real-time measurement of the beam timing at the interaction point,
*Δt(b1 -b2)* (aka cogging), which is crucial for the longitudinal
alignment of the collision point at CMS. This measurement is performed
via an oscilloscope acquisition and a plot like the one on Figure
**3** is a result of such measurement. A displacement of this value
from zero indicates a displacement of the collision point at CMS
detector by a proportional amount. At CMS displacements smaller than
*0.15 ns* are acceptable for normal vertex reconstruction. As a part of
this work I have also developed a xDAQ monitoring application, which
can display the measurements for shifters in the run control room.


<div class="row">
	<div class="col-sm"></div>
	<div class="col-sm-9 mt-3 mt-md-0 px-sm-4">
	{% include figure.html path="assets/img/about/fill_4879_cogging.png" title="Cogging measurement in LHC FILL 4879" class="img-fluid rounded z-depth-1" %}
    </div>	
</div>

<div class="caption-right">
Figure 3: Cogging measurement in one of the LHC FILLs with Stable Beams. The (unusual) sinusoidal oscillation are found to be correlated with the temperature changes in one of the RF system of the LHC.
</div>


Between 2016 and 2018 I participated in the beam tests for the future
High Granularity Calorimeter (HGCAL) of CMS. In 2016 we tested single
diode sensors where I helped with their *I-V*, *C-V* characterization
before the test beam. Then, with the test beam data I measured the
time resolution and its dependence on the irradiation dose to the
sensor [[12](#ref)]. In 2017 we had multiple full Hexagon modules
composed of many sensors and we were able to measure energy resolution
of protons and electrons from the test beam particles. I was involved
in preparing the DAQ front-end software, based on the *euDAQ*
framework written and supported by DESY. I participated in the
data-taking in three beam test sessions in 2017, and in the beam test
in Summer of 2018.

During the years in CMS I have done numerous central shifts for DQM,
Trigger and BRIL systems, including the on-call expert shifts for the
BRIL group.

At the moment I continue to work on CMS experiment with RWTH Aachen
group. My current project is a search for Higgs boson decays to charm
quarks. With current data this process is not yet accessible to the
level of the SM, but an upper limit on some new physics models could
be achieved. In 2022 in CMS we released two searches for *H → cc*
decay with the full Run-2 data set collected between 2016
and 2018. One analysis is done in VH production channel, and we set the
stringiest limit to date on the *H → cc*, at 14 times the SM value
[[13](#ref)]. It also leads to the stringiest constraint on the
coupling of the Higgs boson to charm quark, 1.1 < |κ<sub>c</sub>| <
5.5. The second analysis is looking into gluon-fusion production
channel of the Higgs and here we set a limit at 45 times the SM
[[14](#ref)]. Recently I reported these results, along with other ways
one can constrain Higgs-charm coupling at LHC, at ICHEP-2022
conference. The proceedings for my talk can be found at [[15](#ref)].


Thanks for reading. For more detailed info see my [CV](./cv).


### <a name="ref">References</a>

[1] Andrey Pozdnyakov, “Search for the Higgs Boson Decays to a Photon
and Two Leptons with Low Dilepton Invariant Mass”, Northwestern
University, Dec. 2015,
[CMS-TS-2016-001](https://web.archive.org/web/20200824175357/http://cds.cern.ch/record/2119232),
[CERN-THESIS-2015-256](https://web.archive.org/web/20200824175357/http://cds.cern.ch/record/2119232),
[[arXiv:1601.00790](https://web.archive.org/web/20200824175357/https://arxiv.org/abs/1601.00790)]

[2] “Pseudorapidity distributions of charged particles in pp
collisions at √s = 7 TeV with at least one central charged particle”,
CMS Collaboration,
[CMS-PAS-QCD-10-024](https://web.archive.org/web/20200824175357/https://cds.cern.ch/record/1341853),
Apr. 2011

[3] “[Minimum Bias and Underlying Event Working Group documents](https://web.archive.org/web/20200824175357/https://lpcc.web.cern.ch/content/mb-ue-wg-documents)”

[4] “Luminosity Study: Events Selected with a Central Track” Andrey
Pozdnyakov, Michael Schmitt, Mayda Velasco, CMS Internal presentation,
CMS-DP-2011-004, Jun. 2011

[5] “Search for the standard model Higgs boson in the H → ZZ → 2ℓ2ν
channel in pp collisions at √s = 7 TeV”, CMS Collaboration, 2012,
[JHEP 03, 040 (2012)](https://web.archive.org/web/20200824175357/https://link.springer.com/article/10.1007/JHEP03(2012)040),
[[arXiv:1202.3478](https://web.archive.org/web/20200824175357/https://arxiv.org/abs/1202.3478)]

[6] “Search for Higgs boson pair production in the final state
containing two photons and two bottom quarks in proton-proton
collisions at √s = 13 TeV”, CMS Collaboration, [2018, Phys. Lett. B
788](https://web.archive.org/web/20200824175357/https://doi.org/10.1016/j.physletb.2018.10.056),
[CMS-HIG-17-008](https://web.archive.org/web/20200824175357/https://cds.cern.ch/record/2621190),
[doi:10.1016/j.physletb.2018.10.056](https://web.archive.org/web/20200824175357/https://doi.org/10.1007/JHEP11(2018)152),
[[arXiv:1806.00408](https://web.archive.org/web/20200824175357/https://arxiv.org/abs/1806.05996)]

[7] “Search for the standard model Higgs boson in the dilepton plus
photon channel in pp collisions at √s = 13 TeV, CMS Collaboration,
2018, [JHEP 11, 152
(2018)](https://web.archive.org/web/20200824175357/https://link.springer.com/article/10.1007%2FJHEP11%282018%29152),
[CMS-HIG-17-007](https://web.archive.org/web/20200824175357/https://cds.cern.ch/record/2624385),
[doi:10.1007/JHEP11(2018)152](https://web.archive.org/web/20200824175357/https://doi.org/10.1007/JHEP11(2018)152),
[[arXiv:1806.05996](https://web.archive.org/web/20200824175357/https://arxiv.org/abs/1806.05996)]

[8] “Search for a Higgs boson decaying into γ*γ to ℓℓγ with low
dilepton mass in pp collisions at √s = 8 TeV”, CMS Collaboration,
2015, [Phys. Lett. B
753](https://web.archive.org/web/20200824175357/https://www.sciencedirect.com/science/article/pii/S0370269315009879),
[CMS-HIG-14-003](https://web.archive.org/web/20200824175357/https://cds.cern.ch/record/2033215),
[doi:10.1016/j.physletb.2015.12.039](https://web.archive.org/web/20200824175357/https://doi.org/10.1016/j.physletb.2015.12.039),
[[arXiv:1507.03031](https://web.archive.org/web/20200824175357/https://arxiv.org/abs/1507.03031)]

[9] A. Anastassov et al., “Single Particle Response in the CMS
Calorimeter”, CMS Internal AN-2010/179

[10] G. Bauer, et al., “Examination of an excess of events in the
search for the standard model Higgs boson in the H → ZZ* → 4ℓ
channel”, CMS Internal AN-2012/414

[11] Joe Bochenek, et al., “Search for the Higgs boson in the H → ZZ*
→ 2ℓ2ν decay channel in pp collisions with the CMS detector”, CMS
Internal AN-2012/138

[12] N. Akchurin et al, “First beam tests of prototype silicon modules
for the CMS High Granularity Endcap Calorimeter”, [2018 JINST 13
P10023](https://iopscience.iop.org/article/10.1088/1748-0221/13/10/P10023)

[13] CMS Collaboration, "Search for Higgs boson decay to a charm
quark-antiquark pair in proton-proton collisions at √s = 13 TeV",
[CMS-HIG-21-008](https://cds.cern.ch/record/2809290),
CERN-EP-2022-081, Accepted for publication in Phys. Rev. Lett.,
[[arXiv:2205.05550](http://arxiv.org/pdf/2205.05550)]
  
[14] CMS Collaboration, "Inclusive search for a boosted Higgs boson
decaying to a charm quark pairs in proton-proton collisions at √s = 13
TeV", [CMS-PAS-HIG-21-012](https://cds.cern.ch/record/2809929)

[15] Andrey Pozdnyakov, "Constraints on the Higgs-charm coupling by
CMS", in proceedings of ICHEP-2022 conference, PoS(ICHEP2022)505,
(2022)
