# COVID-19 Ventilator Projects and Resources and FAQ

An analyzed list of projects to make emergency ventilators in response to COVID-19, focusing on free-libre open source.

PLEASE make pull requests or submit issues too add any project missing from this list.  The comments are entirely my own (possibly not well-informed) opinions and are meant to be helpful to those looking for quick information, not to disparage any project.

# Evaluation of Known Projects

![April 1st, Top Projects](https://user-images.githubusercontent.com/5296671/78171602-50b17400-741a-11ea-863d-a4adabeeb1d4.png)

This image was updated April 1st, 2020. This data may be more easily and currently viewed as a [spreadsheet](https://docs.google.com/spreadsheets/d/1inYw5H4RiL0AC_J9vPWzJxXCdlkMLPBRdPgEVKF8DZw/edit?usp=sharing). Please send me point-of-contact information for each project via an issue, and I will put it in this (very public) spreadsheet.

We would like to thank everyone who has contributed to this effort. In the interest of transparency
and information for the community, we have analyzed all projects we are aware of in terms of criteria 
we believe are essential to successfully deploying an open-source ventilator during the COVID-19 pandemic.
These seven attributes are:
1. Openness
1. Community Support
1. Buildability
1. Functionally Tested
1. Reliability Tested
1. COVID-19 Suitability
1. Clinician Friendly

Each of the projects is evaluated on [5-point scale defined here](https://docs.google.com/document/d/e/2PACX-1vRl9yZ27KvslftcNvweHgH1A81pO8gHL62TWpY_VY-UELWdK9x-4-3hNw3DbkemClzExPsg8RfnxilP/pub) on each of these attributes.
Uses this [link](https://docs.google.com/document/d/1lWXCij-7yrbWUJJx-y4d6dREdYaTkb62iOZDTDbRi0I/edit?usp=sharing) to comment on those attributes.

Our goal is not to rank projects, but to shed light on the state of readiness of these projects, and perhaps
identify things that must be addressed before they can be deployable. Although in times of crises one
may compromise, ventilators are life-critical, last-resort devices that may do more harm than good if they
do not meet stringent requirements. We have largely followed the guidelines of the 
[Rapidly Manufactured Ventilator System](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/874279/RMVS001_Rapidly_Manufactured_Ventilator_Specification__PDF.pdf) criteria set out by the UK.





It is our hope that this will always be out-of-date. That is, we hope projects move so fast that cannot keep up with updating
their progress. We certainly intend no slight to any project. If you believe a project has made progress in category,
is misevaluated, or a new project should be added, please open an issue.

# Essential Reading

I believe these are the three most essential documents to read first:

[A Super-simple Guide to Mechanical Ventilation For Open Source Engineers Designing Ventilators for the COVID-19 Pandemic](https://docs.google.com/document/d/1p-oYUv_6FadipV67g2O5yfnQvpdvZDm4WadYVubhoH4/edit?usp=sharing) -- This was written by me (Robert L. Read). It's my best attempt at an introduction.

[Key Ventilation Specifications](https://e-vent.mit.edu/clinical/key-ventilation-specifications/)

[Rapidly Manufactured Ventilator System](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/876167/RMVS001_v3.1.pdf)


[U.S. ICU Resource Availability for COVID-19](https://sccm.org/getattachment/Blog/March-2020/United-States-Resource-Availability-for-COVID-19/United-States-Resource-Availability-for-COVID-19.pdf?lang=en-US)

[Ventilator Supply Mitigation Strategies: Letter to Health Care Providers](https://www.fda.gov/medical-devices/letters-health-care-providers/ventilator-supply-mitigation-strategies-letter-health-care-providers) (Explains reuse and adaptations of exisiting devices.)

[OSCMS - Ventilator Machines](https://docs.google.com/document/d/1lZWUwIpN2kINxURqP9Tczn2zYqpuVlBSDBypJt76a2Q/edit?usp=sharing)

[Informal notes from a pulmonologist](https://github.com/jcl5m1/ventilator/wiki/Notes-from-chatting-with-a-pulmonologist) speaking with Johnny Lee are also highly relevant.


# Videos

Stephen Kramer compiled and donated with a CC0 license a [spreadsheet](https://github.com/PubInv/covid19-vent-list/blob/master/Covid19_Projects_from_YouTube.xlsx) with 85 projects that have YouTube videos. We have not yet had time to cross reference this or integrate it with our Analysis spreadsheet or this list of projects and resources.

# Most Buildable Projects

These three projects are, in our humble opinion, the closest to being actually buildable by a third party. We do not believe they are ready to built or manufactured in quantity, and have only had the lightest of testing. Furthermore, the COVID-19 disease requires critical care in an ICU; these designs may be excellent for patients with other diseases, such as acute trauma. However, some medical professionals have asserted that more features are needed in the case of ARDS, a common complication of COVID-19, and patients may requires ventilation for many days. These designs are in a poor state of readiness for multi-day treatment, as far as can be determined.


[AmboVent](https://1nn0v8ter.rocks/AmboVent-1690-108) A well-tested design by a large team from the Israeli Air Force. Definitely one to watch. This is the number one low-cost, easily built project since their release of their [plans and code](https://github.com/AmboVent/AmboVent)  on April 2nd! 

[Beatmungsgerät [Respirator]](https://devpost.com/software/diy-beatmungsgerat) - German language site, but appears to be in best state of openness, build reproducibility, monitoring and alarming. Reliability testing uncertain.


[Low-Cost Open Source Ventilator](https://github.com/jcl5m1/ventilator)

Probably best state of buildability at the the time of this writing. The link above is to the repo. The inventor, Johnny Lee, is actively improving the
system as of March 21st, and has called for assistance. It has been pressure-tested. It has a [wiki](https://github.com/jcl5m1/ventilator/wiki).

I recommend the community of makers and volunteers for open-source ventilator design offer Johnny Lee their full assistance.

[Rice OEDK Design: ApolloBVM](https://docs.google.com/document/d/1-DRXnVkJOlDCmvTzh-DgWDxeLSrZTiBYyH0ypzv8tNA/edit?usp=sharing)

This project is well-documented. It is not clear that it has an active team working on it. The document above is dated April 19, 2019, and was almost certainly presented at the OEDK for 2019 at the end of the school year, possibly by graduating 
Seniors. It has been pressure-tested. At present it states it only works for 6 hours without human intervention. It does not appear to have repository.

[Protofy Team OxyGEN](https://oxygen.protofy.xyz/)

This project was active as of March 16th, 2020. It has a [repo](https://github.com/ProtofyTeam/OxyGEN) of design documents.
As of March 16th it has limited control capability.  As of 5 April, there are two versions: ”IP" for large scale manufacturers and "M" for makers.  Version M is fully open source but the documents lag behind the version IP.  
Version IP is a closed consortium of SEAT, protofy.xyz and others, it is my understanding that their documents will be filtered back into the ”M” documents.
Version IP has passed animal trials and the Spanish government agreed hospital clinical trials with COVID19 patients.  
COVID19 ICU patients in Barcelona are using the IP version as of 3 April, video and photos are on a number of news sites.  
Government agreement includes SEAT ramping up their manufacturing line to 400 units a day.  
The government/consortium plan is to rollout wider testing to more hospitals in Catalunya this week, from 6 April.  Human trials will continue this week.
Recommend waiting to built version M until the documents are updated after feedback from clinical trails of version IP.
Discord group: https://discord.gg/zDYmR5

[Open Source Ventilator - OpenLung BVM Ventilator](https://opensourceventilator.ie/) [GitLab repo here](https://gitlab.com/open-source-ventilator/OpenLung)

Fully open (GPL). Aims to adopt bag valve masks, based on designs (not open) from Rice and MIT. Author (Trevor Smale) responded to email. Highly organized, but not buildable at the time of this writing.

[VentilAid](https://www.ventilaid.org/)

Current prototype is pneumatic. 3D printed parts complete, but I can't find complete assembly instructions. They are working on a second electric prototype.

[Mechanical Ventilator Milano (MVM):
A Novel Mechanical Ventilator Designed for Mass Scale Production in
Response to the COVID-19 Pandemics](https://arxiv.org/pdf/2003.10405.pdf)

## Projects Not Yet Buildable (March 21st, 2020)

### Blower/Fan/Pump based


[MIT E-Vent](https://e-vent.mit.edu/) -- This looks like one of the most advance projects. Sadly it is somewhat closed at present, they do not actually offer designs, though they say they will.

['Pandemic ventilator' could offer solution in potential 'worst case' coronavirus scenario](https://www.cbc.ca/news/canada/london/pandemic-ventilator-coronvirus-hospitals-1.5493830)

A well-developed device reported on by Canadian Broadcasting Company. Creator (Mr. John Strupat) may open source design soon. Note that this has a test-lung as part of the system, a very simple and important feature reproducible elsewhere even without this design. Nature of internale design not visible


[A low oxygen consumption pneumatic ventilator for emergency construction during a respiratory failure pandemic](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1365-2044.2009.06207.x)

[Electric Blower Based Portable
Emergency Ventilator](https://digitalcommons.usu.edu/cgi/viewcontent.cgi?referer=https://www.google.com/&httpsredir=1&article=1016&context=spacegrant&fbclid=IwAR1EtJVcxXm82PjGWFCA0t7H_MxNVjuseAePRfxNORr9h4ZQLQ9sNdQjXhc)


[The Pandemic Ventilator](https://docs.google.com/document/d/1Dz7eMgXowFBtBA_0PKzfAXweHnNMbGlIAXPshCbI2Vk/edit?usp=sharing)
[Open Source Pandemic Ventilator (GoFundMe for above)](https://www.gofundme.com/f/open-source-pandemic-ventilator) 

Online funding for development of an Open Source Ventilator. They provide a Google Docs project overview. According to the photo provided it is a CPAP blower type. Impressive document.

#### Reports on Projects with No Designs

[Saving Babies' Lives Starts With Aquarium Pumps And Ingenuity](https://www.npr.org/sections/health-shots/2014/01/03/259436844/saving-babies-lives-starts-with-aquarium-pumps-and-ingenuity)

[Low-Cost Ventilator Wins Sloan Health Care Prize](https://www.medicaldesignandoutsourcing.com/low-cost-ventilator-wins-sloan-health-care-prize/)

### Ambubag based

[Jeff Ebin's Prototpye](https://www.facebook.com/groups/670932227050506?view=permalink&id=675336579943404&scmts=scwspsdd&extid=MnVADGiqBuaYx9KD) and [his valuable document](https://docs.google.com/document/d/1FNRe2GS7ShhJAJu6Ogdl0OAjS0oLJZ-lkPjT1DSAhpI/edit?ts=5e79401f).

Functioning Abmu-bag based model. Not obviously open with no published design, but possibly easy to copy.

[The Pandemic Ventilator](https://www.instructables.com/id/The-Pandemic-Ventilator/)

From 2007. Uses a relatively old and expensive programmable logic controller, but a great starting place. Possibly well tested.

[Hackaday Rex Ventilator V1](https://www.youtube.com/watch?v=pFnB-vOWQmU)

An update of the previous project. No known open-source repo at present.

[Simple device from www.POMO.cl](https://www.facebook.com/groups/670932227050506/permalink/675264606617268/?app=fbl)

Nice video, possibly nice control, no obvious link to replicatable design documents.

[MIT Low Cost Ventilator](https://github.com/RuairiSpain/openVentilator)

Some work from MIT?  Have not had time to evaluate.

[Pandemic Ventilator Project](https://panvent.blogspot.com/2008/02/test-of-pandemic-ventilator-with.html)

Working prototype, currently active.

[Dr. Mujeeb ur Rahman design ](http://www.technologyreview.pk/pakistani-engineer-braves-tragedy-to-develop-low-cost-ventilator/)

Unclear if the design is published. Good data collection.

[CoronavirusMakers](https://gitlab.com/coronavirusmakers)

Currently active. I found it interesting. They are using 'maker' hardware (ie. Arduino MEGA, TB6600 driver, NEMA17 or NEMA23)

[VentilatorPAL](https://freebreathing.org/) Pre-orderable for &euro 370. Claims will be open sourced March 29th. Has repo, but files in odd format (to me).

[Oxford new report](https://www.youtube.com/watch?v=xdZtMgpxnPI) Yet another news report of a project. No information that it is open.

[OpenBreath Italy](https://www.openbreath.it/en/) Sadly not an open design; claims good progress but hard to tell.

[Ad Hoc](https://20100.be/ad-hoc-ventilator/)

[Low-Cost Automated Emergency Ventilator](https://gitlab.com/PerAsperaAdAstra/lcaev) Site a bit unclear, look at the [design log](https://gitlab.com/PerAsperaAdAstra/lcaev/-/wikis/Design%20Log) to understand it

## Systems for Multiple Patients

[Breathing Aid](https://www.breathing-aid.org/homeen) In several langauges, appers to be a large pneumatic circuit design for ventilator many patients at once. Seems to provide CPAP but not varaible bilevel ventilation. Might be good for people who don't require full ventilation in a field hospital.

## Bellows based

[OpenVentilator](https://www.popsolutions.co/en_US/openventilator) -- Seems very well developed on first glance. Uses very accessible parts. With more testing could be successful.

## Fluid-based

[YACoVV - Yet Another (SARS-)CoV(-2)Ventilator](https://github.com/auenkind/YACoVV)
Focuses on the pressure regulating part with an unconventional but very effective solution

### Cuirass/Negative Pressure/Iron Lung base

[Cuirass Ventilator the DIY way](https://www.youtube.com/watch?v=pvrUQCMa3a8&feature=youtu.be)

A valuable and educational video, open in spirit. (Note: this does not provide positive pressure, or the direct inclusion of oxygen. This would be a valuable part of a spectrum of solutions in a catastrophic situation.)

[Cuirass Ventilator](https://github.com/jps2000/Cuirass-Ventilator)

## Related Therapeutic Projects

[Ventialors SOS](https://www.ventilatorsos.com/) VentilatorsSOS is a Berkeley project to repurpos BiPAP and CPAP machines.

## Test Equipment/Projects

[VentMon inline tester and monitor/alarm](https://github.com/PubInv/ventmon-ventilator-inline-test-monitor) is a [Public Invention](https://www.pubinv.org) project seeking to build an inline flow monitor for testing ventilators and for monitoring
them in actual critial care usage.

My own attempt to build a test apparatus that meaasures clinical suitability as well as reliability. Project is just beginning.

[Ventilator Inline Sensor Package](https://hackaday.io/project/170622-visp-ventilator-inline-sensor-package)

[COVID-19 Ventilator Validation Tests](https://github.com/PubInv/covid19-ventilator-validation-tests) is another [Public Invention](https://www.pubinv.org) project that provides a spreadsheet with ~200 validation tests for clinical 
usability and suitability based on the UK [RMVS](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/876167/RMVS001_v3.1.pdf) standard.

More test projects are needed! If you know of a test project, please make a pull request or enter an issue.

# Communities working on Open-Source Ventilators

[EndCoronaVirus (NECSI)](https://www.endcoronavirus.org/)

An associated with [NECSI](https://necsi.edu/), the New England Complex Systems Institute, effort with over 3000 volunteers in its [Slack team](necsi-edu.slack.com), many of them medical professionals. Channels for Ventilator work are prefixed "#response-ventilators".

[HelpfulEngineering](https://www.helpfulengineering.org/)

HelpfulEngineering has over 12,000 volunteers in its [Slack team](helpfulengineering.slack.com). 

[DIY Ventilators](http://diyventilators.com/)

[Pak Innovation Club](http://www.pakengimed.com/ncov/)

[Ventilator Crowd](https://www.ventilatorcrowd.org/) (They have a [repo](https://github.com/ventilatorcrowd/Ventilator-Crowd) with some analysis.)

[#industryvirus](industryvsvirus.de) A German (and German language?) based [LinkedIn](https://www.linkedin.com/groups/8918186/) group. There is also a [slack](https://wirvsvirus.slack.com/archives/G010J7X703G) group.

[1 million Ventilators Project](https://helpwithcovid.com/projects/13-1-million-ventilators)

[1M Ventilators](https://1mventilators.com/) Note: These two projects have almost the same name, but are different, I think.

[Global Ventilator & PPE DIY Collaboration](https://j.mp/C19diyProjects) An international group using WhatsApp for communication. May have projects soon.

[#EngineersAssemble](https://engineersassemble.tribe.so/)

[The Ventilator Project](https://theventilatorproject.org/) Has a gofundme.

[VENTILATORS COLLABORATION NETWORK](https://soptechint.com/ventilators)

# Challenges and Calls for Papers

[HardwareX: Special Issue on Open-Source COVID19 Medical Hardware](https://www.journals.elsevier.com/hardwarex/call-for-papers/special-issue-on-open-source-covid19-medical-hardware) (Submission deadline June 1st, 2020)

[Code Life Ventilator Challenge](https://www.agorize.com/en/challenges/code-life-challenge?t=c55DcF41nZeLDXfG6-Goyg)

[ULTIMATE MEDICAL HACKATHON: HOW FAST CAN WE DESIGN AND DEPLOY AN OPEN SOURCE VENTILATOR?](https://hackaday.com/2020/03/12/ultimate-medical-hackathon-how-fast-can-we-design-and-deploy-an-open-source-ventilator/)

[The Covid Sprint](https://www.covid-sprint.com/) 

[https://covid-global-hackathon.devpost.com/](https://covid-global-hackathon.devpost.com/)

[Opens Source COVID-19 Medical Supplies](https://www.facebook.com/groups/opensourcecovid19medicalsupplies) An excellent resources for supplies in general (focues more on PPE than ventilators)

[Give a Breath - Challenge](https://give-a-breath-challenge.innosabi.com/) Appears to be both a challenge and a community. Opened applications March 25th, judging for second phase April 3rd. Challenge has funding (for prize and a realization fund) of at least €1 million (additional partners and donors invited). Join in and help to save as many lives as possible!

# Potential Grant Resources

[COVID-19 Solutions Fund](https://blog.mozilla.org/blog/2020/03/31/moss-launches-covid-19-solutions-fund/)

# Resources

[U.S. ICU Resource Availability for COVID-19](https://sccm.org/getattachment/Blog/March-2020/United-States-Resource-Availability-for-COVID-19/United-States-Resource-Availability-for-COVID-19.pdf?lang=en-US)

This important document suggests that in the case of a severe epidemic, the US will bottleneck on have enough people trained on ventilators (but also not have enough ventilators, or beds.)

[Medical Ventilator System Basics](https://www.docdroid.net/gval5gc/medical-ventilator-system-basics-a-clinical-guide-by-yuan-lei.pdf)

[Rapidly Manufactured Ventilator System (RMVS)](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/874279/RMVS001_Rapidly_Manufactured_Ventilator_Specification__PDF.pdf)

Note: This is an excellent read and great source of information. However, we have had an MD and respiratory therapist state that it should be taken with some skepticism as an actual minimum set of requirements, asserting that simpler designs with fewer features may also be extremely valuable in a resource-starved shortfall.

[Clinical course and risk factors for mortality of adult inpatients with COVID-19 in Wuhan, China: a retrospective cohort study](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30566-3/fulltext)

This is a very important study in part because it allows us to predict ventilator need (in terms of days) for patients.

[Manufacturing and COVID-19: How you or your organisation could help](https://www.ifm.eng.cam.ac.uk/manufacturing-and-covid-19-ways-your-company-could-help/)

[Open Source Ventilator Project](https://simulation.health.ufl.edu/technology-development/open-source-ventilator-project/)

[Open Source Ventilator](https://github.com/CSSALTlab/Open_Source_Ventilator)

University of Florida, mostly specifications right now, but amoung the best set of quality specifications available:

Overall Design Philosophy
Open source for use worldwide and contributions from others worldwide
(https://github.com/CSSALTlab/Open_Source_Ventilator.git)

[Internet Book of Critical Care (IBCC) : COVID-19](https://emcrit.org/ibcc/covid19/)

[Covid-19 Research and Reports Esp. WRT Modeling](https://covid.idmod.org/#/ResearchandReports)

[Open source ventilator](https://docs.google.com/document/d/1RDihfZIOEYs60kPEIVDe7gmsxdYgUosF9sr45mgFxY8/preview?pli=1#heading=h.l93gl0t8fdvh)

A great overall working document from the people at HelpfulEngineering.

[Indicative Specification for a Rapidly Manufactured Ventilation System (RMVS)](https://www.britishchambers.org.uk/media/get/Specification%20For%20RMVS%20Challenge.pdf)

[Penn Medicine - COVID-19 Hospital Impact Model for Epidemics](https://penn-chime.phl.io/)

A specific but valuable interactive model of hospital admissions

[COVID-19 Open Research Dataset (CORD-19)](https://pages.semanticscholar.org/coronavirus-research)

Massive collection of resources, mostly academic papers AFAIK

[OSCMS - Ventilator Machines](https://docs.google.com/document/d/1lZWUwIpN2kINxURqP9Tczn2zYqpuVlBSDBypJt76a2Q/edit?usp=sharing)

[Specifications for simple open source mechanical ventilator](https://docs.google.com/document/d/1FNPwrQjB1qW1330s5-S_-VB0vDHajMWKieJRjINCNeE/preview)

[Coronavirus Tech Handbook](https://coronavirustechhandbook.com/ventilators)

[FDA Guidance on Conduct of Clinical Trials of Medical Products during COVID-19 Pandemic: Guidance for Industry, Investigators, and Institutional Review Boards](https://www.fda.gov/media/136238/download)

[Handbook COVID-19 Prevention and Treatment](https://www.wapa.com/assets/documents/Handbook%20of%20COVID-19%20Prevention%20and%20Treatment.pdf)

[Principles and Practice of Mechanical Ventilation, 3rd Edition](https://lookaside.fbsbx.com/file/Principles-and-Practice-of-Mechanical-Ventilation-3rd-Edition.pdf?token=AWw3WFewSdPPCZAOKYoSF1XYpRfMzNRyrZe7V_b-I3LBX25xsqrcrgQigtWUHNFxDNJ7XxDFv9voXZvOsr8I1k-p_9QE9IBWqf4sxlfRxRHmhbngaaBsM10K6Wbna4aNlCHtm0fakn2R7viBqlufWW1yeL91ZaM5ljUtfXFZF8_WHQ)

[Virus Simulator](https://github.com/SilverLinings89/VirusSimulator)

A useful resource for programmers as a model; data seems insufficient to accurately model COVID-19 at present although it has a preset for it.

[VENTILATOR ALLOCATION GUIDELINES](https://www.health.ny.gov/regulations/task_force/reports_publications/docs/ventilator_guidelines.pdf)

This document sadly outlines how to triage ventilators when you don't have enough. It underscores the importance of this project.

[U.S. FDA Standard And Requirements for Ventilators](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfPCD/classification.cfm?ID=99)

[A Single Ventilator for Multiple Simulated
Patients to Meet Disaster Surge](https://onlinelibrary.wiley.com/doi/pdf/10.1197/j.aem.2006.05.009)

[3D Printed Ventilator Manifold Might One Day Save Patients from Lung Damage](https://3dprint.com/45352/3d-printed-ventilator-manifold/)

[PUMANI bubbleCPAP](http://hadleighhealthtechnologies.com/pumani-bcpap/) (for infants, commercial, but may be a useful low-cost reference point)

[Retrofitting CPAP machines to reduce the ventilator shortage](https://docs.google.com/document/d/1uF6VbxwtKA2iuQtYNQJ-yW9clQXDOgtaTS5TvQ8Sk8k/edit?usp=sharing)

[Impact of non-pharmaceutical interventions (NPIs) to reduce COVID19 mortality and healthcare demand](https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf) -- This is the famous Imperial College model that instigated social distancing in the UK and US. Although not focused on ventilators, it did focus on ICU beds, a closely related issue.

[Top 10 Innovative Israeli tech for COVID-19](https://socialimpactil.com/corona-virus/)
[Alternative Ventilation](https://github.com/PubInv/covid19-vent-list/blob/master/resources_unvetted/AlternativeVentilation5.pdf) (Provided by Ori Avihail).

[Mechanical Ventilators in US Acute Care Hospitals](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C21&q=Mechanical+Ventilators+in+US+Acute+Care+Hospitals&btnG= ) A valuable resource, but behind a paywall, this is the Google Scholar Citation.

[Frontier Tech 4 COVID Action: 10 things we’ve learnt about ventilators for emerging markets](https://medium.com/frontier-technology-livestreaming/frontier-tech-4-covid-action-10-things-weve-learnt-about-ventilators-for-emerging-markets-c9eeaf2908ee) A valuable essay, topical as of March 27th.

[Open Hardware COVID19](https://opensource.com/article/20/3/open-hardware-covid19) A news article talking about open hardware projects beyond ventilators but medically interesting.


[A short list of relevant ISO standards described](https://docs.google.com/spreadsheets/d/1WmPpG8hsu2mlgI_rFDZl2zZMAPZdp-kboGi0jfIsrI4/edit#gid=2126274196)






# Basic Educational Resources

Five videos on using Mechanical Ventilators:

[Part 1 ](https://youtu.be/gk_Qf-JAL84)

[Part 2 ](https://youtu.be/K0maLgTzIto)

[Part 3 ](https://youtu.be/6Bdv7QhNNy4)

[Part 4 ](https://youtu.be/KHpJ21UWbhg)

[Part 5 ](https://youtu.be/Jx7oeJKzI9g)


[OpenSourceCoronavirusProjects](https://github.com/cyborg527/OpenSourceCoronavirusProjects?fbclid=IwAR2OFWCfl4kF2lXv1wW5laZlRPu4RcKs8NBkDOrSCcPAd0ONJIemClQrGdM) -- a large list of resources not specific to ventilators

[Understanding Mechanical Respiration in 90 Minutes](https://diyventilators.discourse.group/t/understanding-mechanical-respiration-in-90-minutes/138)

[Closed-Loop Control of Mechanical Ventilation: Description and Classification of Targeting Schemes](http://rc.rcjournal.com/content/56/1/85) -- I found this paper particular useful.

# FAQ

Q: What is a test lung?

A: A test lung is a [bag between two pieces of plastic](https://smile.amazon.com/gp/product/B0767RBQ1H/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1) which approximates the resistance to inflation of a human lung. They cost about $200. They are used for testing ventilators.

Q: What is barotrauma?

A: [Ventilator Induced Barotrauma](https://en.wikipedia.org/wiki/Barotrauma#Ventilator-induced_barotrauma) is dangerous and common, and why you can't just use an untested ventilator on a human being. It is caused by too much or too little pressure, too much air flow speed, or even too much volume at low pressures.

Q: What is a pneumatic ventilator?

A: A pneumatic ventilator is powered primarily by pressurized air, rather than electronics.


# Interesting Articles of Unknwown Validity

[PulmCrit Wee- Could the best mode of noninvasive support for COVID-19 be… CPAP ??](https://emcrit.org/pulmcrit/cpap-covid/)

[Automatic resucitators can server as effective "force multipliers" for emergency ventilaotry support in mass casualty scenarios](http://www.tecnomed.eu/vortran/file/Automatic%20Resuscitators%20Can%20Serve%20as%20Eff%20Force%20Multipliers_Aug%2006.pdf)



# Request for Donations to Public Invention

[Public Invention](https://www.pubinv.org/) is a small, all-volunteer 501(c)3 US public charity. Your [small donation](https://www.pubinv.org/donate/) is a stamp of approval for our work that will really help us.


