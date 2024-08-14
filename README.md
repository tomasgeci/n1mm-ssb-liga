[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://supportukrainenow.org/)

# n1mm-ssb-liga
SSB liga konfig pre N1MM contest logger 

## navod na instalaciu

- stiahnut subor **"SSBLIGA.UDC"**
- tento subor ulozit do priecinka, kde sa nachadzaju uzivatelske nastavenia N1MM loggera, konkretne do priecinka **"UserDefinedContests"**, zvycajne niekde v adresari `C:\users\vase_uzivatelske_meno\n1mm`, pripade v adresari `Dokumenty\n1mm`
- stiahnut subor **"SSBLIGA.sec"**
- tento subor ulozit do priecinka, kde sa nachadzaju uzivatelske nastavenia N1MM loggera, konkretne do priecinka **"SupportFiles"**

## navod na vytvorenie kontestoveho logu pre SSB ligu

- po predchadzajucich operaciach treba N1MM logger zavriet
- po opatovnom otvoreni N1MM loggera zvolte **"New log in database xxx"**
- nasledne vyberte z "Log Type" polozku **"SSBLIGA"**
- nastavte si parametre podla potreby, hlavne "Send Exchange" a parametre operatora
- kliknite na **"Import section list"** - malo by sa ozvat hlasenie o uspesnom importe z SSBLIGA.sec - to su okresne znaky OK a OM
```diff
- Prosim nezabudnite kliknut na "Import section list", inak vam nebude fungovat kontrola okresnych znakov
```
V tejto chvili je vas log pripraveny na SSB ligu - s kontrolou spravne vyplnenych okresnych znakov OK a OM

V pripade otazok mi nevahajte napisat na om5ast(at)omradio.sk

### Ak sa nekamaratite s GitHub alebo s GIT zalezitostami, nevahajte pouzit zelene tlacidlo vpravo hore "Code" a ako volbu pouzite "Download ZIP". Vsetky subory budete mat v ZIP archive a postaci ich rozbalit  beznym sposobom.

Ako inspiracia posluzili konfigy od OK1NE a OK1PCB, za co im touto cestou dakujem.

73 ES GL
