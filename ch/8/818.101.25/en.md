---
sr: "818.101.25"
title: Ordinance of 24 June 2020 on the Proximity Tracing System for the Sars-CoV-2 coronavirus (PTSO)
eli: "https://fedlex.data.admin.ch/eli/cc/2020/468"
language: en
version: 2021-03-18
adopted: 2020-06-24
in_force: 2020-06-25
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2020/468/20210318/en/xml/fedlex-data-admin-ch-eli-cc-2020-468-20210318-en-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2020/468/20210318/en"
---

> Unofficial reproduction of the consolidated version (Fedlex). English is not an official language of the Confederation: this translation is for information only and has no legal force. Only the publication in the Official Compilation is authoritative (Art. 15 PublA, SR 170.512).

# Ordinance on the Proximity Tracing System for the Sars-CoV-2 coronavirus

English is not an official language of the Swiss Confederation. This translation is provided for information purposes only, has no legal force and may not be relied on in legal proceedings.

(PTSO)

of 24 June 2020 (Status as of 18 March 2021)

The Swiss Federal Council,

on the basis of Article 60*a* paragraph 7 of the Epidemics Act of 28 September 2012[^ingress-1] (EpidA),

ordains:

[^ingress-1]: [SR 818.101](https://fedlex.data.admin.ch/eli/cc/2015/297)

#### Art. 1

**Subject matter**

This Ordinance regulates the details of the organisation, operation and data processing of the Proximity Tracing System for the Sars-CoV-2 coronavirus under Article 60*a* EpidA (PT System).

#### Art. 2

**Structure**

<sup>1</sup>

The PT System comprises the following components:

- a. a proximity data management system (the PDM System), consisting of a software application that users install on their smartphones (the SwissCovid app), and a back end (PDM back end);
- b. a system for managing codes for releasing the notifications (the code management system), consisting of a web-based front end and a back end.
- [tab] <sup>2</sup> The PDM back end and the code management system are operated as a central server by the Federal Office of Public Health (FOPH).

#### Art. 3

**Voluntary nature**

<sup>1</sup> Installation and use of the SwissCovid app are voluntary.

<sup>2</sup> The express consent of the infected person is required before a notification is sent to app users who have potentially been exposed to the coronavirus.

#### Art. 4

**Federal authority responsible**

The FOPH is the federal authority responsible for all components of the PT System under data protection law.

#### Art. 5

**Basic operation procedure**

<sup>1</sup>

During basic operations, the PDM back end makes its content available online to the SwissCovid apps. The content comprises a list with the following data:

- a. the private keys of infected app users which were effective in the period in which other app users were potentially exposed to the coronavirus (“the relevant period”);
- b. the date of each key.

<sup>2</sup>

The SwissCovid app carries out the following functions via an interface to the mobile phone’s operating system:

- a. It generates a new private key at least every day that does not permit the SwissCovid app, the mobile telephone or the user to be traced.
- b. It exchanges a variable identification code at least every half-hour with all compatible apps within Bluetooth range; the identification code is derived from the current private key but may not be traced back to that key and does not permit the SwissCovid app, the mobile telephone or the user to be traced.
- c. It stores the identification codes received, details of the strength of the signal, the date and the estimated duration of the encounter*.*
- d. It periodically retrieves the list of private keys belonging to infected app users from the PDM back end and checks whether any of the identification codes it has stored locally were generated using a private key on the list.
- e.[^5-1] If it establishes that any one of the locally stored identification codes was generated using a private key on the list, and if the encounter requirements set out in the Annex number I are met, the app issues a notification; the distance of the encounter is estimated based on the strength of the signal received.

<sup>3</sup> The operating systems’ functions used via the interface must meet the requirements of Article 60*a* EpidA and this Ordinance; this does not apply to the rule relating to the source code under Article 60*a* paragraph 5 letter e EpidA. The FOPH shall ensure that these requirements are met, in particular by obtaining related assurances.

<sup>4</sup> ...[^5-2]

[^5-1]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^5-2]: Repealed by No I of the O of 18 Nov. 2020, with effect from 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 6

**Procedure following an infection**

<sup>1</sup> If a user tests positive for the coronavirus, an authorised agency may with the consent of the infected person request a unique activation code with time-limited validity from the code management system; to do so, the agency sends the code management system the date on which the first symptoms occurred or, if the infected person has not displayed any symptoms, the date of the test.[^6-1]

<sup>2</sup> The authorised agency gives the activation code to the infected person.[^6-2] The infected person may choose to enter the activation code into their SwissCovid app.

