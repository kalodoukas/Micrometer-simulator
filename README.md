# Micrometer readings simulator — PWA package

## Περιεχόμενα

- `index.html` — κύρια εφαρμογή
- `manifest.json` — PWA manifest
- `service-worker.js` — offline cache / install support
- `icons/` — εικονίδια PWA 192x192 και 512x512

## Ανέβασμα στο GitHub Pages

1. Δημιουργήστε νέο repository στο GitHub.
2. Ανεβάστε όλα τα αρχεία και τον φάκελο `icons` στη ρίζα του repository.
3. Πηγαίνετε: **Settings → Pages**.
4. Στο **Build and deployment**, επιλέξτε:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Πατήστε **Save**.
6. Μετά από λίγο, η εφαρμογή θα είναι διαθέσιμη στο URL του GitHub Pages.

## Σημείωση

Για να λειτουργεί σωστά ως PWA, η εφαρμογή πρέπει να σερβίρεται μέσω HTTPS. Το GitHub Pages παρέχει HTTPS αυτόματα.
