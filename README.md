# Speakybara

**Sleep een kader over iets op je scherm. Speakybara leest het hardop voor.**

Het werkt op alles wat je ziet: een pdf, een plaatje, een foto van een brief,
een spelletje, een menu, tekst die je niet kunt selecteren. Je hoeft niets te
kopiëren en niets over te typen.

> Dit is een **testversie**, voor Windows en nu ook voor de Mac. Hij is nog
> niet af, en feedback is precies waarvoor hij hier staat:
> [vertel hoe het ging](https://speakybara-website.vercel.app/nl/feedback).

## Downloaden

👉 **[Download de laatste versie](../../releases/latest)** en klik onder **Assets** op:

- `Speakybara-…-windows.zip` voor Windows 10 of 11 (64-bits)
- `Speakybara-…-macos.zip` voor de Mac (macOS 14 of nieuwer, Mac met Apple-chip)

## Installeren op Windows

1. Pak de zip helemaal uit (rechtermuisknop → **Alles uitpakken**).
   Rechtstreeks starten vanuit de zip werkt niet.
2. Dubbelklik op **Speakybara.exe**.
3. Windows zegt: *"Windows heeft uw pc beveiligd"*.
   Klik op **Meer informatie** → **Toch uitvoeren**.

Die waarschuwing hoort erbij. Ze verschijnt bij elk programma zonder duur
handtekeningcertificaat, niet omdat er iets mis is met dit bestand.

Er wordt niets geïnstalleerd. Alles blijft in de map die je uitpakt: je
instellingen, je geschiedenis en de stemmen. Map weggooien is alles weggooien.

**Updaten:** pak de nieuwe zip uit in een nieuwe map en neem je eigen
bestanden mee uit de oude: `config.json`, `history.json`, `annotations.json`,
`words.json`, `pronunciations.json`, `usage.json`, `eigen-woorden.txt`,
`english-words.txt` en de mappen `previews` en `voices`.

## Installeren op de Mac

1. Dubbelklik op de zip en sleep **Speakybara** naar de map **Apps**
   (Programma's).
2. Open Speakybara. macOS zegt dat het de app niet op malware kan
   controleren, omdat Apple hem nog niet heeft ondertekend. Klik op **Gereed**.
3. Open **Systeeminstellingen › Privacy en beveiliging**, scrol naar beneden
   en klik bij Speakybara op **Toch openen**. Dat hoef je maar één keer te doen.
4. Zet **Schermopname** aan als de app erom vraagt. Zonder die toestemming
   ziet hij de tekst in je kader niet.

## Sneltoetsen

| Windows | Mac | Wat het doet |
| --- | --- | --- |
| `Ctrl` + `Alt` + `S` | `Control` + `Option` + `S` | Kader trekken en laten voorlezen |
| `Ctrl` + `Alt` + `E` | `Control` + `Option` + `E` | Kader trekken en de tekst kopiëren |
| `Ctrl` + `Alt` + `C` | `Control` + `Option` + `C` | Voorlezen wat op je klembord staat |
| `Ctrl` + `Alt` + `P` | `Control` + `Option` + `P` | Pauze / verder |
| `Ctrl` + `Alt` + `X` | `Control` + `Option` + `X` | Stoppen |

## Wat er in deze versie zit

- Tekstherkenning die op je eigen computer draait, zonder internet.
- Scrollshot: scroll in het kader om meer tekst te pakken dan op je scherm past.
- Het kader blijft staan na het slepen: stel het bij en kies eronder of je
  wilt voorlezen, kopiëren of een snelle actie gebruiken.
- Een leespagina om mee te lezen, te markeren, notities te maken en op te
  zoeken wat een woord betekent.
- Stemmen die op je eigen computer draaien, en 37 talen om voor te lezen.
  De app zelf is er in 36 talen.

## Wat nog niet af is

- De apps zijn niet ondertekend, vandaar de waarschuwing van Windows en de
  extra stap op de Mac.
- De Mac-versie werkt alleen op een Mac met Apple-chip (M1 of nieuwer).
- Speakybara Managed (de stemmen van Google zonder eigen sleutel) komt na
  de testperiode.
- Op Windows moet Windows de taal kennen die je laat voorlezen.

## Iets kapot? Iets raars?

Vertel het via het [feedbackformulier](https://speakybara-website.vercel.app/nl/feedback),
of open een [issue](../../issues) en schrijf op wat je deed en wat er gebeurde.
Een schermafbeelding helpt enorm. Start de app op Windows niet op, plak dan
`screenspeak-error.log` uit de map erbij.
