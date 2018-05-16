This dataset contains instances of dermatology cancer occurrences.

## Data

This dataset was found on [OpenML - dermatology](https://www.openml.org/d/35)

Original owners: 

* Nilsel Ilter, M.D., Ph.D., 
Gazi University, 
School of Medicine 
06510 Ankara, Turkey

* H. Altay Guvenir, PhD., 
Bilkent University,
Department of Computer Engineering and Information Science,
06533 Ankara, Turkey

Donor: 
* H. Altay Guvenir, 
Bilkent University, 
Department of Computer Engineering and Information Science, 
06533 Ankara, Turkey

Data is located in directory `data`

`data/dermatology.csv`

### Attribute information

#### Class
* 1: psoriasis
* 2: seboreic dermatitis
* 3: lichen planus
* 4: pityriasis rosea
* 5: cronic dermatitis
* 6: pityriasis rubra pilaris

#### Family history:
* 1: if any of these diseases has been observed in the family
* 0: otherwise

#### Age:
* Represents the age of the patient

#### All other attributes:
* 0: feature not present
* 1, 2 indicate the relative intermediate values
* 3 indicates the largest amount possible

## Preparation

Scripts are in directory `scripts`

`scripts/main.py`

## Licence
Licensed under the [Public Domain Dedication and Licence][pddl] (assuming
either no rights or public domain licence in source data).

[pddl]: http://opendatacommons.org/licenses/pddl/1.0/