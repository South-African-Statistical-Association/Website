# SASA Quarto site

Source for the South African Statistical Association website, built with [Quarto](https://quarto.org). The content mirrors sastat.org as of September 2026.

## Build

- `quarto preview` to view the site locally.
- `quarto render` to build it into `_site/`.

## Where things live

| Content | File(s) |
|---|---|
| Home page (announcement, events, news, jobs summary) | `index.qmd` |
| Navigation, footer, site settings | `_quarto.yml` |
| Colours and layout | `styles.scss` (SASA blue is `$sasa-main`) |
| About, mission, executive committee, past presidents, honorary members | `about/` |
| Membership, login, profile update, partner, SACNASP, privacy | top-level `.qmd` files |
| Special interest groups | `groups/` |
| Education committee, bursaries, competitions, funding | `education/` |
| Awards (Sichel Medal, SAS Thought Leader, postgraduate) | `awards/` |
| Events and conferences | `events/` |
| News, columns and profiles (Quarto listings) | `articles/news/`, `articles/columns/`, `articles/profiles/` |
| Universities, universities of technology, research institutions | `community/` |
| Jobs, journal, resources | `jobs.qmd`, `journal.qmd`, `resources.qmd` |
| Photos and logos | `images/` (people, presidents, awards, groups, profiles, articles, conferences) |
| PDFs (constitution, brochures, glossaries, infographic) | `about/files/`, `groups/files/`, `resources/files/`, `files/` |

## Common updates

- **New job advert:** edit `jobs.qmd` and the jobs bullet on `index.qmd`.
- **New event:** edit `events/current-and-upcoming.qmd` and the events bullet on `index.qmd`.
- **New President's Column or profile:** add a `.qmd` file to `articles/columns/` or `articles/profiles/` with `title`, `date`, `description` and `image` in the front matter. The listing pages pick it up automatically.
- **Committee change:** edit the relevant page and drop a square photo into `images/people/`.
