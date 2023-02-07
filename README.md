# COVID-19 Ventilator Projects and Resources with FAQs -- NO LONGER ACTIVELY MAINTAINED AS OF 2023

An analyzed list of projects to make emergency ventilators in response to COVID-19, focusing on free-libre open source.

**Note**: PLEASE make pull requests or submit issues to add any project missing from this list. The comments are entirely my own (possibly not well-informed) opinions. They are meant to be helpful to those looking for quick information, and not to disparage any project.

# Evaluation of Known Projects

![Top Projects as pf April 1st](https://user-images.githubusercontent.com/5296671/78171602-50b17400-741a-11ea-863d-a4adabeeb1d4.png)
 
**Note**: This image was updated April 1st, 2020. This data may be more easily and currently viewed as a [spreadsheet](https://docs.google.com/spreadsheets/d/1inYw5H4RiL0AC_J9vPWzJxXCdlkMLPBRdPgEVKF8DZw/edit?usp=sharing). 
Please send me point-of-contact information for each project via an issue, and I will put it in this (very public) spreadsheet.

**Introduction**: 
We would like to thank everyone who has contributed to this effort. In the interest of transparency and information for the community, all the known projects have been analyzed in terms of criteria we believe are essential to successfully deploy an open-source ventilator during the COVID-19 pandemic.

These seven attributes are:
1. Openness
2. Community Support
3. Buildability
4. Functionally Tested
5. Reliability Tested
6. COVID-19 Suitability
7. Clinician Friendly

**Evaluation criteria**: Each project is evaluated on [5-point scale defined here](https://docs.google.com/document/d/e/2PACX-1vRl9yZ27KvslftcNvweHgH1A81pO8gHL62TWpY_VY-UELWdK9x-4-3hNw3DbkemClzExPsg8RfnxilP/pub) on each of these attributes.
Use this [link](https://docs.google.com/document/d/1lWXCij-7yrbWUJJx-y4d6dREdYaTkb62iOZDTDbRi0I/edit?usp=sharing) to comment on those attributes.

Our goal is not to rank projects, but 
  * to shed light on the state of readiness of these projects, and perhaps
  * identify things that must be addressed before they can be deployable. 

**Caution**: Although in times of crises one may compromise, since ventilators are life-critical, last-resort devices they may do more harm than good if they do not meet stringent requirements. We have largely followed the guidelines of the [Rapidly Manufactured Ventilator System](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/879382/RMVS001_v4.pdf) criteria set out by the UK.

We hope that this will always be out-of-date. That is, we hope projects move so fast that we cannot keep up with updating
their progress. We certainly intend no slight to any project. 

Please open an issue, if you believe a project, 
  1. has made progress in a specific category,
  2. is misevaluated, or 
  3. a new project should be added.

# Essential Reading

I believe the following are the most essential documents to read first:
1. [A brief for engineers, by a doctor, on hacking a ventilator for surge capacity in Covid19 patients](https://docs.google.com/document/d/1sdrKYQ0mDOu4bJum6Fx6piRutIJovo7UqFKYHHxUD5A/edit?usp=sharing)
   Author: Dr. Eric Schulz, MBBS, FANZDA, an anesthetist/anesthesiologist from Australia.

    Dr. Schulz has now made it a 4-volume guide:

      a. [Vol. 1](https://docs.google.com/document/d/1sdrKYQ0mDOu4bJum6Fx6piRutIJovo7UqFKYHHxUD5A/edit#heading=h.zfqx8qqil1g1)

      b. [Vol. 2](https://docs.google.com/document/d/1SBT8auegsJCKCVMBHFLWaVo8rKbs0zsJc3dDVAqeADE/edit#heading=h.sx9qnelsso49)

      c. [Vol. 3](https://docs.google.com/document/d/1-eV7ClGCTgaqPug7u9ovE_s-U6J5s8Hzc3XAalkEgVE/edit)

      d. [Vol. 4](https://docs.google.com/document/d/1CmCRtK_f4hgo4RHnpn1sE981lPSzp8PU7A5Yu4urgz0/edit)

1. [A Super-simple Guide to Mechanical Ventilation For Open Source Engineers Designing Ventilators for the COVID-19 Pandemic](https://docs.google.com/document/d/1p-oYUv_6FadipV67g2O5yfnQvpdvZDm4WadYVubhoH4/edit?usp=sharing) -- 
   Author: Robert L. Read, that's me. It's my best attempt at an introduction, although somewhat redundant with the above guide. Dr. 
   Schulz and I may attempt to harmonize them as we have time.
   
1. [Modular Design of Pandemic Ventilators: How Do We Get There?](https://docs.google.com/document/d/1a5A7RKkY1qwI-skN0oNvwTFSHDIaYoWLQpEWUn0mXfU/edit?usp=sharing) Written with Jenny Filipetti, this is my personal breakdown of the problem into modules; it is a shared google doc that anyone can comment on.

1. [Key Ventilation Specifications](https://e-vent.mit.edu/clinical/key-ventilation-specifications/)

1. [Rapidly Manufactured Ventilator System](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/876167/RMVS001_v3.1.pdf)

1. [U.S. ICU Resource Availability for COVID-19](https://sccm.org/getattachment/Blog/March-2020/United-States-Resource-Availability-for-COVID-19/United-States-Resource-Availability-for-COVID-19.pdf?lang=en-US)

1. [Ventilator Supply Mitigation Strategies: Letter to Health Care Providers](https://www.fda.gov/medical-devices/letters-health-care-providers/ventilator-supply-mitigation-strategies-letter-health-care-providers): Explains reuse and adaptations of existing devices.

1. [OSCMS - Ventilator Machines](https://docs.google.com/document/d/1lZWUwIpN2kINxURqP9Tczn2zYqpuVlBSDBypJt76a2Q/edit?usp=sharing)

1. [Informal notes from a pulmonologist](https://github.com/jcl5m1/ventilator/wiki/Notes-from-chatting-with-a-pulmonologist) speaking with Johnny Lee also highly relevant.


# Videos

Stephen Kramer has compiled and donated with a CC0 license, a [spreadsheet](https://github.com/PubInv/covid19-vent-list/blob/master/Covid19_Projects_from_YouTube.xlsx) with 85 projects that have YouTube videos. 

**Note**: We have not yet had time to cross reference this or integrate it with our analysis spreadsheet, or this list of projects and resources.

# Most Buildable Projects

**Background**: These two projects are, in our humble opinion, the closest to being actually buildable by a third party. 

**Word of caution**: 
  * Our analyses of these project is now badly out of date.
 

1. [AmboVent](https://1nn0v8ter.rocks/AmboVent-1690-108): A well-tested design by a large team from the Israeli Air Force. Definitely one to watch. This is the number one low-cost, easily built project since they released their [plans and code](https://github.com/AmboVent/AmboVent) on April 2nd! 

1. [Rice OEDK Design: ApolloBVM](https://docs.google.com/document/d/1-DRXnVkJOlDCmvTzh-DgWDxeLSrZTiBYyH0ypzv8tNA/edit?usp=sharing):
This project is well-documented. It is not clear whether there is an active team working on it. Above document is dated April 19, 2019, and was almost certainly presented at the OEDK for 2019 at the end of the school year, possibly by graduating Seniors. It has been pressure-tested. At present it claims to work only for 6 hours without human intervention. It does not appear to have repository.

# Almost Buildable Projects

1. [Beatmungsgerät [Respirator]](https://devpost.com/software/diy-beatmungsgerat) - German language site, but appears to be in best state of openness, build reproducibility, monitoring and alarming. Reliability testing uncertain.

1. [Low-Cost Open Source Ventilator](https://github.com/jcl5m1/ventilator)-Probably best state of buildability at the time of writing this. The above link is to the repo. The inventor, Johnny Lee, is actively improving the system as of March 21st, and has called for assistance. It has been pressure-tested and has a [wiki](https://github.com/jcl5m1/ventilator/wiki). I recommend the community of makers and volunteers for open-source ventilator design offer Johnny Lee their full assistance.

1. [Protofy Team OxyGEN](https://oxygen.protofy.xyz/): Project active as of March 16th, 2020. It has a [repo](https://github.com/ProtofyTeam/OxyGEN) of design documents.
   * March 16th: Limited control capability. 
   * April 5th: Two versions available: Version ”IP" for large scale manufacturers and version "M" for makers. 
     * Version M, fully open source but the documents lag behind the version IP.  
     * Version IP, a closed consortium of SEAT, protofy.xyz and others. As per my understanding their documents will be filtered back into the ”M” documents. Version IP has passed animal trials and the Spanish government agreed hospital clinical trials with COVID19 patients.  
   * April 3rd: COVID19 ICU patients in Barcelona are using the IP version as of 3 April, video and photos are on a number of news sites.   Government agreement includes SEAT ramping up their manufacturing line to 400 units a day.  
   * April 6th: The government/consortium plan is to rollout wider testing to more hospitals in Catalunya this week, from 6 April. Human trials will continue this week.Recommend waiting to built version M until the documents are updated after feedback from clinical trails of version IP. Discord group: https://discord.gg/zDYmR5

1. [Open Source Ventilator - OpenLung BVM Ventilator](https://opensourceventilator.ie/)[GitLab repo here](https://gitlab.com/open-source-ventilator/OpenLung): Fully open(GPL). Aims to adopt bag valve masks. Based on designs (not open) from Rice and MIT. Author (Trevor Smale) responded to email. Highly organized, but not buildable at the time of writing this.

1. [VentilAid](https://www.ventilaid.org/): Current prototype is pneumatic. 3D printed parts complete, but I can't find complete assembly instructions.They are working on a second electric prototype.

1. [Mechanical Ventilator Milano (MVM):A Novel Mechanical Ventilator Designed for Mass Scale Production in Response to the COVID-19 Pandemics](https://arxiv.org/pdf/2003.10405.pdf)


 ### Electric Blower Based Portable

1. [Emergency Ventilator](https://digitalcommons.usu.edu/cgi/viewcontent.cgireferer=https://www.google.com/&httpsredir=1&article=1016&context=spacegrant&fbclid=IwAR1EtJVcxXm82PjGWFCA0t7H_MxNVjuseAePRfxNORr9h4ZQLQ9sNdQjXhc)

1. [Pandemic Ventilator](https://docs.google.com/document/d/1Dz7eMgXowFBtBA_0PKzfAXweHnNMbGlIAXPshCbI2Vk/edit?usp=sharing)[Open Source Pandemic Ventilator(GoFundMe for above)](https://www.gofundme.com/f/open-source-pandemic-ventilator): Online funding  for development of an Open Source Ventilator.They provide a Google Docs project overview. According to the photo provided it is a CPAP blower type. Impressive document.

1. [Zephyr Ventilator](https://github.com/Julhh/Zephyr): Open source mechanical ventilator with the goal of reaching MHRA spec. 

#### Reports on Projects with No Designs

1. [Saving Babies' Lives Starts With Aquarium Pumps And Ingenuity](https://www.npr.org/sections/healthshots/2014/01/03/259436844/saving-babies-lives-starts-with-aquarium-pumps-and-ingenuity)

1. [Low-Cost Ventilator Wins Sloan Health Care Prize](https://www.medicaldesignandoutsourcing.com/low-cost-ventilator-wins-sloan-health-care-prize/)

### Ambubag based

1. [Jeff Ebin's Prototpye](https://www.facebook.com/groups/670932227050506?view=permalink&id=675336579943404&scmts=scwspsdd&extid=MnVADGiqBuaYx9KD) and [his valuable document](https://docs.google.com/document/d/1FNRe2GS7ShhJAJu6Ogdl0OAjS0oLJZ-lkPjT1DSAhpI/edit?ts=5e79401f):Functioning Ambu-bag based model. Not obviously open with no published design, but possibly easy to copy.

1. [The Pandemic Ventilator](https://www.instructables.com/id/The-Pandemic-Ventilator/): Since 2007. Uses a relatively old and expensive programmable logic controller, but a great starting place. Possibly well tested.

1. [Hackaday Rex Ventilator V1](https://www.youtube.com/watch?v=pFnB-vOWQmU):An update of the previous project. No known open-source repo at present.

1. [Simple device from www.POMO.cl](https://www.facebook.com/groups/670932227050506/permalink/675264606617268/?app=fbl): Nice video with possibly nice control. No obvious link to replicatable design documents.

1. [MIT Low Cost Ventilator](https://github.com/RuairiSpain/openVentilator).
 **Note**: Some work from MIT? Have not had time to evaluate.

1. [Pandemic Ventilator Project](https://panvent.blogspot.com/2008/02/test-of-pandemic-ventilator-with.html): Working prototype, currently active.

1. [Dr. Mujeeb ur Rahman design ](http://www.technologyreview.pk/pakistani-engineer-braves-tragedy-to-develop-low-cost-ventilator/): Unclear if the design is published. Good data collection.

1. [CoronavirusMakers](https://gitlab.com/coronavirusmakers): Currently active. I found it interesting. They are using 'maker' hardware (ie. Arduino MEGA, TB6600 driver, NEMA17 or NEMA23)

1. [VentilatorPAL](https://freebreathing.org/): Pre-orderable for &euro 370. Claims will be open sourced March 29th. Has repo, but files in odd format (to me).

1. [Oxford new report](https://www.youtube.com/watch?v=xdZtMgpxnPI): Yet another news report of a project. No information that it is open.

1. [OpenBreath Italy](https://www.openbreath.it/en/): Now with a repo. Just made their first prototype.

1. [Ad Hoc](https://20100.be/ad-hoc-ventilator/)

1. [Low-Cost Automated Emergency Ventilator](https://gitlab.com/PerAsperaAdAstra/lcaev): Site a bit unclear, look at: [design log](https://gitlab.com/PerAsperaAdAstra/lcaev/-/wikis/Design%20Log) 

1. (https://www.kvue.com/article/news/health/coronavirus/coronavirus-ut-researchers-prototype-emergency-ventilator/269-1c767f513aef-4eb6-8c0b-4e2f058f0f2c)

1. [Austin Bridge Breathing Unit](https://thedailytexan.com/2020/04/07/university-researchers-develop-breathing-unit-to-help-combat-ventilator-shortage): Plans to open-source code after obtaining emergency FDA approval. Reported in the [news](https://www.kvue.com/article/news/health/coronavirus/coronavirus-ut-researchers-prototype-emergency-ventilator/269-1c767f51-3aef-4eb6-8c0b-4e2f058f0f2c)

## Systems for Multiple Patients

1. [Breathing Aid](https://www.breathing-aid.org/homeen):
     * In several langauges, 
     * Appears to be a large pneumatic circuit design for ventilator to use simultaneously on multiple patients. 
     * Seems to provide CPAP but not varaible bilevel ventilation. 
     * Might be good for people who don't require full ventilation in a field hospital.

1. [Remote Ventilator Monitoring Project](http://www.ventilatormonitor.com/): An early project that presents a dashboard for monitoring multiple ventilators.

## Bellows based

1. [OpenVentilator](https://www.popsolutions.co/en_US/openventilator):
     * Seems very well developed on first glance. 
     * Uses very accessible parts. 
     * Could be successful With more testing. 

## Fluid-based

1. [YACoVV - Yet Another (SARS-)CoV(-2)Ventilator](https://github.com/auenkind/YACoVV): Focuses on the pressure regulating part with an unconventional, but very effective solution

### Cuirass/Negative Pressure/Iron Lung base

1. [Cuirass Ventilator the DIY way](https://www.youtube.com/watch?v=pvrUQCMa3a8&feature=youtu.be): A valuable and educational video, open in spirit. 
 **Note**: This does not provide positive pressure, or the direct inclusion of oxygen. This would be a valuable part of a spectrum of solutions in a catastrophic situation.

1. [Cuirass Ventilator](https://github.com/jps2000/Cuirass-Ventilator)

## Related Therapeutic Projects

1. [Ventialors SOS](https://www.ventilatorsos.com/): A Berkeley project to repurpos BiPAP and CPAP machines.

## Test Equipment/Projects

1. [VentMon inline tester and monitor/alarm](https://github.com/PubInv/ventmon-ventilator-inline-test-monitor): A [Public Invention](https://www.pubinv.org) project seeks to,
    * build an inline flow monitor for testing ventilators and
    * for monitoring them in actual critial care usage.
 **Note**: This is my own attempt to build a test apparatus that meaasures clinical suitability as well as reliability. Project is just beginning.

1. [Ventilator Inline Sensor Package](https://hackaday.io/project/170622-visp-ventilator-inline-sensor-package)

1. [COVID-19 Ventilator Validation Tests](https://github.com/PubInv/covid19-ventilator-validation-tests): Another [Public Invention](https://www.pubinv.org) project that provides, a spreadsheet with ~200 validation tests for clinical usability and suitability, based on: UK[RMVS](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/876167/RMVS001_v3.1.pdf) standard.

1. [A Venturi Tube Calculator](https://docs.google.com/spreadsheets/d/15T2E0_az5z4KQWNToqmD7rcZ1vJXbD5SSi3-eamiD4c/edit?usp=sharing) This is a personal project, but I don't know where else to put it. There is a world-wide shortage of flow-sensors right now; I've repackaged other people's math to make it easier to match the math to off-the-shelf flow sensors.
      
 **NOTE**: More test projects are needed! If you know of a test project, please make a pull request or enter an issue.

# Communities working on Open-Source Ventilators

1. [EndCoronaVirus (NECSI)](https://www.endcoronavirus.org/): Associated with [NECSI](https://necsi.edu/), the New England Complex Systems Institute, effort with over 3000 volunteers in its [Slack team](necsi-edu.slack.com), many of them medical professionals. Channels for Ventilator work are prefixed "#responseventilators".

1. [HelpfulEngineering](https://www.helpfulengineering.org/): HelpfulEngineering has over 12,000 volunteers in its [Slack team](helpfulengineering.slack.com)

1. [DIY Ventilators](http://diyventilators.com/)

1. [Pak Innovation Club](http://www.pakengimed.com/ncov/)

1. [Ventilator Crowd](https://www.ventilatorcrowd.org/): They have a [repo](https://github.com/ventilatorcrowd/Ventilator-Crowd) with some analysis.

1. [#industryvirus](industryvsvirus.de): German (and German language?) based [LinkedIn](https://www.linkedin.com/groups/8918186/) group. There is also a [slack](https://wirvsvirus.slack.com/archives/G010J7X703G) group.

1. [1 million Ventilators Project](https://1mventilators.com/):Large, active community. Best to contact through [Discord](https://discord.gg/g3kbSSb)

1. [Global Ventilator & PPE DIY Collaboration](https://j.mp/C19diyProjects): An international group using WhatsApp for communication. May have projects soon.

1. [#EngineersAssemble](https://engineersassemble.tribe.so/)

1. [The Ventilator Project](https://theventilatorproject.org/): Has a gofundme.

1. [VENTILATORS COLLABORATION NETWORK](https://soptechint.com/ventilators)

1. [TECHNOLOGY EXCHANCE LAB](https://www.techxlab.org/solutions/categories/covid19/ventilator/)

# Challenges and Calls for Papers

1. [HardwareX: Special Issue on Open-Source COVID19 Medical Hardware](https://www.journals.elsevier.com/hardwarex/call-for-papers/special-issue-on-open-source-covid19-medical-hardware) 
 **Note**: (Submission deadline June 1st, 2020)

1. [Code Life Ventilator Challenge](https://www.agorize.com/en/challenges/code-life-challenge?t=c55DcF41nZeLDXfG6-Goyg)

1. [ULTIMATE MEDICAL HACKATHON: HOW FAST CAN WE DESIGN AND DEPLOY AN OPEN SOURCE VENTILATOR?](https://hackaday.com/2020/03/12/ultimate-medical-hackathon-how-fast-can-we-design-and-deploy-an-open-source-ventilator/)

1. [The Covid Sprint](https://www.covid-sprint.com/) 

1. [https://covid-global-hackathon.devpost.com/](https://covid-global-hackathon.devpost.com/)

1. [Opens Source COVID-19 Medical Supplies](https://www.facebook.com/groups/opensourcecovid19medicalsupplies): An excellent resources for supplies in general (focusses more on PPE than ventilators)

1. [Give a Breath - Challenge](https://give-a-breath-challenge.innosabi.com/) 
      * Appears to be both a challenge and a community. 
      * Opened applications March 25th, judging for second phase April 3rd. 
      * Challenge has funding (for prize and a realization fund) of at least €1 million (additional partners and donors invited). 
      * Join in and help to save as many lives as possible!

# Potential Grant Resources

[COVID-19 Solutions Fund](https://blog.mozilla.org/blog/2020/03/31/moss-launches-covid-19-solutions-fund/)

# Resources

1. [Initiatives around the world](https://opensourceventilator.org/#initiatives) A separate list of initiatives, somewhat different than the one we maintain.

1. [U.S. ICU Resource Availability for COVID-19](https://sccm.org/getattachment/Blog/March-2020/United-States-Resource-Availability-for-COVID-19/United-States-Resource-Availability-for-COVID-19.pdf?lang=en-US):This important document suggests that in the case of a severe epidemic, 
     * the US will bottleneck on have enough people trained on ventilators, 
     * but also not have enough ventilators, or beds.

1. [Medical Ventilator System Basics](https://www.docdroid.net/gval5gc/medical-ventilator-system-basics-a-clinical-guide-by-yuan-lei.pdf)

1. [Rapidly Manufactured Ventilator System (RMVS)](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/874279/RMVS001_Rapidly_Manufactured_Ventilator_Specification__PDF.pdf)

      **Note**: This is an excellent read and great source of information. However, an MD and respiratory therapist state that, it should be taken with some skepticism as an actual minimum set of requirements, asserting that simpler designs with fewer features may also be extremely valuable in a resource-starved shortfall.

1. [Clinical course and risk factors for mortality of adult inpatients with COVID-19 in Wuhan, China: a retrospective cohort study](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30566-3/fulltext): This is a very important study in part because it allows us to predict ventilator need (in terms of days) for patients.

1. [Manufacturing and COVID-19: How you or your organisation could help](https://www.ifm.eng.cam.ac.uk/manufacturing-and-covid-19-ways-your-company-could-help/)

1. [Open Source Ventilator Project](https://simulation.health.ufl.edu/technology-development/open-source-ventilator-project/)

1. [Open Source Ventilator](https://github.com/CSSALTlab/Open_Source_Ventilator): University of Florida, mostly specifications right now, but amoung the best set of quality specifications available:

1. Overall Design Philosophy:[Open source for use worldwide and contributions from others worldwide](https://github.com/CSSALTlab/Open_Source_Ventilator.git)

1. [Internet Book of Critical Care (IBCC) : COVID-19](https://emcrit.org/ibcc/covid19/)

1. [Covid-19 Research and Reports Esp. WRT Modeling](https://covid.idmod.org/#/ResearchandReports)

1. [Open source ventilator](https://docs.google.com/document/d/1RDihfZIOEYs60kPEIVDe7gmsxdYgUosF9sr45mgFxY8/preview?pli=1#heading=h.l93gl0t8fdvh): A great overall working document from the people at HelpfulEngineering.

1. [Indicative Specification for a Rapidly Manufactured Ventilation System (RMVS)](https://www.britishchambers.org.uk/media/get/Specification%20For%20RMVS%20Challenge.pdf)

1. [Penn Medicine - COVID-19 Hospital Impact Model for Epidemics](https://penn-chime.phl.io/): A specific but valuable interactive model of hospital admissions

1. [COVID-19 Open Research Dataset (CORD-19)](https://pages.semanticscholar.org/coronavirus-research): Massive collection of resources, mostly academic papers AFAIK

1. [OSCMS - Ventilator Machines](https://docs.google.com/document/d/1lZWUwIpN2kINxURqP9Tczn2zYqpuVlBSDBypJt76a2Q/edit?usp=sharing)

1. [Specifications for simple open source mechanical ventilator](https://docs.google.com/document/d/1FNPwrQjB1qW1330s5-S_-VB0vDHajMWKieJRjINCNeE/preview)

1. [Coronavirus Tech Handbook](https://coronavirustechhandbook.com/ventilators)

1. [FDA Guidance on Conduct of Clinical Trials of Medical Products during COVID-19 Pandemic: Guidance for Industry, Investigators, and Institutional Review Boards](https://www.fda.gov/media/136238/download)

1. [Handbook COVID-19 Prevention and Treatment](https://www.wapa.com/assets/documents/Handbook%20of%20COVID-19%20Prevention%20and%20Treatment.pdf)

1. [Principles and Practice of Mechanical Ventilation, 3rd Edition](https://lookaside.fbsbx.com/file/Principles-and-Practice-of-Mechanical-Ventilation-3rd-Edition.pdf?token=AWw3WFewSdPPCZAOKYoSF1XYpRfMzNRyrZe7V_b-I3LBX25xsqrcrgQigtWUHNFxDNJ7XxDFv9voXZvOsr8I1k-p_9QE9IBWqf4sxlfRxRHmhbngaaBsM10K6Wbna4aNlCHtm0fakn2R7viBqlufWW1yeL91ZaM5ljUtfXFZF8_WHQ)

1. [Virus Simulator](https://github.com/SilverLinings89/VirusSimulator)
     * A useful resource for programmers as a model; 
     * Data seems insufficient to accurately model COVID-19 at present although it has a preset for it.

1. [VENTILATOR ALLOCATION GUIDELINES](https://www.health.ny.gov/regulations/task_force/reports_publications/docs/ventilator_guidelines.pdf)
     * This document sadly outlines how to triage ventilators when you don't have enough. 
     * It underscores the importance of this project.

1. [U.S. FDA Standard And Requirements for Ventilators](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfPCD/classification.cfm?ID=99)

1. [A Single Ventilator for Multiple Simulated Patients to Meet Disaster Surge](https://onlinelibrary.wiley.com/doi/pdf/10.1197/j.aem.2006.05.009)

1. [3D Printed Ventilator Manifold Might One Day Save Patients from Lung Damage](https://3dprint.com/45352/3d-printed-ventilator-manifold/)

1. [PUMANI bubbleCPAP](http://hadleighhealthtechnologies.com/pumani-bcpap/): For infants, commercial but, may be a useful low-cost reference point

1. [Retrofitting CPAP machines to reduce the ventilator shortage](https://docs.google.com/document/d/1uF6VbxwtKA2iuQtYNQJ-yW9clQXDOgtaTS5TvQ8Sk8k/edit?usp=sharing)

1. [Impact of non-pharmaceutical interventions (NPIs) to reduce COVID19 mortality and healthcare demand](https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf) -- This is the famous Imperial College model that instigated social distancing in the UK and US. Although not focused on ventilators, it did focus on ICU beds, a closely related issue.

1. [Top 10 Innovative Israeli tech for COVID-19](https://socialimpactil.com/corona-virus/)[Alternative Ventilation](https://github.com/PubInv/covid19-vent-list/blob/master/resources_unvetted/AlternativeVentilation5.pdf)(Provided by Ori Avihail)

1. [Mechanical Ventilators in US Acute Care Hospitals](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C21&q=Mechanical+Ventilators+in+US+Acute+Care+Hospitals&btnG= ): A valuable resource, but behind a paywall, this is the Google Scholar Citation.

1. [Frontier Tech 4 COVID Action: 10 things we’ve learnt about ventilators for emerging markets](https://medium.com/frontier-technology-livestreaming/frontier-tech-4-covid-action-10-things-weve-learnt-about-ventilators-for-emerging-markets-c9eeaf2908ee): A valuable essay, topical as of March 27th.

1. [Open Hardware COVID19](https://opensource.com/article/20/3/open-hardware-covid19): A news article talking about open hardware projects beyond ventilators but medically interesting.

1. [A short list of relevant ISO standards described](https://docs.google.com/spreadsheets/d/1WmPpG8hsu2mlgI_rFDZl2zZMAPZdp-kboGi0jfIsrI4/edit#gid=2126274196)

1. The MIT E-Vent has [published](https://e-vent.mit.edu/mechanical/power-calculation/): Extremely useful analysis of the power required to drive a ventilator base on a model of breathing.

1. [Differential Multiventilation](https://www.differentialmultivent.org/components/) Has a number of very usesful components needed to attempt supporting multiple patients on a single ventilator. Very useful as a source for 3D printed valves.

1. [A Repair Database for Medical Parts](https://www.ifixit.com/Device/Medical_Device)

1. [Ventilator design ideas](https://www.txtpwr.com/Ventilator_Ideas_Andy_Firth_of_Letchworth.htm)

# Basic Educational Resources

1. Five videos on using Mechanical Ventilators:

    a. [Part 1 ](https://youtu.be/gk_Qf-JAL84)

    b. [Part 2 ](https://youtu.be/K0maLgTzIto)

    c. [Part 3 ](https://youtu.be/6Bdv7QhNNy4)

    d. [Part 4 ](https://youtu.be/KHpJ21UWbhg)

    e. [Part 5 ](https://youtu.be/Jx7oeJKzI9g)

1. [OpenSourceCoronavirusProjects](https://github.com/cyborg527/OpenSourceCoronavirusProjects?fbclid=IwAR2OFWCfl4kF2lXv1wW5laZlRPu4RcKs8NBkDOrSCcPAd0ONJIemClQrGdM): A large list of resources not specific to ventilators

1. [Understanding Mechanical Respiration in 90 Minutes](https://diyventilators.discourse.group/t/understanding-mechanical-respiration-in-90-minutes/138)

1. [Closed-Loop Control of Mechanical Ventilation: Description and Classification of Targeting Schemes](http://rc.rcjournal.com/content/56/1/85) -- I found this paper particular useful.

# FAQs

Q: What is a test lung?

A: A test lung is a 
 * [bag between two pieces of plastic](https://smile.amazon.com/gp/product/B0767RBQ1H/ref=ppx_yo_dt_b_asin_title_o00_s000ie=UTF8&psc=1) 
 * It approximates the resistance to inflation of a human lung, 
 * It costs about $200 and is used for testing ventilators.

Q: What is barotrauma?

A: [Ventilator Induced Barotrauma](https://en.wikipedia.org/wiki/Barotrauma#Ventilator-induced_barotrauma), is dangerous and common, and 
 * is the reason you can't just use an untested ventilator on a human being, and 
 * is caused by too much or too little pressure, too much air flow speed, or even too much volume at low pressures.

Q: What is a pneumatic ventilator?

A: A pneumatic ventilator is powered primarily by pressurized air, rather than electronics.

# Interesting Articles of Unknown Validity

1. [PulmCrit Wee- Could the best mode of noninvasive support for COVID-19 be… CPAP ??](https://emcrit.org/pulmcrit/cpap-covid/)

1. [Automatic resucitators can server as effective "force multipliers" for emergency ventilaotry support in mass casualty scenarios](http://www.tecnomed.eu/vortran/file/Automatic%20Resuscitators%20Can%20Serve%20as%20Eff%20Force%20Multipliers_Aug%2006.pdf)


# Request for Donations to Public Invention

[Public Invention](https://www.pubinv.org/) is a small, all-volunteer 501(c)3 US public charity. 
Your [small donation](https://www.pubinv.org/donate/) is a stamp of approval for our work that will really help us.


