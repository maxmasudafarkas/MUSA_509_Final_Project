# Proposal: Philadelphia Transit Reliability Dashboard

**By**:
* Ben Aiken, Ben She, Max Masuda-Farkas

## Abstract

The experience of waiting for minutes, sometimes tens of minutes, after a bus or train was scheduled to arrive has become an all too familiar one for many public transit riders in the United States.  Among the many roadblocks facing transit agencies—not least of which, the COVID-19 pandemic—a persistent lack of reliability stands as a significant one, undermining public trust in a system already short on resources.  To ensure long-term sustainability, transit agencies have a mandate to deliver better services.

There is recently, however, much reason to be hopeful.  With the passage of the landmark federal infrastructure package, states and localities are poised to receive an influx of needed capital to improve local infrastructure.  A sizable portion of that bill has been designated for public transit improvements.  Help, it seems, is on the way.

The question for local transit agencies thus will soon become one of allocation: Where are the funds most needed?  Transit data offer a powerful means to answer just this question.  Agencies such as Philadelphia’s Southeastern Pennsylvania Transportation Authority (SEPTA) assiduously collect data related to their transportation services to monitor operations, identify problems, and ultimately strive to deliver a better passenger experience.

Yet, these data are too often out of reach to the very stakeholders for which improvements are made: passengers.  Although passengers may technically have access through open data, raw data are functionally meaningless to them if not presented in a legible form.  Moreover, because passengers make up the electorate that authorizes transit agencies to function in the first place, they are entitled to have access to these data in a form they can understand.

Philadelphia is one such city where transit data are available in abundance but have not been rendered in a form comprehensible to end users.  This dashboard will set out to fill the gap.  It will offer an up-to-date view of transit data in Philadelphia, evaluating reliability and communicating it in a manner understandable to agencies and lay individuals alike.  

The dashboard will focus primarily on SEPTA rail and bus services, incorporating both static and real-time data to produce key reliability metrics.  The dashboard will give users a detailed look at these transit options not only from a global view, but also from the neighborhood level.  This will ensure that individuals can gain a sense of the transit landscape as it directly affects their immediate surroundings, as well as the broader city.  With such a view, transit passengers—and especially transit advocates—can draw attention to the specific areas where public investment is in greatest need.

## Stakeholders

* Public transit passengers; particularly, transit advocates
* Transit agencies

## Data sources

- **SEPTA Google Transit Feed Specification (GTFS)** -- [SEPTA GTFS](http://www3.septa.org/developer/), static and real-time bus and rail data, updated daily.
- **US Census Block Group demographics** -- BigQuery public datasets, updated with the national census, i.e. yearly estimates at its most frequent
- **Philadelphia Neighborhoods** -- [OpenDataPhilly](https://www.opendataphilly.org/dataset/philadelphia-neighborhoods/resource/6c61f240-aafe-478e-b993-b75fd09a93d6)


## Wireframes

[More Detail](https://docs.google.com/presentation/d/1WQt_ryHEUxQoZPnBtShEOhjGH0DA1yorD8q37yPxdwg/edit?usp=sharing)

Quick sketches:
* ![Wireframe-main_page](https://user-images.githubusercontent.com/90015778/142436296-ede8397d-e6fd-4e5c-a699-4bc648a6ef51.jpg)

* ![Wireframe-neighborhood_page](https://user-images.githubusercontent.com/90015778/142436366-9512a719-bf1d-4498-9622-09736dc963a8.jpg)
