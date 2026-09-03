# you-site

Produktseite von YOU (Körper und Geist) auf https://you.yg-media.de, gebaut von YG MEDIA nach dem Muster von usely-site. Reines HTML/CSS/JS, deutsch als Master unter `/`, englisch unter `/en/`. Deploy über GitHub Pages (Actions-Workflow, `scripts/` bleibt draußen).

Gate vor jedem Commit: `python3 scripts/verify.py` muss grün sein.
Lokal testen: `python3 -m http.server 8767` im Repo-Root.
Doku und Entscheidungen: YG-Brain (Repo YGMEDIA/Website, `brain/06-specs/SPEC-you-onepager.md`).
