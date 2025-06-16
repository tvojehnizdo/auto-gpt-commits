
README – Automatický GPT Bot pro více repozitářů

1. V GitHubu přejdi na záložku Actions → GPT Multi-Repo Commit
2. Klikni na „Run workflow“
3. Vyplň:
   - Název cílového repozitáře (např. tvojehnizdo.github.io)
   - Cestu k souboru (např. index.html)
   - Nový obsah, který má být zapsán

4. GPT bot provede commit a push do repozitáře.

Ujisti se, že:
- máš v sekci Settings → Secrets uložený klíč `GH_PAT`
- cílový repozitář je tvůj nebo máš práva pro zápis
