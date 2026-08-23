# RSSSF Notes


```
json generation:


= Belgium 2024/25
== Pro League
== Cup

=>
{
  "name": "Belgium 2024/25",
  "sections":[
     {"name": "Pro League",
      "matches: []},
     {"name": "Cup",
      "matches: []}
  ]
}

-or-

add section property/key to match record - why? why not?
```



```
- [] new table property - add - why? why not?

Final Table:   | Halfway Table:

until §§  -or-
      next heading `==`   -or-
      leading round (outline) marker `▪`  -or-
      (maybe) double blank??


e.g.

Final Table:

 1.R. Union Saint-Gilloise          10   9  1  0  22- 3  56  [28*]      Champions
 2.Club Brugge KV                   10   7  2  1  21- 6  53  [30*] [C]
 3.KRC Genk                         10   4  1  5  14-11  47  [34]
 4.RSC Anderlecht                   10   3  1  6  12-13  36  [26*]
 5.R. Antwerp FC                    10   2  3  5  10-18  32  [23]
 6.KAA Gent                         10   1  0  9   4-32  26  [23*]

NB: bonus points regular stage (halved, rounded upward) between square brackets
[*] gained an additional half point due to rounding; in case of a tie on points,
    ranked below a club which did not profit from rounding

   §§

or use <>  (diamond) for  end of property ??

````



## Formats Trivia (Conversion Rules)

```
- [ ] fix heading hierachy e.g.

= Belgium 2024/25

== Pro League
=== Regular Stage
=== Playoff Stage
==== Playoff 1
==== Playoff 2
==== Relegation Playoff
=== Promotion/Relegation Playoff   ## note - use same level as Regular/Playoff Stage!!!

== Cup

== Challenger Pro League
=== Promotion Playoff

== 1e Nationale
=== Vlaanderen (VV)
=== Wallonie (ACFF)
==== Regular Season
==== Promotion Playoff
==== Relegation Playoff




- [ ] add (leading) round marker (small black square)

▪ Round 1
▪ Round 2

▪ Semifinals
▪▪ First Legs
▪▪ Second Legs


- [ ] remove enclosing brackets from dates

[Apr 24]  => Apr 24


- [ ]  if round and dates combined on one line, separe into two round and date header lines


Final [May 4]

=>

▪ Final
May 4
```




##  Special Cases

```
Sep 29
  Antwerp           awd. Beerschot         [awarded 5-0; abandoned at 4-0 in 75' due
                                            to crowd trouble]
  Union             3-0 Kortrijk

note - match status note CANNOT overlap with next match e.g.

[Sep 29]
  Antwerp           awd Beerschot         [awarded 5-0; abandoned at 4-0 in 75' due
  Union             3-0 Kortrijk            to crowd trouble]
```

- [ ]  use `awd` or `awd.`  ??





##  use §§ to alternate between "verbatim/intro/summary block" and (structured) football.txt block


```
▪ Round 15
Nov 22
  Antwerp           1-1 Dender
Nov 23
  Club Brugge       7-0 Sint-Truiden
  Standard          1-0 Cercle Brugge
  Genk              3-0 Charleroi
Nov 24
  Mechelen          3-0 Beerschot
  Leuven            1-1 Union
  Anderlecht        6-0 Gent
  Westerlo          4-0 Kortrijk

  §§

Halfway Table:

 1.KRC Genk                         15  11  1  3  31-19  34
 2.Club Brugge KV                   15   8  4  3  30-16  28  [C]
 3.R. Antwerp FC                    15   8  3  4  28-12  27
 4.RSC Anderlecht                   15   7  5  3  30-12  26
 5.KV Mechelen                      15   7  3  5  31-19  24
 6.KAA Gent                         15   6  4  5  23-18  22
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
 7.KVC Westerlo                     15   6  3  6  27-23  21
 8.R. Standard de Liège             15   6  3  6  10-18  21
 9.R. Union Saint-Gilloise          15   4  8  3  18-13  20
10.FCV Dender EH (Denderleeuw)      15   4  6  5  18-24  18  [P]
11.R. Charleroi SC                  15   5  2  8  14-19  17
12.K. Sint-Truiden VV               15   4  5  6  20-31  17
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
13.Oud-Heverlee Leuven              15   3  8  4  15-19  17
14.Cercle Brugge KSV                15   4  3  8  16-27  15
15.KV Kortrijk                       15   4  2  9  10-29  14
16.K. Beerschot VA                  15   1  4 10  12-34   7  [P]

  §§

