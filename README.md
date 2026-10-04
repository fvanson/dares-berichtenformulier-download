# DARES Berichtenformulier – downloads

App voor het invullen, bewaren en afdrukken van het **DARES Berichtenformulier**, gebaseerd op het papieren
formulier (V2.5) en het digitale formulier voor Winlink (V1.3.1). De app werkt **volledig offline**: berichten
blijven op je eigen apparaat.

> **Alpha-versie (V0.02 Alpha).** Dit is een testversie om de app te bekijken en uit te proberen. Er kunnen
> nog fouten in zitten en onderdelen kunnen nog veranderen. Gebruik deze versie (nog) niet als enige middel bij een
> echte inzet.
>
> Deze app is een initiatief van PD2FT (DARES R20) en is (nog) geen officiële uitgave van DARES.

## Downloaden

Ga naar **[Releases](https://github.com/fvanson/dares-berichtenformulier-download/releases)** en download bij de nieuwste versie het bestand voor jouw apparaat:

| Apparaat | Bestand |
|---|---|
| Windows 10/11 (laptop/pc) | `Berichtenformulier-V0.02-Alpha-Windows.zip` |
| Android 7.0 of nieuwer (telefoon/tablet) | `Berichtenformulier-V0.02-Alpha-Android.apk` |

## Installeren op Windows

1. Pak het zip-bestand uit, bijvoorbeeld naar je map Documenten (rechtsklik → *Alles uitpakken*).
2. Open de map `Berichtenformulier` en start `berichtenformulier.exe`.
3. Windows kan waarschuwen met *"Windows heeft uw pc beveiligd"*, omdat de app nog niet digitaal ondertekend is.
   Klik op **Meer informatie** en dan op **Toch uitvoeren**.

Installeren is niet nodig en er zijn geen beheerdersrechten nodig. Verwijderen = de map weggooien.

Melding over `MSVCP140.dll` of `VCRUNTIME140.dll` bij het starten? Dan heb je een oude zip van V0.01 Alpha:
download de nieuwste versie.

## Installeren op Android

1. Open de link naar het `.apk`-bestand op je telefoon en download het.
2. Tik op het gedownloade bestand. Android vraagt of je apps uit deze bron wilt toestaan
   (*Onbekende apps installeren*): sta dit toe voor je browser of bestandsbeheerder.
3. Google Play Protect kan waarschuwen dat de app onbekend is. Kies **Details** → **Toch installeren**.

De app heet op je telefoon **Berichtenformulier**.

## Bijwerken naar een nieuwe versie

Je berichten en instellingen blijven bewaard bij het bijwerken.

- **Windows:** pak de nieuwe zip uit en gebruik de nieuwe map `Berichtenformulier` (de oude map mag weg). De berichten
  staan niet in die map maar in je gebruikersprofiel (`%APPDATA%\me.vanson\DARES Berichtenformulier`).
- **Android:** installeer de nieuwe APK gewoon over de oude heen; **niet** eerst verwijderen, want dan ben je je
  berichten kwijt.

Maak voor de zekerheid vóór het bijwerken een **CSV-export** als back-up.

## Eerste start

De app vraagt eerst om je **roepnaam** (callsign). Die staat bovenaan het formulier bij *Dit station* en wordt
standaard ingevuld bij *Origineel station* en *Door (By)*. Je kunt hem later wijzigen via **Instellingen**
(tandwiel rechtsboven).

## Wat kan V0.02 Alpha

- Berichtenformulier invullen zoals op papier: grijze velden voor DARES, witte velden voor de opdrachtgever.
- Bericht van maximaal 25 woorden (maximaal 35 tekens per woord) in een 5×5-raster, met automatische woordtelling.
- **Check**: wordt automatisch geteld; bij een ontvangen bericht vul je de opgegeven Check in en ziet je direct of
  die klopt met het aantal woorden. Een verschil wordt genoteerd als bijvoorbeeld *13/12*.
- Nummering per post, waarschuwing bij een dubbel nummer.
- *Ontvangen van* en *Doorgegeven aan*.
- Berichten bewaren, terugzoeken en bewerken.
- **Afdrukken** en **opslaan als PDF** (A4 liggend, in de opmaak van het papieren formulier).
- **CSV-export** (per periode) en **CSV-import**, bijvoorbeeld als back-up of om in Excel te bekijken.

Nog **niet** in deze versie: versturen via Winlink, versies voor iPhone/iPad, Mac en Linux.

## Je gegevens

Alles blijft op je eigen apparaat; de app stuurt niets via internet. Maak tijdens het testen af en toe een
**CSV-export** als back-up: bij een latere testversie kan het nodig zijn de app opnieuw te installeren.

## Waar letten we op bij het testen?

- Is het formulier duidelijk en snel in te vullen, ook onder tijdsdruk?
- Klopt de woordtelling met hoe je op papier telt?
- Ziet de afdruk / PDF er goed uit?
- Werken CSV-export en -import (ook in Excel)?
- Past het formulier op je scherm (laptop, telefoon, tablet)?

## Feedback

Graag! Mail naar **frank@vanson.me** en vermeld:

- de versie (staat bovenaan het formulier, bijvoorbeeld *V0.02 Alpha*);
- je apparaat en Windows- of Android-versie;
- wat je deed, wat je verwachtte en wat er gebeurde;
- een schermafbeelding als dat helpt.
