# Dashboard Immobilier — GitHub Pages

**Mobile-first** • KPIs éditables • Checklists hebdo/mensuel/trimestre • Persistance JSON (localStorage + export/import).

## Déployer sur GitHub Pages (rapide)
1. Crée un dépôt `immoplan-dashboard` sur GitHub.
2. Ajoute `index.html`, `db.sample.json`, `README.md`, `LICENSE`, `.nojekyll` à la racine.
3. Dans **Settings → Pages** : Source = *Deploy from a branch*, Branch = *main*, Folder = */ (root)* → **Save**.
4. Ton site : `https://<ton-user>.github.io/immoplan-dashboard/`.

## Données
- Stockées localement via `localStorage`. Utilise **Exporter/Importer JSON** pour backup/restauration.
