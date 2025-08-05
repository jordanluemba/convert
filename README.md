# FileToJPG

Convertisseur de fichiers Word, PDF et Excel en images JPG directement dans le navigateur.

## Fonctionnalités

- Glisser-déposer ou sélection de fichiers DOC, DOCX, PDF, XLS, XLSX
- Conversion locale en images JPG (aucun envoi sur un serveur)
- Affichage de la progression de conversion
- Téléchargement individuel ou groupé des images générées
- Interface moderne avec Tailwind CSS

## Technologies utilisées

- [Tailwind CSS](https://tailwindcss.com/) pour le style
- [PDF.js](https://mozilla.github.io/pdf.js/) pour la conversion PDF
- [xlsx](https://github.com/SheetJS/sheetjs) pour la conversion Excel
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) pour la conversion Word

## Utilisation

1. Ouvre `index.html` dans ton navigateur.
2. Glisse/dépose ou sélectionne tes fichiers Word, PDF ou Excel.
3. Clique sur "Convertir tout".
4. Télécharge les images JPG générées individuellement ou toutes en une fois.

## Limitations

- La conversion Word et Excel est simplifiée (texte uniquement, pas de mise en page avancée).
- La conversion se fait entièrement côté client, donc certaines fonctionnalités avancées ne sont pas prises en charge.

## Licence

Projet open source, libre d'utilisation et de modification.

---

© FileToJPG - Tous