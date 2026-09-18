# Loggbøker – Bildediagnostikk Kalnes

En enkel, selvstendig nettside som samler:

- **Lenker til loggbøkene** (Lab 4, 6, 7 og Transportabel 2, 3, 4) i SharePoint.
- **Veiledning** for hvordan man fører loggen.
- **En «Meld feil»-knapp** som åpner e-post (Outlook) med mottakere og kopimottakere ferdig utfylt.

## Filer

- `index.html` – hele siden, én selvstendig fil (ingen byggesteg, ingen avhengigheter).

## Publisering via GitHub Pages

1. Gå til repoets **Settings → Pages**.
2. Under **Source**, velg branchen og mappen `/ (root)`.
3. Lagre. Siden blir tilgjengelig på `https://<bruker>.github.io/loggbok/`.

Alternativt kan `index.html` legges rett på en intern webserver / SharePoint.

## Tilpasning

- **Mottakere:** Rediger `TO`- og `CC`-listene i `<script>` nederst i `index.html`.
- **Loggbok-lenker:** Rediger `LABS`-listen samme sted.
- **Veiledningstekst:** Rediger seksjonen «Slik fører du loggen» i HTML-en.

> **Merk om veiledningsteksten:** Innholdet under «Slik fører du loggen» er en generell
> mal og *ikke* en offisiell rutine. Gå gjennom og tilpass til faktisk praksis.

> **Merk om e-postknappen:** Lenken bruker komma mellom adressene (RFC-standard).
> Enkelte Outlook-oppsett tar kun med første mottaker med komma. Kopier-knappene på
> siden fungerer som reserveløsning hvis ikke alle mottakere fylles inn automatisk.
