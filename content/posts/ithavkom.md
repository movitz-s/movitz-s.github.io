+++
title = 'IT-HAVKOM'
date = 2024-02-12T08:00:00-07:00
draft = false
+++

## SHK kuriosa
Statens haverikommission [inrättades 1978](https://data.riksdagen.se/fil/6A606E4C-0CD8-4783-8415-65CD47BD7F36) och tog över ansvaret för undersökning av luftfartsolyckor från militären. Andra länder har motsvariga myndigheter och funktionen de fyller kravställs av [Chicagofördraget](https://en.wikipedia.org/wiki/Aviation_accidents_and_incidents) som alla FN-stater (förutom Lichtenstein) har ratificerat. *Transport Safety Boards* runt om i världen har oftast endast har i uppdrag att undersöka civila luftfarts- eller transportolyckor, vilket innebär att svenska SHK är bland de få instanser som har ett sådant omfattande ansvarsområde som sträcker sig utanför civil transport.  


Internationellt finns det ännu inte något som liknar ett Chigagofördrag för cyber generellt, istället existerar mer specifika förordningar som t.ex. [dataskyddsförordningen](https://eur-lex.europa.eu/legal-content/SV/TXT/HTML/?uri=CELEX:32016R0679#d1e4590-1-1) som kräver oberoende tillsynsmyndigheter. Dock har cyberkommissioner modellerade utifrån transporthaverikommissioner introduceras i vissa länder och i Sverige diskuteras förslaget om en IT-haverikommission.


## Cyber- eller upphandlingshaverikommission?

Två separata koncept har diskuterats, mig veterligen. I [Motion 2016/17:3080](https://www.riksdagen.se/sv/dokument-och-lagar/dokument/motion/etablera-en-haverikommission-for-offentliga_h4023080/) lyfts problematiken offentliga IT-projekt som går över budget men även ransomware och it-attacker.  

*(I motionen ovan refereras en Holländsk kommission som granskar offentliga IT-projekt. Jag hann inte identifiera vilken myndighet det är. Kontakta mig om du vet.)*

Projektledning/beställning och IT-attacker är, i min mening, väldigt skilda utredningsområden. Huruvida en eventuell kommission ska analysera t.ex. Stockholm stads Skolplattformen och/eller Kaseya-hacket är en stor distinktion. Senare diskussion samt internationella paralleller kommer att öka distinktionen och fokusera mer på cybersäkerhet. Trots separationen så överlappar såklart beställarkompetens och säkerhet, t.ex. har attacker skett p.g.a dåliga upphandlingar som förhindrar patching (Karolinska).  

En haverikommissions mål bör vara att öka säkerheten, inte att bespara staten pengar. Jag kommer att använda benämningen IT-HAVKOM för att vara konsekvent, men syftar specifikt endast på utredningen av "cyberincidenter".

Jag vill inte lägga mig i utredning av IT-projekt som blir dyra eller misslyckas. Jag misstänker att typ [DIGG/ESV](https://www.digg.se/download/18.79c61f7c17db5871992f0b2/1647952779700/myndigheters-strategiska-itprojekt-itkostnader-och-mognad.pdf) bör ta det uppdraget. 

## Historik av policyförslaget

Här finns de diskussioner som jag har hittat om en IT/Cyber-haverikommission. Bidrag välkomnas.

Över tid har olika former av en "IT-haverikommission" eller "Haverikommission för cyberincidenter" diskuterats. Central policyentrepenör *verkar vara* Patrik Fältström med stöd från Ann-Marie Löwinder samt Centerpartiet. 

Löwinder behandlar förslaget i [IIS remisssvar](https://internetstiftelsen.se/docs/Remissvar-NISU-IIS-slutlig.pdf) 2015.

Rickard Nordin (C) föreslog en IT-haverikommission 2016 och 2018 (identiska motioner). Förslagen hade mest fokus på offentliga IT-investeringar, d.v.s. inte så mycket cyber. Båda motioner fick avslag av finansutskottet, delvis då man ansåg att ESV hade fått liknande uppdrag. Skulle man ramat in det som en strikt cyberfråga och tilldelat motionen till försvarsutskottet kanske svaret hade varit annorlunda.


Frågan har sedan tagits upp 2022 i IVA:s rapport, [*Cybersäkerhet för ökad konkurrenskraft*](https://www.iva.se/contentassets/ec4545faa53541f2b8d29b150ae39645/202210-iva-cybersakerhet-rapport.pdf) som bl.a. Fältström har delförfattat, och då har man slutat fokusera på IT-kostnader. Efter detta ställdes en [skriftlig fråga](https://www.riksdagen.se/sv/dokument-och-lagar/dokument/svar-pa-skriftlig-fraga/haverikommission-for-cyberincidenter_ha12922/) 2023 från Adrian Magnusson (S) till Carl-Oskar Bolin om förslaget och ministern menade att det var "ett av många intressanta förslag".

Nu får vi invänta den framtida cybersäkerhetsstrategi som Bolin utlovade.

<!-- https://www.paftech.se/notes/1873/ håller inte med, lösning som söker problem -->

## Internationella motsvarigheter

#### Cyber Safety Review Board

CSRB är en ny kommité i USA som etablerades 2021. De har $3,2 miljoner dollar i budget och leds av tunga ledamöter som representerar både privata och offentliga sektorn.  

De har hittills skrivit en rapport om året:
- [Log4J](https://www.cisa.gov/sites/default/files/2023-02/CSRB-Report-on-Log4j-PublicReport-July-11-2022-508-Compliant.pdf) (2022)
    - Slutsatserna behandlade bland annat SBOM-implementering
    - Kommunicerade med många parter, inkl. kinesiska myndigheter [(Blackhat, 8:47)](https://www.youtube.com/watch?v=a2hU6LEpws8)
- [Lapsus$](https://www.cisa.gov/sites/default/files/2023-08/CSRB_Lapsus%24_508c.pdf) (2023)
  - Rapporten behandlar en enskild hotaktör, deras TTPs och rekommendationer för att bemöta dem
- [Cloud Security](https://www.dhs.gov/news/2023/08/11/department-homeland-securitys-cyber-safety-review-board-conduct-review-cloud) (2024?)

De har välkomnats i policysammanhang och jag har inte hört någon kritik mot CSRB. Rapporterna reflekterar inte att kommitten är modellerad efter NTSB.

#### Cyber Incident Review Board

CIRB i Australien är starkt inspirerat av amerikanska CSRB och är i skrivande stund på remiss.

[Remissfrågorna](https://www.homeaffairs.gov.au/cyber-security-subsite/files/cyber-security-strategy-2023-30-consultation-paper.pdf) som ställs kring CIRB är bra att fundera på i svensk kontext.

#### Onderzoeksraad voor Veiligheid (Dutch Safety Board)

Den [nederländska haverikommissionen (OVV)](https://onderzoeksraad.nl/en/thema/digital-safety/) liknar till stor del den svenska i dess bredd, men har även möjlighet att undersöka digitala incidenter. 

OVV har producerat två eller fyra rapporter om digital säkerhet, beroende på hur man räknar:
- [DigiNotar-incidenten](https://onderzoeksraad.nl/en/onderzoek/the-diginotar-incident/)
  - Utreddes i 6 månader under 2011/2012
- [Who is in control? Road safety and automation in road traffic](https://onderzoeksraad.nl/en/onderzoek/who-is-in-control-road-safety-and-automation-in-road-traffic/)
  - Trots att det faller under både trafik- och digital säkerhet, så är det inte riktigt "IT-säk"
  - Utreddes från 2017 till 2019
- [Patient safety during IT outages in hospitals](https://onderzoeksraad.nl/en/onderzoek/patient-safety-during-it-outages-in-hospitals/)
  - Även detta inte "cyber"
  - Utreddes från 2018 till 2020
- [Vulnerable through software - Lessons resulting from security breaches relating to Citrix software](https://onderzoeksraad.nl/en/onderzoek/vulnerable-through-software-lessons-resulting-from-security/)
  - Väldigt specifik 
  - Utreddes från 07-2020 till 12-2021 


Efter DigiNotar-incidenten efterfrågade inrikesministeriet bland andra att haverikommissionen skulle undersöka saken. Det var allvarligt för staten delvis för att PKIoverheid, den statliga PKI-lösningen i Nederländerna, drevs av DigiNotar. Dock behandlar inte rapporten någon teknisk detalj, utan det verkar som att motsvarigheten till PTS utredde den tekniska aspekten.

Då jag skummade en maskinöversatt version av rapporten så kan jag inte garantera en korrekt tolkning av situationen.

#### Onnettomuustutkintakeskus (Safety Investigation Authority, Finland)

Finska SIAF har också väldigt brett mandat att undersöka olika områden. De har bland annat gjort rapporter om skolskjutningar, Covid-19 och sjukvårdsfrågor utöver det som svenska SHK utreder. Enligt [IVA:s rapport](https://www.iva.se/contentassets/ec4545faa53541f2b8d29b150ae39645/202210-iva-cybersakerhet-rapport.pdf) ska de få utreda cyberincidenter, men det är inget de verkar skylta med eller hunnit genomföra ännu. Myndigheten får själva välja vilka incidenter i de övriga kategorierna de vill undersöka, då internationell lagstiftning inte finns. Cyber nämns inte specifikt.

## Jämförelse med SHK

| | SHK | IT-HAVKOM |
| - | - | - |
| Teknik |  Fåtal modeller av flyg, mest Airbus och Boeing <br><br> Tåg/fartyg ganska generiska, en expert på tåg kan utreda många liknande incidenter | Vitt skilda tech stacks <br><br>AD-miljöer, SaaS-tjänster i molnet, serverhallar, telekom, fibernät, SCADA, COBOL-banker, kryptografi + ändlösa system |
| Aktörer | Förutsägbara. <br><br>Fåtal aktörer, i stor mån svenska myndigheter och stora bolag + samarbetsstruktur med EU | Många olika IT-bolag, komplicerad leveransstruktur och beroenden. Ingen reglerande myndighet på samma sätt. |
| Rekommendation till implementation | Fåtalet aktörer innebär att alla involverade direkt adresseras | Många rekommendationer finns redan som inte implementeras i bolag p.g.a kompetens-/resursbrist |
| Incidenter | Mestadels olyckor | Olyckor + attacker från antagonistiska stater och kriminella |
| Behov av transparens | Medborgare känner sig utsatta i transportsituationer och vill känna trygghet<br>Flygbolag tjänar på tillit och har stort finansiellt incitament att vara säkra | Många fler bolag i ekosystemet, mindre finansiellt incitament att reda ut haverier |

I denna jämförelse kommer jag fram till att en IT-HAVKOM lär ha svårt att arbeta med så många incidenter som SHK gör. De bör vara selektiva i val av utredningar så att rekommendationerna är så allmännyttiga som möjligt. Man bör alltså arbeta "strategisk/operativ" nivå i jämförelse med den detaljerade tekniska nivån som SHK undersöker.


Det publika intresset och allvaret i incidenter korresponderar inte med hur allmännyttiga de tekniska lärdomarna är. T.ex. är det fullt möjligt att *senaste stora incidenten* var ett resultat av stulna lösenord. Därför är t.ex. CSRB analys av flera incidenter från samma hotaktör eller av samma typ värdefullare än en enskild teknisk genomgång av incidenterna. 


## Slutsats 

Jag har inte hittat exempel av någon stat som har implementerat en IT-HAVKOM som utreder cyberincidenter i samma utsträckning som transportincidenter. Trots att Nederländerna har möjligheten har de bara skapat två rapporter om cyber. Jag gissar ärligt att det inte finns kapacitet i Sverige för att utreda cyberincidenter i högre volym idag, speciellt när flera andra cyberfunktioner samtidigt håller på att startas och tar form. Det verkar som att konceptet har runnit ut i sanden hos OVV och eventuellt i uppstart hos SIAF. Om kommissionen själva får välja vilka cyberincidenter som utreds, t.ex. till skillnad från samtliga flygincidenter, så är risken att efterfrågan inte känns av och att interna viljan och kompetensen försvinner.

Att eftersträva skulle vara den amerikanska CSRB-modellen. Med det menar jag att man ska utreda cybersäkerheten på operativ nivå i Sverige, med representation och stor input från samtliga aktörer, vilket borde resultera i cirka en rapport med råd och policyrekommendationer om året, inte 20 st vilket SHK rapporterade 2023.  

Som exempel skulle en sådan kommission kunna undersöka T\*\*\*oevry-haveriet, men inte ur ett tekniskt perspektiv. Mer intressant från allmänhetens perspektiv är hur man eliminerar SPOF:ar i IT-drift och att hantera risker i leverantörskedjor. Detta skulle inte vara enskilt relevant för T\*\*\*oevry och lösningen kräver förändring bland leverantörer, köpare, tekniken och policy.
