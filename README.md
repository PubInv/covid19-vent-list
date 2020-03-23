# COVID-19 Ventilator Projects and Resources and FAQ

A list projects to make emergency ventilators in response to COVID-19, focusing on free-libre open source.

PLEASE make pull requests or submit issues too add any project missing from this list.  The comments are entirely my own (possibly not well-informed) opinions and are meant to be helpful to those looking for quick information, not to disparage any project.

A list of valuabe resources exists below this list.

# Essential Reading

I believe these are the three most essential documents to read first:

[Rapidly Manufactured Ventilator System](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/874279/RMVS001_Rapidly_Manufactured_Ventilator_Specification__PDF.pdf)

[U.S. ICU Resource Availability for COVID-19](https://sccm.org/getattachment/Blog/March-2020/United-States-Resource-Availability-for-COVID-19/United-States-Resource-Availability-for-COVID-19.pdf?lang=en-US)

[OSCMS - Ventilator Machines](https://docs.google.com/document/d/1lZWUwIpN2kINxURqP9Tczn2zYqpuVlBSDBypJt76a2Q/edit?usp=sharing)

[Informal notes from a pulmonologist](https://github.com/jcl5m1/ventilator/wiki/Notes-from-chatting-with-a-pulmonologist) speaking with Johnny Lee are also highly relevant.

# Projects

## Most Buildable Projects

These three projects are, in our humble opinion, the closest to being actually buildable by a third party. We do not believe they are ready to built or manufactured in quantity, and have only had the lightest of testing. Furthermore, the COVID-19 disease requires critical care in an ICU; these designs may be excellent for patients with other diseases, such as acute trauma. However, the some medical professionals have asserted that more features are needed in the case of ARDS, a common complication of COVID-19, and patients may requires ventilation for many days. These designs are in a poor state of readiness for multi-day treatment.


[Low-Cost Open Source Ventilator](https://github.com/jcl5m1/ventilator)

Probably best state of buildability at the the time of this writing. The link above is to the repo. The inventor, Johnny Lee, is actively improving the
system as of March 21st, and has called for assistance. It has been pressure-tested. It has a [wiki](https://github.com/jcl5m1/ventilator/wiki).

I recommend the community of makers and volunteers for open-source ventilator design offer Johnny Lee their full assistance.

[Rice OEDK Design: ApolloBVM](https://docs.google.com/document/d/1-DRXnVkJOlDCmvTzh-DgWDxeLSrZTiBYyH0ypzv8tNA/edit?usp=sharing)

This project is well-documented. It is not clear that it has an active team working on it. The document above is dated April 19, 2019, and was almost certainly presented at the OEDK for 2019 at the end of the school year, possibly by graduating 
Seniors. It has been pressure-tested. At present it states it only works for 6 hours without human intervention. It does not appear to have repository.

[Protofy Team OxyGEN](https://oxygen.protofy.xyz/)

This project was active as of March 16th, 2020. It has a [repo](https://github.com/ProtofyTeam/OxyGEN) of design documents.
As of March 16th it has limited control capability and has not been pressure tested.

[Open Source Ventilator - OpenLung BVM Ventilator](https://gitlab.com/open-source-ventilator/OpenLung)

Fully open (GPL). Aims to adopt bag valve masks, based on designs (not open) from Rice and MIT. Author (Trevor Smale) responded to email. Highly organized, but not buildable at the time of this writing.



## Projects Not Yet Buildable (March 21st, 2020)

### Blower/Fan/Pump based

['Pandemic ventilator' could offer solution in potential 'worst case' coronavirus scenario](https://www.cbc.ca/news/canada/london/pandemic-ventilator-coronvirus-hospitals-1.5493830)

A well-developed device reported on by Canadian Broadcasting Company. Creator (Mr. John Strupat) may open source design soon. Note that this has a test-lung as part of the system, a very simple and important feature reproducible elsewhere even without this design. Nature of internale design not visible


[A low oxygen consumption pneumatic ventilator for emergency construction during a respiratory failure pandemic](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1365-2044.2009.06207.x)

[Electric Blower Based Portable
Emergency Ventilator](https://digitalcommons.usu.edu/cgi/viewcontent.cgi?referer=https://www.google.com/&httpsredir=1&article=1016&context=spacegrant&fbclid=IwAR1EtJVcxXm82PjGWFCA0t7H_MxNVjuseAePRfxNORr9h4ZQLQ9sNdQjXhc)

#### Reports on Projects with No Designs

[Saving Babies' Lives Starts With Aquarium Pumps And Ingenuity](https://www.npr.org/sections/health-shots/2014/01/03/259436844/saving-babies-lives-starts-with-aquarium-pumps-and-ingenuity)

[Low-Cost Ventilator Wins Sloan Health Care Prize](https://www.medicaldesignandoutsourcing.com/low-cost-ventilator-wins-sloan-health-care-prize/)

### Ambubag based

[Jeff Ebin's Prototpye](https://www.facebook.com/groups/670932227050506?view=permalink&id=675336579943404&scmts=scwspsdd&extid=MnVADGiqBuaYx9KD)

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


Yet another Ambubag based design, using a plywood cam. Well-documented and buildable.

### Cuirass/Negative Pressure/Iron Lung base

[Cuirass Ventilator the DIY way](https://www.youtube.com/watch?v=pvrUQCMa3a8&feature=youtu.be)

A valuable and educational video, open in spirit. (Note: this does not provide positive pressure, or the direct inclusion of oxygen. This would be a valuable part of a spectrum of solutions in a catastrophic situation.)

[The Pandemic Ventilator](https://docs.google.com/document/d/1Dz7eMgXowFBtBA_0PKzfAXweHnNMbGlIAXPshCbI2Vk/edit?usp=sharing)

An impressive document, other status unknown at time of writing.

## Test Equipment/Projects

[Ventilator Test Fixture](https://github.com/PubInv/ventilator-test-lung-analyzer)

My own attempt to build a test apparatus that meaasures clinical suitability as well as reliability. Project is just beginning.

More test projects are needed! If you know of a test project, please make a pull request or enter an issue.

# Communities working on Open-Source Ventilators

[EndCoronaVirus (NECSI)](https://www.endcoronavirus.org/)

An associated with [NECSI](https://necsi.edu/), the New England Complex Systems Institute, effort with over 3000 volunteers in its [Slack team](necsi-edu.slack.com), many of them medical professionals. Channels for Ventilator work are prefixed "#response-ventilators".

[HelpfulEngineering](https://www.helpfulengineering.org/)

HelpfulEngineering has over 12,000 volunteers in its [Slack team](helpfulengineering.slack.com). 

[DIY Ventilators](http://diyventilators.com/)

[Pak Innovation Club](http://www.pakengimed.com/ncov/)

# Challenges

[Code Life Ventilator Challenge](https://www.agorize.com/en/challenges/code-life-challenge?t=c55DcF41nZeLDXfG6-Goyg)

[ULTIMATE MEDICAL HACKATHON: HOW FAST CAN WE DESIGN AND DEPLOY AN OPEN SOURCE VENTILATOR?](https://hackaday.com/2020/03/12/ultimate-medical-hackathon-how-fast-can-we-design-and-deploy-an-open-source-ventilator/)

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

A great overall working doucment from the people at HelpfulEngineering.

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

[U.S. FDA Standard And Requirements for Ventialtors](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfPCD/classification.cfm?ID=99)

[A Single Ventilator for Multiple Simulated
Patients to Meet Disaster Surge](https://onlinelibrary.wiley.com/doi/pdf/10.1197/j.aem.2006.05.009)

[3D Printed Ventilator Manifold Might One Day Save Patients from Lung Damage](https://3dprint.com/45352/3d-printed-ventilator-manifold/)

[PUMANI bubbleCPAP](http://hadleighhealthtechnologies.com/pumani-bcpap/) (for infants, commercial, but may be a useful low-cost reference point)

[Retrofitting CPAP machines to reduce the ventilator shortage](https://docs.google.com/document/d/1uF6VbxwtKA2iuQtYNQJ-yW9clQXDOgtaTS5TvQ8Sk8k/edit?usp=sharing)

# Basic Educational Resources

[Part 1 ](https://youtu.be/gk_Qf-JAL84)
[Part 2 ](https://youtu.be/K0maLgTzIto)
[Part 3 ](https://youtu.be/6Bdv7QhNNy4)
[Part 4 ](https://youtu.be/KHpJ21UWbhg)
[Part 5 ](https://youtu.be/Jx7oeJKzI9g)

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


