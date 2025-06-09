# db-first

| name               | type         | attributes | index       |
| ------------------ | ------------ | ---------- | ----------- |
| id                 |              | serial     | PRIMARY KEY |
| name               | VARCHAR(20)  | NOT NULL   |             |
| km                 | MEDIUMINT    |            |             |
| price              | MEDIUMINT    |            |             |
| model              | VARCHAR(20)  |            |             |
| fuel_type          | VARCHAR(15)  |            |             |
| gear_box           | VARCHAR(15)  |            |             |
| first_registration | DATE         |            |             |
| seats              | TINYINT      |            |             |
| doors              | TINYINT      |            |             |
| power              | VARCHAR (10) |            |             |
| emission_class     | VARCHAR (10) |            |             |
| emissions          | VARCHAR(10)  |            |             |
| colour             | VARCHAR(10)  |            |             |
| manufacter_color   | VARCHAR (10) |            |             |
| description        | TEXT         |            |             |
