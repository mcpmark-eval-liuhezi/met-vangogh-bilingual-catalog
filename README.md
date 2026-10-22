# Van Gogh — Bilingual English–Italian Catalog

## English

This bilingual English–Italian catalog accompanies our online exhibit on Vincent van Gogh, co-produced with our partner museum in Rome. It presents six paintings by Vincent van Gogh (Dutch, Zundert 1853 – 1890 Auvers-sur-Oise) from the European Paintings department of The Metropolitan Museum of Art in New York. For each work, the file `vangogh_catalog.csv` records the Met object ID, the title in English and Italian, the artist, the creation date, the medium in English and Italian, the department, and the link to the primary collection image.

The six works are:

1. **Sunflowers** (1887) — a Paris-period bouquet of sunflower heads built up in bold impasto;
2. **Self-Portrait with a Straw Hat** (1887) — painted on the reverse of a study of a peasant peeling potatoes;
3. **The Flowering Orchard** (1888) — an orchard in spring blossom painted in Arles;
4. **L'Arlésienne: Madame Joseph-Michel Ginoux** (1888–89) — a portrait of the proprietress of the Café de la Gare in Arles;
5. **Wheat Field with Cypresses** (1889) — painted at the Saint-Rémy asylum with a swirling sky and flame-like cypresses;
6. **Irises** (1890) — a still life of irises executed in the last year of the artist's life.

All six are painted in oil on canvas.

**Validation results:** the catalog table was assembled and validated in Python using pandas. **All 6 of 6 rows passed validation.** Every row has non-empty values in both languages (English and Italian titles and medium wording), and every image URL is well-formed and points to the primary image of the Met collection record. The Italian medium wording is governed by the terminology glossary `vangogh-art-terms`, which enforces "Oil on canvas" as "Olio su tela".

Data source: The Metropolitan Museum of Art collection records.

---

## Italiano

Questo catalogo bilingue inglese-italiano accompagna la nostra mostra online su Vincent van Gogh, coprodotta con il nostro museo partner a Roma. Presenta sei dipinti di Vincent van Gogh (olandese, Zundert 1853 – 1890 Auvers-sur-Oise) della sezione Pittura europea del The Metropolitan Museum of Art di New York. Per ogni opera, il file `vangogh_catalog.csv` riporta il numero di inventario del Met, il titolo in inglese e in italiano, l'autore, la data di esecuzione, la tecnica in inglese e in italiano, la sezione e il collegamento all'immagine principale della collezione.

Le sei opere sono:

1. **Girasoli** (1887) — un mazzo di capolini di girasole del periodo parigino, realizzato con un impasto deciso;
2. **Autoritratto con cappello di paglia** (1887) — dipinto sul retro di uno studio di una contadina che sbuccia patate;
3. **Il frutteto in fiore** (1888) — un frutteto in piena fioritura primaverile dipinto ad Arles;
4. **L'Arlésienne: Madame Joseph-Michel Ginoux** (1888–89) — ritratto della proprietaria del Café de la Gare di Arles;
5. **Campo di grano con cipressi** (1889) — dipinto nell'ospedale psichiatrico di Saint-Rémy, con un cielo vorticoso e cipressi simili a fiamme;
6. **Iris** (1890) — una natura morta di iris eseguita nell'ultimo anno di vita dell'artista.

Tutte e sei le opere sono eseguite a olio su tela.

**Risultati della validazione:** la tabella del catalogo è stata assemblata e validata in Python utilizzando pandas. **Tutte e 6 le righe su 6 hanno superato la convalida.** Ogni riga presenta valori non vuoti in entrambe le lingue (titoli e denominazione della tecnica in inglese e in italiano), e ogni URL dell'immagine è ben formato e rimanda all'immagine principale della scheda della collezione del Met. La denominazione della tecnica in italiano è disciplinata dal glossario terminologico `vangogh-art-terms`, che prescrive "Oil on canvas" come "Olio su tela".

Fonte dei dati: Schede della collezione del Metropolitan Museum of Art.
