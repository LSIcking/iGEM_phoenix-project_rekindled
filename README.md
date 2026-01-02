![image](https://github.com/LSIcking/iGEM_phoenix-project_rekindled/blob/main/images/PPR_logo.png?raw=true)


# iGEM Phoenix-Project - Rekindled
Overhaul/Revamp of the [iGEM Phoenix Project](https://community.igem.org/projects/phoenix-project)

The Phoenix Project was imagined as a database to help researchers and iGEM teams to get an overview what kind of project have been tackled in the past. Teams are listed on on the [teams page of the competition](https://teams.igem.org/). This page was not build for the purpose of having an easily structured search for basic information of the teams. Therefore, the Phoenix Project fills an, in my opinion, important gap to help teams search for project that have worked on similar projects in the previous years and maybe tackled similar problems the teams are facing.

As this reimagine of the database is not made in official collaboration with iGEM, it will be hosted on this GitHub.

## Description
The Phoenix Project rekindled (PPR) v1.0 should serve as an addition to the previous Project Phoenix database. The previous version stopped including teams after 2022 so at the moment it is missing data from 2023 onwards. The PPR is imagined to fill this gap in some extend with revamps of how the colums are arranged together with dismissing some information and adding in new information.

## Changes to the previous version
### Removals
**Parts:**
Parts are one of the most important things that come out of an iGEM project. Therefore, it seems rather counter-intuitive to remove the summarised part links as a whole. At the moment, these links appear to be mostly broken with no part pages loading at all. This is hopefully a feature that can be reintroduced in a later version of the PRR after the [registry is finished with the overhaul](https://registry.igem.org/).

**Institutions:**
Institutions has been ommitted due to the different formatting of how institutions are embedded in on the team's page. This made it rather difficult to create a webscraper that grabs all institutional data in their different formats. As this information has not been seen as crucial for the database, it has been ommitted for the time being. The team name together with the country serve similar information.

### Additions
Something that had not been found in the PP database was information on the team roster. As this could be interesting for statistics and to follow people throughout their iGEM journey via their membership, the information has been added. The roster has been incorporated into the database via the following new columns: "PIs", "instructors", "advisors", "student leaders", "students", and for a quick overview of how many roster members have been registered, "roster members". This kind of information is thought to be mostly interesting for people into statistics or chronology of iGEMers, this is a format that should make it most easy to work with this information. As to my knowledge, it is no quite clear what is the difference between primary PIs and secondary PIs, seeing that there can be multiple primary and secondary PIs, these two positions have been merged in "PIs". The difference is also not clearly defined by [iGEM itself](https://competition.igem.org/registration/principal-investigators).

### Revisions
- "Track" has been renamed as "village"
- "Project Title" has been renamed as "title"
- "Team name" has been renamed as "team"
- "Location" has been renamed as "country"

### Politics
Something that has been realised rather late is that the PP from iGEM lists countries as "locations", potentially to get around hot political conflicts and appear as "neutral". As this information on the team pages is listed under countries, the column also carries the name "country" in the PPR.

### Errors
If you found some errors in the table regarding any information, feel free to create an issue for the error.
