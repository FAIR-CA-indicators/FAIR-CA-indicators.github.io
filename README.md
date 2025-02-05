# Welcome to the FAIR COMBINE Archive Indicators project

## Project coordination: [Irina Balaur](https://sites.google.com/view/irinabalaur/home) and [Dagmar Waltemath](https://www.fis.med.uni-greifswald.de/FIS/init_person_browser.action?pers_id=ngpocpv7uc2ss)

Many computational models have been developed and published for the past 20 years to investigate biochemical to multiorgan mechanisms in humans as well as animal models. Disease maps have been provided to integrate the various complex levels of information leading to insights on disease progression; the latest example is the [COVID-19 Disease Map](https://covid.pages.uni.lu/). These resources are becoming increasingly interesting for clinician 
scientists, as supporting tools for diagnosis, therapy, and scientific investigations using patient data. However, the uptake of computational models in the clinic is still hindered for several reasons (including limited reusable annotations in the models, lack of standardisation of the 
properties/ settings indicating how the model can be used for computational simulations, insufficiently clear specifications on the model kinetics, reduced reproducibility of the model simulation results, see for example [https://doi.org/10.15252/msb.20209982](https://doi.org/10.15252/msb.20209982), [http://ceur-ws.org/Vol-1692/paperC.pdf](http://ceur-ws.org/Vol-1692/paperC.pdf). 

We believe that a major roadblocker is the lack of trust in a model’s quality. More transparency and objective measures of model quality will increase trust and thus improve cross-disciplinary collaboration in clinical and health research. With this project, a first step towards trust building and cross-discipline communication is taken. We believe that FAIR can be a connecting principle as it is recognised and appreciated in both clinical research and systems biomedicine. 

## New! Workshop at HARMONY 2023
We run a workshop at the [HARMONY 2023 conference](https://co.mbine.org/events/) on April 26. Please join us for some hands-on sessions, here is the schedule in local time, remote attendance is possible: 

|9am PDT (6pm CEST) | Update from the EOSC FAIR COMBINE Archive Indicators	| Irina Balaur and Dagmar Waltemath |
|9:20am PDT (6:20pm CEST) |	Status of FAIR evaluation tool | Francois |
|9:45am PDT	(6:45pm CEST) | Task distribution for hands-on session | Irina Balaur and Dagmar Waltemath |
|10am PDT (7pm CEST) | Start hacking | all :) |
|12:30pm PDT (9:30pm CEST) | Wrap up | all |

We will offer a meeting room on site as well as breakout rooms on Zoom. Further details and the Zoom link are provided via the HARMONY2023 slack channel, or write an email to [Dagmar Waltemath](https://www.fis.med.uni-greifswald.de/FIS/init_person_browser.action?pers_id=ngpocpv7uc2ss).

## Project goals (Oct 2022-Mar2023)
1. Achieve Community-consensus on FAIR indicators
2. Develop FAIR evaluation guidelines
3. Implement a FAIR evaluation tool

## Development of FAIR evaluation guidelines: 
The FAIR indicator template adapted to the COMBINE domain is available [here](https://github.com/FAIR-CA-indicators/FAIR-CA-indicators.github.io/blob/main/FAIR_indicators_for_COMBINE/COMBINE_FAIR_assessment_template.xlsx). 

We still do  appreciate your comments. Please use the [Issue](https://github.com/FAIR-CA-indicators/CA-RDA-Indicators/issues) that we created per each indicator to add your comments and edits. Thank you. 

## Implementation of a FAIR evaluation tool:
The FAIR evaluator is a semi-automatic tool for the assessment of a model's or an archive's FAIRness. The scoring is based on the RDA Indicators (RDA FAIR Data Maturity Model Working Group, B. "FAIR Data Maturity Model: specification and guidelines." Res. Data Alliance 10 (2020)) and has then been adjusted to match the specificities of the COMBINE community. The evaluator itself is independent of specific community standards. 
Currently, the tool parses COMBINE archives (OMEX) and models in the SBML, CELLML or SED-ML standard formats. A Docker image of the backend is available for free reuse (Apache-2.0 license). Please see the project repository for more information:

Backend: [https://github.com/FAIR-CA-indicators/fair-ca-indicators-backend](https://github.com/FAIR-CA-indicators/fair-ca-indicators-backend)

Frontend: [https://github.com/FAIR-CA-indicators/fair-ca-indicators-frontend](https://github.com/FAIR-CA-indicators/fair-ca-indicators-frontend)

## Involved communities
* COmputational MOdeling in BIology NEtwork ([COMBINE](https://combine-org.github.io/))
* [BioModels](https://www.ebi.ac.uk/biomodels/)
* Physiome Model Repository ([PMR2](https://models.physiomeproject.org/))

## Related meetings
* Workshop at [COMBINE 2021](https://combine-org.github.io/author/combine-2021/)
* Workshop at [HARMONY 2022](https://combine-org.github.io/author/harmony-2022/)
* Workshop at [COMBINE 2022](https://combine-org.github.io/author/combine-2022/) supported by EOSC Future (no. 101017536).
* Workshop at [HARMONY 2023](https://co.mbine.org/events/) supported by EOSC Future (no. 101017536).

## Outreach and open material 

* Presentation at [Workshop Computational Models in Biology and Medicine](http://www.biometrische-gesellschaft.de/arbeitsgruppen/statistische-methoden-i-d-bioinformatik/workshop2023.html) in Stuttgart, June 15, 2023 - [DOI: 10.5281/zenodo.8318673](https://doi.org/10.5281/zenodo.8318673).

* Presentation at [12th EURINT INTERNATIONAL CONFERENCE - Challenges and future prospects for a resilient Europe| 
Open science opportunities and practices in social sciences](https://eurint.uaic.ro/) in Iasi, Romania, May 19-20, 2023 - [DOI: 10.5281/zenodo.8044822](https://doi.org/10.5281/zenodo.8044822).

* Presentation at [EOSC Symposium](https://symposium22.eoscfuture.eu/) in Prague, Czech Republic, November 14-17, 2022 - [DOI: 10.5281/zenodo.7405912](http://doi.org/10.5281/zenodo.7405912). [Abstract (talk 5)](https://symposium22.eoscfuture.eu/symposium/fair-enabling-practices/)

* Presentation at [ICSB 2022](https://www.icsb2022.berlin/) in Berlin, Germany, October 11, 2022 - [DOI: 10.5281/zenodo.7716716](http://doi.org/10.5281/zenodo.7716716). [Abstract](https://easychair.org/smart-program/ICSB2022/2022-10-11.html#talk:205389)

* Poster at [ICSB 2022](https://www.icsb2022.berlin/) in Berlin, Germany, October 11, 2022 - [DOI:  10.5281/zenodo.7716885]( http://doi.org/10.5281/zenodo.7716885).

* Our [webpage](https://eoscfuture-grants.eu/node/274) on the EOSCFuture website.
  
* Our [webpage](https://www.rd-alliance.org/rda-indicators-within-combine-community) on the RDA website.

## Getting involved 
* Join our [Mailing List on Google Groups](https://groups.google.com/g/fair-ca-indicators)
* Sign up to the related [github projects](https://github.com/FAIR-CA-indicators) of your interest, try out the indicators, add examples
* Join our regular community calls (first Friday each month, 11-12am. Pls contact [Dagmar Waltemath](https://www.fis.med.uni-greifswald.de/FIS/init_person_browser.action?pers_id=ngpocpv7uc2ss) to receive the Zoom link).
* Become an <paid> intern at the Medical Informatics Laboratory at University Medicine Greifswald or at the University of Luxembourg between October 2022 and March 2023. 

## Funding
<table>
    <td style="width:120px; text-align:center; font-size:90%; padding-top:0.4em;"><img src="../pics/funding/eu_flag.jpg" width="110"/></td>
    <td style="vertical-align:top; padding-left:0.8em; padding-top:0.4em;">This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 101017536.</td>
</table>
