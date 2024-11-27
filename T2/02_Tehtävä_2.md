**RAJAPINNAT T2: Esimerkkitehtävä, jossa on kaksi osaa**

Opittavat tiedot ja taidot: Englannin opiskelua, tiedonetsintää ja rajapinnan kokeilua


**T2.1** Suomenna oheinen englanninkielinen esimerkkitehtävä, itsellesi riittävällä tarkkuudella. Kerro pdf-dokumentissa vapaamuotoisesti mitä siinä tarkoitetaan eli mitä pitää tehdä?. 
[[ Pitää tehdä sovellus, joka seuraa Bitcoin hintaa tiettyjen aikojen välissä
ja näyttää ne jonkinlaisessa graafisessa UI:ssa. ]]

Englanninkielinen esimerkkitehtävä : Vincitpressassignment.md https://github.com/Gradia-Ohjelmistokehitys-k2022/rajapinnat-k2025/blob/main/T2/vincitpreassignment.md

T2.2 
a) Selvitä edellä suomentamasi tehtävän avulla alla olevan coingecko-rajapinnan bitcoin-haun from ja to -kenttien arvojen merkitys. 
[[ 
FROM ja TO kentät kertovat päivämäärät UNIX ajassa, ne pitää laittaa olemaan tästä päivästä kaksi viikkoa eteenpäin.
]]

b) Säädä alla olevan bitcoin-haun from ja to -arvot niin että ne viittaavat nyt tähän ja edeltävään kahteen viikkoon.
[[ FROM 1732752000(vastaa 27/11/2024), TO 1733961600(vastaa 11/12/2024). 
LASKIN SEN NÄIN:
54 years in total.
13 leap years from total.
41 years without leap(total - leap years)


13 x 366 = 4758(total days in leap years).
41 x 365 = 14965(total days in normal years).

leap years + normal years / 4758 + 14965 = 19723.

19723 total days from 1/1/2024 to 1/1/2024.

total days x seconds per day / 19723 x 86400 = 1704067200.

[[ TOTAL DAYS 2024 PER MONTH ]]
January - 31 days
February - 28 days in a common year and 29 days in leap years
March - 31 days
April - 30 days
May - 31 days
June - 30 days
July - 31 days
August - 31 days
September - 30 days
October - 31 days
November - 30 days
December - 31 days


total 366 days in 2024.
332 days already passed.
332 + 14 = 346(2 weeks from current time {11/27/2024} )

19723 total days(from 1/1/2024 to 1/1/2024)

total days + days passed this year / 19723 + 332 = 20055.
total days + 2 weeks / 19723 + 346 = 20069.

20055(current amount of days passed from 1/1/1970) x 86400(seconds per day) = 1732752000.
20069(2 weeks into the future) x 86400(s per day) = 1733961600.
]]

c) Miten käsittelet niihin liityviä arvoja c#:ssa?
[[ C# voi laskea UNIX ajan manuaalisesti tai sitten voit käyttää valmiita C# omia metodeja UNIX ajan laskentaan. ]]


Malli bitcoin-hausta: https://api.coingecko.com/api/v3/coins/bitcoin/market_chart/range?vs_currency=eur&from=1577836800&to=1677836800