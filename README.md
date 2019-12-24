# Dataset Statistics

## MovieLens
(Containing rating and timestamp information)

(Note: We utilize the Pearson's coefficient to measure the similiarities in the KNN algorithm)

(Source : https://grouplens.org/datasets/movielens/)

| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 943           |
| Age            | 8             |
| Occupation     | 21            |
| Movie          | 1,682         |
| Genre          | 18            |

### Relation Statistics
| Relation            |#Relation      |
| :-------------:     |:-------------:|
| User - Movie        | 100,000       |
| User - User (KNN)   | 47,150        |
| User - Age          | 943           |
| User - Occupation   | 943           |
| Movie - Movie (KNN) | 82,798        |
| Movie - Genre       | 2,861         |

## Douban Movie
(Containing rating information)

### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 13,367        |
| Movie          | 12,677        |
| Group          | 2,753         |
| Actor          | 6,311         |
| Director       | 2,449         |
| Type           | 38            | 

### Relation Statistics
| Relation          |#Relation      |
| :-------------:   |:-------------:|
| User - Movie      | 1,068,278     |
| User - Group      | 570,047       |
| User - User       | 4,085         |
| Movie - Actor     | 33,587        |
| Movie - Director  | 11,276        |
| Movie - Type      | 27,668        |
## Douban Book 
(Containing rating information)

### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 13,024        |
| Book           | 22,347        |
| Group          | 2,936         |
| Location       | 38            |
| Author         | 10,805        |
| Publisher      | 1,815         |
| Year           | 64            |

### Relation Statistics
| Relation          |#Relation      |
| :-------------:   |:-------------:|
| User - Book       | 792,062       |
| User - Group      | 1,189,271     |
| User - User       | 169,150       |
| User - Location   | 10,592        |
| Book - Author     | 21,907        |
| Book - Publisher  | 21,773        |
| Book - Year       | 21,192        |
## Amazon
(Containing rating and timestamp information)

(Source : http://jmcauley.ucsd.edu/data/amazon/)
### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 6,170         |
| Item           | 2,753         |
| View           | 3,857         |           
| Category       | 22            |
| Brand          | 334           |

## Relation Statistics
| Relation          |#Relation      |
| :-------------:   |:-------------:|
| User - Item       | 195,791       |
| Item - View       | 5,694         |
| Item - Category   | 5,508         | 
| Item - Brand      | 2,753         |
## LastFM
(Note: We utilize the Pearson's coefficient to measure the similiarities in the KNN algorithm)

(Source : https://grouplens.org/datasets/hetrec-2011/)

### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 1,892         |
| Artist         | 17,632        |
| Tag            | 11,945        |

## Relation Statistics
| Relation               |#Relation      |
| :-------------:        |:-------------:|
| User - Artist          | 92834         |
| User - User (Original) | 25,434        |
| User - User (KNN)      | 18,802        |
| Artist - Artist (KNN)  | 153,399       |
| Artist - Tag           | 184,941       |

## Yelp
(Containing rating information)
### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 16,239        |
| Business       | 14,284        |
| Compliment     | 11            |
| Category       | 511            | 
| City           | 47           |

### Relation Statistics
| Relation            |#Relation      |
| :------------------:|:-------------:|
| User - Business     | 198,397       |
| User - User         | 158,590       |
| User - Compliment   | 76,875        |
| Business - City     | 14,267        |
| Business - Category | 40,009        |

## Yelp-2
(Containing rating information)
### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| User           | 1,286         |
| Business       | 2,614         |
| Service        | 2             |
| Star level     | 9             | 
| Reservation    | 2             |
| Category       | 3             |

### Relation Statistics
| Relation                |#Relation      |
| :----------------------:|:-------------:|
| User - Business         | 30,838        |
| Bussiness - Service     | 2,614         |
| Bussiness - Star level  | 2,614         |
| Business - Revervation  | 2,614         |
| Business - Category     | 2,614         |

## DBLP
(Note: author_map_id.dat map the author id to the unique id)
### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| Author         | 14,475        |
| Paper          | 14,376        |
| Author_label   | 4             |
| Conference     | 20            |
| Type           | 8,920          |

### Relation Statistics
| Relation             |#Relation        |
| :-----------------:|:-------------:|
| Author - Label     | 4,057         |
| Paper - Author     | 41,794        |
| Paper - Conference | 14,376        |
| Paper - Type       | 114,624       |

## Aminer
(Note: author_map_id.dat map the author id to the unique id)
### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| Author         | 164,472       |
| Paper          | 127,623       |
| Papel_label    | 10            |
| Conference     | 101           |
| Reference      | 147,251       |

### Relation Statistics
| Relation             |#Relation        |
| :-----------------:|:-------------:|
| Paper - Label      | 127,623       |
| Paper - Author     | 355,072       |
| Paper - Conference | 127,632       |
| Paper - Reference  | 392,519       |

