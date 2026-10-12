# Near Mosque content

Files the Near Mosque apps download on request. No app code lives here.

| Folder | What it is | Terms |
|---|---|---|
| `packs/` | Downloadable content for the app's languages (library, Qur'an translations and other sources). Each pack's manifest names its sources. | Each source's own terms, as recorded in the pack manifests and the app's Sources screen. |
| `books/` | Classical books of Ahl al-Sunnah: the authors' text, one PDF per printed volume, without the modern editors' notes. | The texts come from the OpenITI corpus (KITAB project), licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/): free, non-commercial use with attribution, shared under the same licence. Cite: Romanov, M. & Seydi, M., *OpenITI: a Machine-Readable Corpus of Islamicate Texts*, doi:10.5281/zenodo.3082463. Typeset in Amiri (SIL Open Font License 1.1). |

The apps check every file against a SHA-256 they were built with, so a changed file is never used.
Each app version downloads from one fixed commit of this repository, so files can be added later without changing what an installed app receives.
