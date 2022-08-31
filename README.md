# Data stories

## Divorces and divortiality since 1876
https://www.bfs.admin.ch/bfs/en/home/statistics/population/marriages-partnerships-divorces/divortiality.assetdetail.18584917.html
* year
* male/female
* swiss/foreign
* **with/without children**
* marriage duration - bucket
* **marriage duration - avg**
* **cause (legal article)**
* **agreement type**

## Divorces by canton, duration of marriage and age class of both of the divorcing partners
https://www.bfs.admin.ch/bfs/en/home/statistics/population/marriages-partnerships-divorces/divortiality.assetdetail.22724377.html
* year
* **canton**
* marriage duration - bucket
* age husband - bucket
* age wife - bucket

## Divorces by duration of the marriage, citizenship (selection) at divorce and age class of both of the divorcing partners
https://www.bfs.admin.ch/bfs/en/home/statistics/population/marriages-partnerships-divorces/divortiality.assetdetail.22724419.html
* year
* marriage duration - bucket
* age husband - bucket
* age wife - bucket
* **citizenship husband**
* **citizenship wife**

## Divorces by institutional units, duration of marriage and citizenship (category) of both of the divorcing partners at divorce
https://www.bfs.admin.ch/bfs/en/home/statistics/population/marriages-partnerships-divorces/divortiality.assetdetail.22724375.html
* year
* commune
* marriage duration - bucket
* swiss/foreign wife
* swiss/foreign husband


## Questions:
* Where are least ppl divorcing?
    - married count per gde/canton
    - divorced count per gde/canton
* When are ppl divorcing?
    - divorces per age group (husband/wife)
    - divorces per marriage duration
* Who is divorcing most?
    - divorces per citizenship
    - with/without children?
* What are the reasons of divorce?
    - divorces per cause
* What are agreements following divorce?
    - divorces per agreement type

What is probabaility of:
    - divorcing
    - being divorced

What is probability of divorcing given:
    - gemeinde
    - nationality husband
    - nationality wife
    - age husband
    - age wife
    - children

How does this probability change with changes in:
    - age husband
    - age wife
    - children


Constraints:
- sum([p_divorcing(x) for x in years]) = p(divorced)
- sum([p_divorcing(c, year) for c in constraints]) = p_divorcing(year)


TODO:
* get number of ppl per gde from lindas/swisstopo in 2020