▪ Round 16
Nov 29
  Kortrijk           3-1 Mechelen
Nov 30
  Club Brugge       4-1 Dender
  Charleroi         1-1 Standard
Dec 1
  Sint-Truiden      2-2 Genk
  Beerschot         3-2 Cercle Brugge
  Leuven            0-0 Anderlecht
  Union             2-1 Antwerp
  Westerlo          2-2 Gent
```



- [ ] remove duplicate final tables (leading & trailing) - keep leading?

```
Final Table:

 1.KRC Genk                         30  21  5  4  55-33  68       Playoff 1
 2.Club Brugge KV                   30  17  8  5  65-36  59  [C]  Playoff 1
 3.R. Union Saint-Gilloise          30  15 10  5  49-25  55       Playoff 1
 4.RSC Anderlecht                   30  15  6  9  50-27  51       Playoff 1
 5.R. Antwerp FC                    30  12 10  8  47-32  46       Playoff 1
 6.KAA Gent                         30  11 12  7  41-33  45       Playoff 1
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
 7.R. Standard de Liège             30  10  9 11  22-35  39       Playoff 2
 8.KV Mechelen                      30  10  8 12  45-40  38       Playoff 2
 9.KVC Westerlo                     30  10  7 13  50-49  37       Playoff 2
10.R. Charleroi SC                  30  10  7 13  36-36  37       Playoff 2
11.Oud-Heverlee Leuven              30   8 13  9  28-33  37       Playoff 2
12.FCV Dender EH (Denderleeuw)      30   8  8 14  33-51  32  [P]  Playoff 2
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
13.Cercle Brugge KSV                30   7 11 12  29-44  32       Relegation Playoff
14.K. Sint-Truiden VV               30   7 10 13  41-56  31       Relegation Playoff
15.KV Kortrijk                      30   7  5 18  28-55  26       Relegation Playoff
16.K. Beerschot VA                  30   3  9 18  26-60  18  [P]  Relegation Playoff


-or-

Final Table:

 1.R. Union Saint-Gilloise          10   9  1  0  22- 3  56  [28*]      Champions
 2.Club Brugge KV                   10   7  2  1  21- 6  53  [30*] [C]
 3.KRC Genk                         10   4  1  5  14-11  47  [34]
 4.RSC Anderlecht                   10   3  1  6  12-13  36  [26*]
 5.R. Antwerp FC                    10   2  3  5  10-18  32  [23]
 6.KAA Gent                         10   1  0  9   4-32  26  [23*]

NB: bonus points regular stage (halved, rounded upward) between square brackets
[*] gained an additional half point due to rounding; in case of a tie on points,
    ranked below a club which did not profit from rounding


-or-

Final Table:

13.K. Sint-Truiden VV                6   3  1  2   9-10  41  [31]
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
14.Cercle Brugge KSV                 6   2  1  3  10-13  39  [32]       Relegation Playoff
-----------------------------------------------------------
15.KV Kortrijk                       6   3  2  1  12- 8  37  [26]       Relegated
16.K. Beerschot VA                   6   2  0  4  10-10  24  [18]  [P]  Relegated

NB: points regular stage between square brackets


and so on
```



```
"unfold" document heading into stage/round!!! - why? why not?

=== Promotion Playoff         =>  ▪ Promotion Playoff

▪ Semifinals                  =>  ▪ Promotion Playoff, Semifinals
▪▪ First Legs                 =>  ▪ Promotion Playoff, Semifinals, First Legs
Apr 24
Lokeren-Temse     2-0 RWD Molenbeek
Patro Eisden      3-2 Beveren

▪▪ Second Legs
Apr 27
RWD Molenbeek     3-2 Lokeren-Temse
Beveren           1-2 Patro Eisden

▪ Final
▪▪ First Leg
May 3
Lokeren-Temse     1-2 Patro Eisden

▪▪ Second Leg
May 11
Patro Eisden      1-1 Lokeren-Temse

=>


▪ Promotion Playoff     (level 1)
  ▪▪ Semifinals         (level 2)
    ▪▪▪ First Legs      (level 3)
    ▪▪▪ Second Legs     (level 3)
  ▪▪ Final              (level 2)
   ▪▪▪ First Leg        (level 3)
   ▪▪▪ Second Leg       (level 3)
```
