# GPT Multi-Repo Commit

Tento repozitář obsahuje workflow **gpt-multirepo.yml**,
který slouží k automatickému provádění commitů do jiných
repozitářů na GitHubu. Workflow umožňuje přepsat daný soubor
v cílovém repozitáři zadaným obsahem a následně změny
odeslat.

## Spuštění workflow

1. Na GitHubu otevři záložku **Actions** tohoto repozitáře a zvol
   workflow **GPT Multi-Repo Commit**.
2. Klikni na **Run workflow** a vyplň parametry:
   - `repo` – název cílového repozitáře (např. `tvojehnizdo.github.io`)
   - `file_path` – cesta k souboru (např. `index.html`)
   - `content` – nový obsah, který se do souboru zapíše
3. Po spuštění proběhne klonování repozitáře, přepsání daného souboru,
   commit a push.

Pro správné fungování musí být v sekci **Settings → Secrets → Actions**
uložen tajný klíč `GH_PAT` s právem zápisu do cílového repozitáře.
