# Space Explorer · Grade 5

A single website for the Grade 5 space reading set.

**[Open the Space Explorer hub](https://lenguajelabs-design.github.io/Grade-5-Science-Unit-Researching-Space/)**

| Topic | Direct link |
| --- | --- |
| Mars | [Read about Mars](https://lenguajelabs-design.github.io/Grade-5-Science-Unit-Researching-Space/mars/) |
| Earth’s Moon | [Read about the Moon](https://lenguajelabs-design.github.io/Grade-5-Science-Unit-Researching-Space/moon/) |
| International Space Station | [Read about the ISS](https://lenguajelabs-design.github.io/Grade-5-Science-Unit-Researching-Space/iss/) |
| The Sun | [Read about the Sun](https://lenguajelabs-design.github.io/Grade-5-Science-Unit-Researching-Space/sun/) |
| Constellations | [Read about constellations](https://lenguajelabs-design.github.io/Grade-5-Science-Unit-Researching-Space/constellations/) |

Each reader retains its photographs, PDF, language support, listening tools, and source credits. Device/browser speech services determine voice availability.

## How publication works

GitHub Pages is set to **GitHub Actions**. The `Publish Space Explorer` workflow assembles the static website and deploys it after pushes to `main`. The build reads repository files; it does not write back to the repository. No database, student accounts, remote fonts, or remote application scripts are required.

The initial browser upload stores the reader payloads as `file-000` through `file-088`. The workflow maps those payloads to their public paths when it builds the website. **[SOURCE-INDEX.md](SOURCE-INDEX.md)** identifies every file, its destination, and its checksum. To update a payload, edit or replace the corresponding source file while retaining its name; the next push rebuilds the website. The mapping is in `.github/workflows/publish.yml`. If changing the content structure, update that mapping too.

All application links and asset URLs are relative so they work under this GitHub project path or a custom domain. Source citations in the readers lead to external websites.

## Padlet

Replace the old separate hosting destinations with the direct topic links above, or use the master hub link. The old warning screenshot is from Padlet’s link scanner. A new address is not a guarantee against a scanner warning; request a review from Padlet support if a valid link is flagged.
