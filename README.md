# Anki flashcard decks for AWS Architecture Icons

## Overview

This project consists of flashcard decks for the Amazon Web Services Architecture Icons. These decks are intended for use with [Anki][1], a spaced-repetition flashcard application. 

The decks may be used to memorize the icons and symbols used to represent AWS services, resources, etc. in architecture diagrams. The intended audience is people who are learning about the AWS platform. 

The architecture icons themselves may not necessarily appear on the exams, which are predominantly text based. However, learners may find it helpful to memorize them as it makes it easier to read architecture diagrams in documentation, training materials, and so on. 

## Installation

Download the [shared deck package][2] from AnkiWeb. 

Alternatively, you may install the [CrowdAnki add-on][3], then clone the deck repository locally, and import the deck using CrowdAnki. 

## About the icons

The images are from the [official AWS icon set][4] which Amazon provides to the public for use in technical materials. 

Version 1.0.0 of this deck was created using the icons included in the [Q2 2023 Asset Package][5] provided by AWS. 

## Tags

The flashcards are tagged to make it easier for learners to prioritize the icons that are most relevant to one's interests, particularly for users who are pursuing AWS certification. 

If a card's material is in scope for a particular exam (according to the [AWS exam guide][6] appendices), then a tag is included to reflect that. 

For example, a person studying for the AWS Certified Developer Associate certification may wish to focus on memorizing information about services that are in-scope only for that exam. 

To do so, select the deck in Anki, then open the card [browser][7]. Then [search][8] for `deck:current tag:AWS-Developer-Associate`. Then select any cards of interest, and use the Reposition feature (available form the Cards dropdown menu) to move those cards to the top of the new card queue. 

### Tags by exam:

```
AWS-Cloud-Practitioner
AWS-Solutions-Architect-Associate
AWS-Developer-Associate
AWS-SysOps-Administrator-Associate
AWS-Solutions-Architect-Professional
AWS-DevOps-Engineer-Professional
AWS-Specialty-Security
AWS-Specialty-Databases
AWS-Specialty-Data-Analytics
AWS-Specialty-Advanced-Networking
AWS-Specialty-Machine-Learning
AWS-Specialty-SAP
```

### Tags by certification track:

```
AWS-Solutions-Architect
AWS-Developer
```

### Tags by certification tier:

```
AWS-Foundation
AWS-Associate
AWS-Professional
AWS-Specialty
```

## Known Issues

If you wish to submit a fix for any of the issues below or any other issue that you are aware of, please refer to `CONTRIBUTING.md`. 

- Over time, as AWS revises the official asset pack, these decks will require updating. Refer to the [AWS Architecture Icons site][4] for the latest icons. 

- The answer (back) side of the notes were generated from the SVG filenames in the assets bundle. Therefore, ampersands which may belong in service and resource names may be missing from the notes. (For example, if you see "Management Governance", it should actually be "Management & Governance".) Some of these have been corrected, but some may still be missing the ampersand or other special characters that were not included in the image filenames. 

[1]: https://apps.ankiweb.net
[2]: https://ankiweb.net/shared/info/561791217
[3]: https://ankiweb.net/shared/info/1788670778
[4]: https://aws.amazon.com/architecture/icons/
[5]: https://d1.awsstatic.com/webteam/architecture-icons/q2-2023/Asset-Package_04282023.ca9655a386a46bda0b6238cca2651e8f27fcb5c9.zip
[6]: https://aws.amazon.com/certification/certification-prep/
[7]: https://docs.ankiweb.net/browsing.html
[8]: https://docs.ankiweb.net/searching.html