<sup>3</sup> The code management back end sends confirmation to the SwissCovid app that the code entered is valid. It deducts the number of days specified in Annex number 2 from the recorded date.[^6-3] The resulting date is the start of the relevant period. The code management back end sends this date to the infected person’s SwissCovid app.

<sup>4</sup> The infected person’s SwissCovid app sends the private keys that were effective in the relevant period to the PDM back end, together with their dates.

<sup>5</sup> The PDM back end records the received private keys with their dates on its list.

<sup>6</sup> After the private keys have been sent, the SwissCovid app generates a new private key. This key cannot be used to identify earlier private keys.

[^6-1]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^6-2]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^6-3]: Second sentence amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 7

**Content of the notification**

<sup>1</sup>

The notification contains:

- a. the information that the app user has potentially been exposed to the coronavirus;
- b.[^7-1] a note of the days on which exposure may have occurred;
- c. the information that the FOPH operates an infoline that provides advice free of charge;
- d. recommendations from the FOPH on what to do.

<sup>2</sup> The PT System does not issue any instructions to app users.

[^7-1]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 8

**Content of the code management system**

<sup>1</sup>

The code management system contains the following data:

- a. the activation codes;
- b. the date on which the first symptoms occurred, or, if the infected person has not displayed any symptoms, the date of the test;
- c. the time when the data in accordance with letters a and b will be destroyed.

<sup>2</sup> These data cannot be used to identify app users.

#### Art. 8a

**Form of access to the code management system**[^8a-1]

The code management system may be accessed via:

- a. a specialist from the authorised agency via the front end; or
- b. an interface between the code management system and a system operated by the authorised agency.

[^8a-1]: Inserted by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 9

**Access to the code management system via the front end[^9-1]**

<sup>1</sup>

The following persons acting for the authorised agency may request the activation code via the front end:[^9-2]

- a. cantonal medical officers;
- b. the Armed Forces Surgeon General;
- c. other staff of the cantonal medical services or of the Armed Forces medical services;
- d. third parties acting on behalf of the cantonal medical services or the Armed Forces medical services;
- e.[^9-3] staff at medical practices;
- f.[^9-4] staff at laboratories with authorisation under Article 16 EpidA;
- g.[^9-5] staff at the facilities specified in Article 24 paragraph 1 letter b of the COVID 19 Ordinance 3 of 19 June 2020[^9-6];
- h.[^9-7] staff of the Infoline under Article 7 paragraph 1 letter c.

<sup>2</sup> The code management system is accessed via the Federal Administration’s Central Access and Permission System for web applications. The provisions of the Ordinance of 19 October 2016[^9-8] on Federal Identity Management Systems and Directory Services apply.

<sup>3</sup> The FOPH assigns and manages access rights to the code management system. It may authorise cantonal medical officers and the Armed Forces Surgeon General or a specific member of their auxiliary personnel to grant access rights to auxiliary personnel.

