Voor mijn afstudeeronderzoek van de [Master Data Driven Business](https://www.hu.nl/voltijd-opleidingen/master-data-driven-business) Heb ik bij het e-learning bedrijf GoodHabitz de onboarding onderzocht. Voor dit onderzoek is onboarding gedefinieerd als: methoden en middelen om nieuwe en al bestaande gebruikers op weg te helpen en ze de waarde van het platform te laten zien bij zowel een eerste kennismaking met het platform als er nieuwe functies worden geïntroduceerd. Hieronder lees je over de resultaten van het onderzoek en in deze [github repository](https://github.com/olivierverwoerd/A-B_test_tool_with_APA) kan je de code vinden om zelf de onboarding te kunnen onderzoeken in een e-learning context, al kan de tool ook worden gebruikt voor algemeen testen. <br>

# Inleiding
GoodHabitz is een bedrijf dat leercontent verkoopt aan bedrijven om de medewerkers van deze bedrijven te professionaliseren. Het algemene doel van GoodHabitz is om mensen in staat te stellen om op een flexibele en leuke manier te leren op een tijdstip en locatie die voor hen werkt. GoodHabitz wil dat de gebruikers, oftewel de werknemers van klanten, zo veel mogelijk gebruik maken van het platform. Door ‘onboardingssucces’ te verhogen, vergroot GoodHabitz de kans op een groter gebruik en betere klantretentie. Nu is het probleem dat de onboardingsfactoren niet bekend zijn voor e-learning. Hierover is binnen de discipline van e-learning niet eerder onderzoek uitgevoerd. Dit onderzoek brengt daar verandering in!

# A/B test tool
Er is onderzocht welke factoren positief van invloed zijn op de onboarding bij e-learning. Het is te tijdrovend en niet goed voor het onderzoek om deze per factor te A/B-testen, daarom is er een A/B test tool ontwikkeld die meerdere varianten tegelijk kan testen en data kan leveren over significantie ten opzichte van een controlegroep. Nu bestaan er wel online A/B-tests, maar deze zijn incompleet in de resultaten of kunnen niet meerdere varianten tegelijk testen.
Aan de hand van het doorlopen proces in dit onderzoek is een stappenplan voor onboardingsoptimalisatie opgesteld en een tool gemaakt om deze stappen uit te voeren. **Deze tool helpt bedrijven om A/B-testen op te stellen en de tool verwerkt de gegevens direct in APA-notatie. Deze tool geeft ook aan wat het effect van bepaalde variaties is en geeft advies over welke elementen je moet behouden, verwijderen of welke elementen (niet veel) invloed hebben.**
De inzichten en de dataverwerking uit de tool konden direct worden toegepast op het onderzoek bij GoodHabitz en kunnen in de toekomst ook door andere e-learning bedrijven gebruikt worden. Zo kunnen e-learning bedrijven zelfstandig hun producten te optimaliseren middels A/B-testen door de adviezen over elementen die blijken te werken te implementeren en de adviezen over elementen die geen of een negatief effect hebben te elimineren. Het innovatieve aan deze tool is dat deze zowel meerdere testen tegelijkertijd kan uitvoeren, als data leveren over de significantie ten opzichte van een controlegroep. Daarbij worden alle data geleverd om de resultaten meteen te kunnen noteren in APA-notatie zodat deze gebruikt kunnen worden in wetenschappelijk onderzoek.

## Voorbeeld output van de A/B test tool
(Data is van gegenereed en niet hetzelfde als het onderzoek.)
![image](https://github.com/olivierverwoerd/A-B_test_tool_with_APA/assets/22635990/ae750973-91cf-44a1-a3bd-4366967df266)
![image](https://github.com/olivierverwoerd/A-B_test_tool_with_APA/assets/22635990/c7cde3ec-4ebe-47af-936b-6f50b7084744)

# Onderzoek in het kort
Uit een literatuurstudie bleek dat **drie onboardingsfactoren de grootste kans hadden om van invloed te zijn op het onboardingssucces**: een relevante persoonlijke onboardingservaring met personalisatieopties, het geven van sociaal bewijs en gebruiksaanwijzingen.
Met ‘gebruiksaanwijzingen’ wordt bedoeld: een korte interactieve uitleg als onboarding over hoe het platform gebruikt kan worden. ‘Sociaal bewijs’ heb ik gedefinieerd als: gegevens die laten zien dat andere gebruikers ook van het platform gebruikmaken en die de gebruiker kunnen overtuigen om tijd op het platform door te brengen om zo het gebruik te stimuleren. Met ‘personalisatie’ worden de keuzes bedoeld die de gebruiker kan invullen om zo een persoonlijke onboardingservaring te krijgen. Het ‘onboardingssucces’ is het percentage gebruikers dat na de onboarding binnen een dag een activiteit doet op het platform.

# De hoofdvraag
Daarom luidt de hoofdvraag van mijn onderzoek:
_"Hoe groot zijn de effecten van de onboardingsfactoren gebruiksaanwijzingen, sociaal bewijs en personalisatie op het onboardingssucces van het e-learning platform GoodHabitz om zo gebruikers een activiteit te laten doen binnen één dag na de onboarding?"_

Om dit te kunnen onderzoeken zijn er drie onboardingsvarianten gemaakt die elk een andere onboardingsfactor hebben. Ook was er een controlegroep. Er is gekeken hoeveel gebruikers er na de onboarding een activiteit hebben gedaan en wat het percentage hiervan was. Ter controle van of de factoren van de onboarding helpen bij het oorspronkelijke probleem van GoodHabitz om gebruikers meer gebruik te laten maken van het platform, is er ook gekeken naar hoeveel activiteiten een gebruiker heeft gedaan na de onboarding en wat de retentie was na een week. Door gebruik te maken van een _z_-toets en een _t_-toets kon er berekend worden of de verschillende onboardingsvarianten statistisch significant verschillen en niet op toeval berusten. Hieronder is dit samengevat:

## Conceptueel model
![image](https://github.com/olivierverwoerd/A-B_test_tool_with_APA/assets/22635990/dc963d30-071a-4478-8349-c8fe0e0f75fc)

# Resultaten
Uit het onderzoek is gebleken dat:
- Gebruiksaanwijzingen (_n_=309) niet significant verschilt met de controlegroep (_z_ = -0.33, _p_ = .371)
- Sociaal bewijs (_n_=400) niet significant met verschilt met de controlegroep (_z_ = -0.08, _p_ = .469)
- Personalisatie (_n_=336) 35.67% beter presteert dan de controlegroep (_z_ = 1.99, _p_ = .023)
  
Een onboarding op basis van de onboardingsfactor gebruiksaanwijzingen of sociaal bewijs heeft geen significant effect op het onboardingssucces van het e-learning platform GoodHabitz. Daarentegen heeft een onboarding op basis van de onboardingsfactor personalisatie een significant positief effect op het onboardingssucces. Het gebruik van personalisatie in het onboardingsproces kan dus bijdragen aan het onboardingssucces.  
Opvallend is ook dat bij het kijken naar het aantal activiteiten dat een gebruiker heeft verricht na zijn onboarding, de factoren gebruiksaanwijzingen _t_(696) = 1.326, _p_ = .010 en personalisatie _t_(723) = 0.775, _p_ = .026 een positief effect hebben op het aantal activiteiten van de gebruiker ten opzichte van de controlegroep. De onboarding op basis van sociaal bewijs had geen significant effect op het aantal activiteiten van de gebruiker _p_ = .393. Het gebruik van personalisatie en gebruiksaanwijzingen in het onboardingsproces kunnen dus bijdragen aan het gebruik van het platform.<br>
Hieruit zijn de nieuwe inzichten voor e-learning dat **een onboarding op basis van personalisatie het meest effectief is** en dat **een onboarding op basis van gebruiksaanwijzingen en personalisatie een positief effect heeft op het gebruik**. Ook is nu bekend dat een onboarding op basis van sociaal bewijs wel werkt voor e-commerce, maar niet in de context van e-learning.

Al met al zijn er dus waardevolle nieuwe inzichten verkregen en is de tool die ik heb ontwikkeld bruikbaar voor ieder bedrijf dat werkt met data en op basis hiervan haar producten wil verbeteren.
Nieuwsgierig naar de tool? [Deze kan je hier vinden!]((https://github.com/olivierverwoerd/A-B_test_tool_with_APA))
