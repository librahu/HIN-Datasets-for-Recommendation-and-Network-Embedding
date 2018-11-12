# DatasetInPaper

## MovieLens

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

## Yelp

## DBLP
(Note: author_map_id.dat map the author id to the unique id)
### Entity Statistics
| Entity         |#Entity        |
| :-------------:|:-------------:|
| Author         | 14,475        |
| Paper          | 14,376        |
| Author_label   | 4             |
| Conference     | 20            |
| Type           | 8920          |

### Relation Statistics
| Entity             |#Entity        |
| :-----------------:|:-------------:|
| Author - Label     | 4,057         |
| Paper - Author     | 41,794        |
| Paper - Conference | 14,376        |
| Paper - Type       | 114,624       |
