## The JOIN operation

##### game
| id   | mdate        | stadium                   | team1 | team2 |
|------|--------------|---------------------------|-------|-------|
| 1001 | 8 June 2012	| National Stadium, Warsaw	| POL   |	GRE   |
| 1002 | 8 June 2012	| Stadion Miejski (Wroclaw)	| RUS   |	CZE   |
| 1003 | 12 June 2012 |	Stadion Miejski (Wroclaw)	| GRE   |	CZE   |
| 1004 | 12 June 2012 |	National Stadium, Warsaw	| POL   |	RUS   |
|.... |

##### goal
| matchid |	teamid | player               |	gtime |
|---------|--------|----------------------|-------|
| 1001    |	POL    | Robert Lewandowski   | 17    |
| 1001    |	GRE    | Dimitris Salpingidis | 51    |
| 1002    |	RUS    | Alan Dzagoev         |	15    |
| 1002    |	RUS    | Roman Pavlyuchenko	  | 82    |
|.... |

##### eteam
| id  | teamname       | coach            |
|-----|----------------|------------------|
| POL | Poland         | Franciszek Smuda |
| RUS | Russia         | Dick Advocaat    |
| CZE | Czech Republic | Michal Bilek     |
| GRE | Greece         | Fernando Santos  |
|... |

##### 13
| mdate	       | team1 |score1 | team2 | score2 |
|--------------|-------|-------|-------|--------|  
| 1 July 2012  | ESP   | 4     | ITA   | 0      |
| 10 June 2012 | ESP   | 1     | ITA   | 1      |
| 10 June 2012 | IRL   | 1     | CRO   | 3      |
| ... |