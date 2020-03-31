# Evaluating Open Source Ventilator Projects

Copyright Robert L. Read 2020. Released under CC0 license.

Created by Public Invention


I propose we use a 5-point scale for each attribute, but we give a precise definition of what it means to be at a certain level for each scale.  Then we can add footnotes, but the overall table will be short and understandable.


Attributes are:

1. Openness
1. Buildability
1. Community Support
1. Functionally Tested
1. Reliability Tested
1. COVID-19 Suitability
1. Clinician Friendly


## Openness

1. Not Open
1. Declared to be open, but no plans published
1. Have a repo with at least some plans
1. Has a clear license strategy, regular updates to plans
1. Fully open, everything document, responsive community, clear license

Buildability

1. Unbuildable
1. Documents available but they require guesswork
1. All software and hardware transparent and documented. Some manufacturing instructions, such as a build video
1. Complete documentations suggested reproducibility
1. Has been successfully reproduced by another team purely from documentation

Community Support

1. Inactive; no point of contact
1. Point of contact, but unresponsive
1. Responsive leader or manager, more than one volunteer
1. Active community, weekly activity and reports, git repo or other shared documents
1. Large, active, open community

Functional Testing

0.  In Design Phase, Not listed/tested
1. Makes a bag move
1. Tested with a test lung
1. Tested for pressure and volume limits, with breath rate control
1. Tested for alarms, multiple modes, O2 mixing
1. All test green (if asserted as a feature)

Reliability Testing

0.   No evidence
1. Operates for one hour
1. Operates for 12 hours
1. Operates for 12 hours passing all functional test acceptably (low exception rate)
1. Independent team operates for 48 hours passing all functional tests, data logs reviewed
1. Mean time between failure data starting to become meaningful

COVID-19 Suitability  

0.  In design phase/Not listed
1. Operates with supplemental oxygen
1. Pressure or volume control or both
1. PEEP
1. Sophisticated alarm capability and stabilizability of all patient contact points
1. Meets British RVMSv1 standards

Clinician Friendly

0.   Unknown controls
1. No controls
1. Breath rate and volume control, standard ports
1. Breath rate, volume and pressure control easy to set, standard ports, clear external labeling graphically and in the language of choice
1. Alarms easy to set and understand; wholesale replication of an existing UI or conformance to a TBD UI standard
1. Data logging, informative, easy control, battery backup for moving. No training needed in normal operation due to similarity with familiar designs.
