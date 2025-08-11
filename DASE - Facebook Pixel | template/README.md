# DASE – Facebook Pixel | Template

[![Download JSON](https://img.shields.io/badge/Download-Container.json-blue)](link-na-json)
[![Meta Pixel Compatible](https://img.shields.io/badge/Meta%20Pixel-Compatible-brightgreen)](https://www.facebook.com/business/help/952192354843755)
[![Version](https://img.shields.io/badge/Version-1.0.0-orange)]()


## Obsah
- [Prehľad](#prehľad)
- [Import do Google Tag Managera](#import-do-google-tag-managera)
- [Nastavenie a použitie](#nastavenie-a-použitie)
- [Changelog](#changelog)
- [Kontakt a odkazy](#kontakt-a-odkazy)


## Prehľad  
Táto šablóna slúži na základné meranie marketingových udalostí pre **Meta** pomocou **Facebook Pixel**.  
Vychádza z **Google Analytics Ecommerce Measurements** a predpokladá implementáciu štandardného e-commerce `dataLayer` podľa Google špecifikácie.  

Obsahuje:  
- tag na odosielanie **page view** udalostí  
- konverzný **Purchase** tag  

<br>
<img src="images/facebook_pixel_tags.png" alt="Facebook Pixel tags" width="60%">
<br>


## Import do Google Tag Managera  
1. V kontajneri prejdite do sekcie **Správca**.  
2. Kliknite na **Importovať kontajner**.  
3. Vyberte súbor stiahnutý z GitHub repozitára.  
4. Odporúčame vytvoriť si nový pracovný priestor:  
   - kliknite na **Vybrať pracovný priestor**  
   - vpravo hore kliknite na **+**  
5. V sekcii **Vyberte možnosť importu**:  
   - ak používate našu **DASE – GA4 – E-commerce** šablónu, vyberte možnosť **Zlúčiť** a následne **Prepísať vzájomne nezlúčiteľné štítky, spúšťače a premenné**  
   - potom otvorte priečinok **PLACEHOLDERS**, otvorte každý tag v priečinku a kliknite na **Zrušiť zmeny** – tým vrátite prepísané položky z E-commerce šablóny do pôvodného stavu vo vašom kontajneri  

<br>
<img src="images/fb_pixel_placeholders.png" alt="FB Pixel placeholders" width="60%">
<br>


## Nastavenie a použitie  
- V premennej **`FB - Pixel ID`** nahraďte hodnotu **`123456789`** vašim Pixel ID.  

<br>
<img src="images/fb_pixel_id.png" alt="FB Pixel ID" width="60%">
<br>


## Changelog  
- **1.0.0** – Prvé vydanie šablóny


## Kontakt a odkazy  
Máte nejaké otázky alebo nejasnosti? Napíšte nám na **cibula@dase.sk**  

👉 [Dase Blog](https://www.dase-analytics.com/blog/sk/)  
👉 [Dase Instagram](https://www.instagram.com/daseanalytics/)
