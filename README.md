# DEVOIRS

Andie SAMADOULOUGOU
300 209 487 

CSI 2532 Devoir 2 

Hiver 2021 

**Q1: Normalisation**

Considérons une relation avec le schéma R(A, B, C, D) et l'ensemble F des dépendances
fonctionnelles: 

F = {
 AB → C,
 C → D,
 D → A
}


***a)***
AB
**b)**

(D → A) D n'est pas une super cle 

R1(D,A) U R2 (A,B,C)


**c)**

**Q2: Dépendances fonctionnelles**



**a.dépendances fonctionnelles**
```
F = {
NIN contractNo -> heuresPerWeeks
NIN -> eName
hotelNo-> hotelLocaction
contractNo -> hotelNo
}
```
**b.clés candidates**
```
NINcontractNo
```
**c.troisième forme normale (3NF)**

R(hotelNo,hotellocation) U R(NIN,contractNo,heuresPerWeeks,hotelNo,eName)


**Q3: Langues pures**

```
c. {t | ∃ r ∈ sailors ∧ r[rating] < 3}
d. {<bid> | ∃ bid,day,sid ∈ reserves ^ day = '2019-04-28')}
e. {<bcolor> | ∃ sid, bid, day (
 <sid, bid, day> ∈ reserves (
 ∧ ∃ sid,sname (
 <sid,sname> ∈ sailors ∧ sname=“lubber”))}
```


**Q4: RAID**


1-B
2-D
3-A
4-E
5-C


**Q5 - B+Tree**



**Q6**

a) 
|  | RO | R1 |R2|R3|
| :------------ |:---------------:| :-----:|-----:|-----:|
| OPEL    | 1 | 1|0|0|
| Peugeot      | 0        |  0 |1|0|
| BMW | 0|    0 |0|1|

|  | RO | R1 |R2|R3|
| :------------ |:---------------:| :-----:|-----:|-----:|
| GREY   | 1 | 0|0|0|
| RED      | 0        |  1 |0|0|
| BLACK | 0|    0 |1|1|


**Q7-hachage**

a): 2, 0, 2, 0, 1, 0, 0,0 , 0, 0
n) Non il ne s'agit pas d'une bonne fonction de hachage car olusieurs valeurs differents ont le meme index de hachage

