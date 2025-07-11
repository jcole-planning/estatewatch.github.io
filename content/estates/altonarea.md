---
name: Alton estate
borough: wandsworth
tags: wandsworth
location: '[51.450221,-0.243483]'
ballot: Required
landlord: Wandsworth Council
architect: Hawkins Brown
total: 288
image: estates/src/images/altonthumblarge.jpg
developer:
itla:
planning:
---
![Alton estate image](src/images/altonthumblarge.jpg)

As detailed in Wandsworth Council’s 2014 Regeneration Masterplan for the estate, 288 homes were earmarked for demolition on Wandsworth's Alton estate in Roehampton, but due to pressures arising from the pandemic, the withdrawal of the developer from the scheme and a change in political administration, Wandsworth Council stopped the procurement for a new development partner and announced they would reconsider proposals for regeneration in September 2022. In this announcement they stated that they were willing to explore all options.

The homes that were under threat of demolition stand around Danebury Avenue to the Southeast of the Estate rather than the tower blocks clustered in the middle of the estate or the five large linear blocks to the north, which are listed. 


Wandsworth Council had [claimed](https://www.wandsworth.gov.uk/media/1627/roehampton_adopted_spd_oct_2015.pdf) that demolition was necessary because the design of the buildings is poor and encourages anti-social behaviour:

![Alton estate image](src/images/altospd.png)

In 2017, Wandsworth signed a joint venture agreement with developer Redrow for the redevelopment of the estate.

Despite the existing estate comprising an almost even split of social rented and private homes (leaseholders and freeholders), it was [claimed](https://planning2.wandsworth.gov.uk/iam/IAMCache/5300271/5300271.pdf) that *"the limited diversity in housing tenures and high proportion of social housing has inhibited the creation of a genuinely mixed and balanced community"*.

![Alton estate image](src/images/socialmix.png)

Redrow submitted a planning application in late 2019, but in August 2020 it announced that it was pulling out of the scheme. Wandsworth Council went ahead and approved the application despite this in October 2020, giving consent for demolition and construction of 1,108 new homes of which 261 affordable (201 social rent). 

In his [stage 1 response](https://www.london.gov.uk/sites/default/files/public%3A//public%3A//PAWS/media_id_471293///alton_estate_report.pdf) to the planning application, the Mayor highlighted concerns about lack of consultation (para 36), quantum and rent levels of replacement 'social housing' (para 27) and the failure to apply for grant funding (para 39) and the failure to explore alternatives to demolition (para 20).

The requirement for the demolition of housing estates only to be considered as a last resort, is enshrined both in the Mayor's [Estate Regeneration Guidance](https://www.london.gov.uk/sites/default/files/better-homes-for-local-people-the-mayors-good-practice-guide-to-estate-regeneration.pdf) and the [London Plan itself](https://www.london.gov.uk/sites/default/files/intend_to_publish_-_clean.pdf):

![Alton estate image](src/images/londplanh8.png)

Despite these concerns, the Mayor's stage 2 [report](https://twitter.com/AltonAction/status/1322956962439507971) concluded that on balance the Mayor was happy with Wandsworth's decision to approve its planning application for the redevelopment of the estate.

In the meantime, estate residents got themselves [organised](https://twitter.com/AltonAction/status/1322956962439507971) aand formed the Alton Action campaign. They reached out to Daniel Fitzpatrick and Pablo Sendra, who then brought in Just Space, and with their support successfully applied for funding from Research England’s Higher Education Innovation Fund to co-produce a Community Plan exploring alternatives to demolition. In this process they were assisted by a group of researchers from [University College London](www.ucl.ac.uk) and the [Just Space network](www.justspace.org.uk).

Between October 2020 and July 2021, this team conducted a knowledge exchange project ‘Co-designing neighbourhoods with communities in a blended environment: digital and face-to-face knowledge exchange’. This was an iterative process that involved 8 community co-design sessions, the final output of which was the Alton Estate People’s Plan, which was published in September 2021. A summary document of the People’s Plan was produced in July 2023. 

This plan included a heritage impact assessment, embodied carbon analyses and provision for a higher number of social rented homes than Wandsworth Plans. The plan involved retention of the majority of the existing buildings with housing delivered through roof extensions. 

![Alton estate image](src/images/altonaction.png)

In September 2022, demolition plans were put on hold under proposals to review schemes following a change of political administration and ongoing viability concerns. The new Labour administration also claimed that the lack of affordable housing provision was part of their rationale. Alton Action met cabinet leads soon after the elections to explain the People’s Plan. The council appointed the consultancy Inner Circle to explore options and looked into taking the review of the plan in-house.

In July 2024, Wandsworth Council launched the [Alton Renewal Plan](https://www.wandsworth.gov.uk/news/news-july-2024/alton-renewal-gets-underway-with-new-council-investment-across-the-estate/) creplacing the Council’s previous 2014 Regeneration Masterplan. In the shorter-term these plans involved:

- Re-design of the Alton Activity Centre to cater for children of all ages, and improve the play space on Downshire Field by Spring 2026
- Creation of a new Roehampton Community Hub on the empty site on the corner of Roehampton Lane and Danebury Avenue. This proposes a new library, youth club and 40 new Council rent homes. Construction is to start mid-2026 and is expected to be completed by mid-2028

In the same month, Wandsworth Council’s Housing Overview and Scrutiny Committee  [discussed](https://www.wandsworth.gov.uk/media/122nf32u/housing_committee_paper_24_170.pdf/)

---

**Links:**   
[Roehampton (Alton estate) SPD Oct 2015](https://www.wandsworth.gov.uk/media/1627/roehampton_adopted_spd_oct_2015.pdf)

[Mayor's stage 1 report](https://www.london.gov.uk/what-we-do/planning/planning-applications-and-decisions/planning-application-search/alton-estate)

[Link to the revised planning application docs (ref:2019/2156)](https://planning1.wandsworth.gov.uk/Northgate/PlanningExplorer/Generic/StdDetails.aspx?PT=Planning%20Applications%20On-Line&TYPE=PL/PlanningPK.xml&PARAM0=977340&XSLT=/Northgate/PlanningExplorer/SiteFiles/Skins/Wandsworth/xslt/PL/PLDetails.xslt&FT=Planning%20Application%20Details&PUBLIC=Y&XMLSIDE=/Northgate/PlanningExplorer/SiteFiles/Skins/Wandsworth/Menus/PL.xml&DAURI=PLANNING)

---

<!------------THE CODE BELOW RENDERS THE MAP - DO NOT EDIT! ---------------------------->

<div id="map" style="width: 100%; height: 400px;"></div>

<script>
  var map = L.map('map').setView({{ location }}, 13);
  L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
  maxZoom: 19,
attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
}).addTo(map);
var circle = L.circle({{ location }}, {
    color: 'red',
    fillColor: '#f03',
    fillOpacity: 0.5,
    radius: 500
}).addTo(map);
</script>

---

![Alton estate image](src/images/alton2.jpg)

