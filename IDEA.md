# Veridomo - idea del sito (31/10/2026)

Repo `cialdecompatibili-netizen/veridomo`, creata il 31/10/2026 con `nuovo_sito.ps1` da `mistraltemplate1` (IT + EN, shop acceso, accento #0e7490 verde acqua scuro).
Sito: https://cialdecompatibili-netizen.github.io/veridomo/

## Idea (da Mirco)
Un sito di allarmi per la casa "tipo Verisure" (allarme monitorato, centrale operativa, app), ma con un brand NOSTRO e non uguale a nessuno.

## Perche' il nome Veridomo
- Cercati nel web e SCARTATI: **Very Alarm** (veryalarm.it e' gia' una societa' di allarmi in Italia), **Verisure** (il modello), **Verizon** (colosso telecom, marchio famoso), **Verison** (troppo vicino a Verizon). Evitare anche Veriallarm (assonanza con Very Alarm).
- **Veridomo** = "veri" + "domo" (casa, in latino/italiano). Cercando nome e parole vicine non ho trovato un marchio di allarmi con lo stesso nome. Nota: non e' una verifica legale; prima di usarlo davvero per un'attivita' controllare marchi (UIBM, EUIPO) e dominio (.it, .com).
- Alternative libere se non piace: Verivigil, Verisentinel.
- Repo GitHub: nessuna repo con questo nome esisteva prima.

## Cosa deve avere il sito (modello Verisure, testi nostri)
- Home: "Proteggi la tua casa", 3 benefici (centrale operativa 24h, videoverifica, app), pulsante preventivo.
- Servizi: allarme casa, allarme azienda, videosorveglianza, perimetrale esterno, antincendio e fumo, assistenza.
- Come funziona: sopralluogo gratuito, installazione, centrale operativa, intervento.
- Shop (acceso): kit allarme, sensori, sirene, telecamere, tastiere. Prodotti dimostrativi, prezzo da definire.
- Preventivo/Contatti: modulo, WhatsApp, telefono.
- FAQ: costi, wireless o cablato, animali domestici, cosa succede quando suona.
- Blog: guide su furti, scelta dell'antifurto, sicurezza in vacanza.

## Regole
- NON copiare testi, immagini, loghi o claim di Verisure o altri: tutto originale.
- Non promettere "guardie giurate" o interventi che non esistono: e' un sito di prova finche' non c'e' un servizio vero.

## DA FARE
- Sostituire i testi segnaposto di home, servizi, chi siamo (IT+EN), poi `python automation\allinea_hash.py`.
- Compilare WhatsApp ed email in `_config.yml`.
- Creare categorie e prodotti shop (kit, sensori, telecamere) e le immagini.
- Logo e colori: ora e' il logo automatico con la V, da rivedere.
- Decidere dominio e controllare i marchi.