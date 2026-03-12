# Oppimispäiväkirja: Git projektissa

**Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?**

Jos projektissa meneekin jotain pieleen niin on helppo palata edelliseen toimivaan versioon. Versionhallinnan historiaa tutkimalla voi myös lähteä selvittämään mistä bugi on mahdollisesti aiheutunut. Koodi pysyy varmuuskopioituna Git-hosting palveluissa ja sitä on helppo sieltä tarvittaessa esitellä tai jakaa muille.

**Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?**

Versionhallinta ylipäätänsä mahdollistaa projektin työstämisen useamman kehittäjän voimin. Jokainen voi tehdä omia juttujaan piittaamatta muista. Historia paljastaa kuka on tehnyt minkäkin muutoksen. Se helpottaa projektin pysymistä kasassa, koska muutokset yhdistetään hallitusti samaan branchiin.

**Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.**

Main-branchissa oleva koodi on tuotannossa ja sen on syytä olla aina vapaa kriittisistä bugeista. Dev-branchissa on vaiheessa oleva koodi. Featuret toteutetaan asiaankuuluvasti nimetyissä feature-brancheissa. Nämä feature-branchit yhdistetään dev-branchiin pull requestin kautta, ei rikkinäistä koodia dev-branchiin. Jokaiseen pull requestiin pyydetään yksi toinen tiiminjäsen tarkistamaan ja hyväksymään pull request. Mergetyt branchit poistetaan kuleksimasta remote reposta. Kun dev-branchissa on tarpeeksi uusia hyödyllisiä muutoksia ja se toimii vakaasti, se yhdistetään pull requestilla main-branchiin yhteisymmärryksessä.

**Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?**

Siististi toteutettu kurssi. Ihan alussa harjoituksessa kaksi minulle oli hieman epäselvää milloin piti committaa ja milloin vain addata, koska ohjeissa käytetään sekaisin sanoja _talleta_ ja _vie_.

Luulen, että harjoituksessa kuusi olin liian nopea noille GitHub actions scripteille, koska virtuaalinen tiimikaveri käyttäytyi hieman oudosti ja eri tavalla kuin ohjeista ymmärsin. Mukava tehtävä silti.

Ehdottoman hyödyllinen kurssi mikäli meinaa mitään ohjelmistokehitystä tehdä ja työmäärä oli sopiva opintopisteisiinsä nähden. Tähän laajuuteen ei mahdu, mutta mieluusti olisin hieman nähnyt sisältöä esim. rebasesta.
