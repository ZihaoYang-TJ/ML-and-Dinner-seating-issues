# ML-and-Dinner-seating-issues
This program utilizes machine learning to solve the problem of seating arrangements during meals. Up to 12 people are supported, with a reasonable ranking from guest of honor, main companion to sixth companion and flexible mobility positions.
In this program, you need to input the csv document including name, Politburo ranking, civil servant level, age, occupation, gender, professional title, net worth, home town and other information see Example:
```
zhangsan ,4, 正国级, 64 ,civil servant, 1 ,high, NAN,shanghai

lisi ,NAN ,NAN , 48 , doctor, 1,mid,45.wuxi

xiaoli,NAN,NAN,32,teacher,0,mid,14, shengjing
```
\\
the name is the primary key of you document, the gender we use 1(male) 0(female). this code acepte NAN.
using this code we obtain the ranking of this dinner.  zhangsan lisi .  Then the code will print xiaoli has no right to attend this dinner.
