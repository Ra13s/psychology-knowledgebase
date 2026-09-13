# Allikaregister

`processed.jsonl` sisaldab üht JSON-objekti rea kohta. Algfail on tühi, sest ühtegi allikat pole selle repo jaoks veel läbi töötatud.

Iga kirje väljad:

- `processed_at`: tegelik läbitöötamise kuupäev kujul YYYY-MM-DD.
- `title`, `url`, `publisher_or_authors`: kontrollitud allika andmed.
- `published_at`: allika avaldamiskuupäev või null, kui teadmata.
- `disposition`: `incorporated`, `context`, `skipped-duplicate`, `skipped-weak-evidence`, `skipped-out-of-scope` või `deferred`.
- `story_path`: seotud loo suhteline failitee või null.
- `note`: otsuse lühike põhjendus.

Säilita varasemad kirjed. Ära lisa allikat loetuks üksnes sellepärast, et nägid otsingutulemust. Kontrolli duplikaate URL-i ja töö identiteedi, mitte üksnes pealkirja järgi.