[^9-1]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-2]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-3]: Amended by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-4]: Inserted by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-5]: Inserted by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-6]: [SR 818.101.24](https://fedlex.data.admin.ch/eli/cc/2020/438)
[^9-7]: Inserted by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-8]: [SR 172.010.59](https://fedlex.data.admin.ch/eli/cc/2016/610)

#### Art. 9a

**Access to the code management system via the interface**[^9a-1]

The FOPH shall enable the authorised agencies under Article 9 paragraph 1 to connect their systems via the interface to the code management system, provided the systems concerned provide an appropriate level of security.

[^9a-1]: Inserted by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 10

**Services from third parties**

<sup>1</sup> The FOPH may instruct third parties to provide the SwissCovid app with online access to the list of data required for notifications.

<sup>2</sup> It may the assign the task of granting rights of access to the code management system to third parties. The third party concerned must guarantee that the authorisation of specialists is verified reliably and in accordance with the law.

<sup>3</sup> The third parties must be contractually required to comply with the requirements of Article 60*a* EpidA and of this Ordinance; this does not apply to the regulation relating to the source code under Article 60*a* paragraph 5 letter e EpidA. The FOPH shall verify compliance with the requirements.

#### Art. 11

**Records of access**

<sup>1</sup> Articles 57*i*–57*q* of the Government and Administration Organisation Act of 21 March 1997[^11-1] and the Ordinance of 22 February 2012[^11-2] on the Processing of Personal Data accumulated through the Use of the Confederation’s Electronic Infrastructure apply to the storing and the evaluation of the records of access to the PDM back end, the code management system and the list under Article 10 paragraph 1.

<sup>2</sup> Apart from these records and records of encounters, the PT System does not maintain any record of the activities of the front end of the code management system and the SwissCovid app.

[^11-1]: [SR 172.010](https://fedlex.data.admin.ch/eli/cc/1997/2022_2022_2022)
[^11-2]: [SR 172.010.442](https://fedlex.data.admin.ch/eli/cc/2012/160)

#### Art. 12

**Disclosure for statistical purposes**

The FOPH shall regularly provide the Swiss Federal Statistical Office (FSO) with the latest collection of data in the two back ends in a completely anonymised form for statistical assessment.

#### Art. 13

**Destruction of the data**

<sup>1</sup> The data in the PDM System shall be destroyed both on the smartphones and in the PDM back end 14 days after they are recorded.

<sup>2</sup> The data in the code management system shall be destroyed 24 hours after they are recorded.

<sup>3</sup> The record data of third parties assigned tasks under Article 10 paragraph 1 shall be destroyed 7 days after they are recorded.

<sup>4</sup> In addition, the destruction of record data is governed by Article 4 paragraph 1 letter b the Ordinance of 22 February 2012[^13-1] on the Processing of Personal Data accumulated through the Use of the Confederations Electronic Infrastructure.

<sup>5</sup> The data made available to the FSO shall also be destroyed in accordance with this Article.

[^13-1]: [SR 172.010.442](https://fedlex.data.admin.ch/eli/cc/2012/160)

#### Art. 14

**Verification of the source code**

<sup>1</sup> The FOPH shall publish the data that allows verification of whether the machine readable programmes of all components of the PT System have been produced using the published source code.

<sup>2</sup> It shall also verify this itself.

#### Art. 15

**Deactivation of the SwissCovid app and reporting**

<sup>1</sup> When this Ordinance ceases to apply, the FOPH shall deactivate the SwissCovid app and instruct users of the SwissCovid app to remove the app from their mobile phones.

<sup>2</sup> The FOPH shall submit a report to the Federal Council within six months of this Ordinance ceasing to apply.

#### Art. 15a

**Connection of the PT System to related foreign systems**[^15a-1]

<sup>1</sup> The PT System may only be connected to a foreign system (Art. 62*a* EpidA) if that system meets the requirements of Article 60*a* paragraph 5 letters a–d EpidA.

<sup>2</sup> When connected, the VA backend and the foreign system are linked to an interconnection system for the mutual transmission of the private keys of infected app users.

<sup>3</sup>

The connection system is subject to the following rules:

- a. It is operated by the FOPH or the responsible foreign body.
- b. Article 60*a* paragraph 5 letter e EpidA and Article 14 of this Ordinance apply to the source code and the technical specifications of the connection system that the FOPH operates.
- c. The data processing purposes are governed by Article 60*a* paragraph 2 EpidA.
- d. The data in the system may be passed on to the FSO and the responsible foreign body in completely anonymised form for statistical purposes.
- e. The data shall be erased as soon as they are no longer required in order to notify app users, but at the latest 14 days after their transmission to the system.

<sup>4</sup>

If the PT System is connected to a foreign system, the following applies in relation to the PT System’s operating procedures in addition to Articles 5 and 6:

- a. During basic operations, the VA backend retrieves the private keys of infected users of the foreign system and the date of these keys from the connection system and places them on its list.
- b. Following an infection, the VA backend transmits the private keys of the infected persons with the relevant date to the foreign system via the connection system.

[^15a-1]: Inserted by No I of the O of 12 March 2021, in force since 18 March 2021 ([AS 2021 144](https://fedlex.data.admin.ch/eli/oc/2021/144)).

#### Art. 16

**Repeal of other legislation**

The COVID-19 Ordinance of 13 May 2020[^16-1] on the Proximity Tracing Pilot Trial is repealed.

[^16-1]: [[AS 2020 1589](https://fedlex.data.admin.ch/eli/oc/2020/324)]

#### Art. 16a

**Updating the Annex**[^16a-1]

The Federal Department of Home Affairs (FDHA) shall update the Annex to this Ordinance in accordance with the current state of the art.

[^16a-1]: Inserted by No I of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 17

**Commencement and duration**

This Ordinance comes into force on 25 June 2020 at 00.00 and applies until 30 June 2022.

Annex*[^t-1]*

(Art. 5 para. 2 let. e and 6 para. 3)

## Epidemiological conditions for an encounter and relevant period

[^t-1]: Amended by No II of the O of 18 Nov. 2020, in force since 19 Nov. 2020 ([AS 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

### 1. Epidemiological conditions for an encounter

The epidemiological conditions for an encounter to have taken place are fulfilled if the following requirements are met:

- a. There has been physical proximity of 1.5 metres or less to at least one mobile phone that pertains to an infected user.
- b. The sum of the duration of all encounters in terms of letter a within any single day is equal to or in excess of fifteen minutes.

### 2. Start of the relevant epidemiological period

Number of days to be deducted: two.
