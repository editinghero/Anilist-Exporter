# AniList Export

A small browser-based exporter for AniList anime and manga lists. It fetches public AniList data and creates backup files plus MyAnimeList-compatible XML.

> To Use It, [Download AniList Exporter](Anilist-Exporter.html) the HTML file and open in browser it runs via filemanger



## Output files

- `<username>-anime.xml` — MAL-compatible anime list.
- `<username>-manga.xml` — MAL-compatible manga list.
- `<username>-anime.csv` / `<username>-manga.csv` — CSV exports with AniList list data.
- `<username>-all.csv` — combined anime + manga CSV.
- `<username>-anilist-export.json` — raw JSON backup.

MAL XML scores are rounded to whole numbers. CSV and JSON keep the original decimal scores. Entries without a MAL ID are omitted from the MAL XML.

## Usage

1. Open `Anilist_Exporter.html` in a normal browser.
2. Enter your AniList username.
3. Click **Fetch lists**.
4. Download the files you need.

The AniList list must be publicly accessible because the exporter uses the public GraphQL API without AniList login/OAuth.

## Import into MyAnimeList

Open the [MyAnimeList Import page](https://myanimelist.net/import.php).

1. Choose **MyAnimeList Import**.
2. Select the generated `-anime.xml` or `-manga.xml` file.
3. Submit the import and review the result.
## Import into Anilist
Anilist support import from Mal exported entry hence these entry you will be able to import it


## AniList documentation

- [AniList API documentation](https://anilist.gitbook.io/anilist-apiv2-docs/)
- [GraphQL query guide](https://anilist.gitbook.io/anilist-apiv2-docs/docs/guide/graphql/queries)
- [AniList Media reference](https://anilist.gitbook.io/anilist-apiv2-docs/docs/reference/object/media)
- API endpoint: `https://graphql.anilist.co`

---
---
---

*** Star the repo if you liked it ***

[Koka](https://GitHub.com/editinghero/koka) - this is a all in anime and manga manager powered by anilist, with ai integrated and RSS news

