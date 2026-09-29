FINAL v10 — PERSISTENT PROGRESS FIX FOR iPHONE PWA

Η πρόοδος πλέον αποθηκεύεται ταυτόχρονα σε:
1. localStorage
2. persistent cookie
3. IndexedDB

Επίσης:
- αποθηκεύεται η ορατή ερώτηση μόλις το app πάει στο background,
  πριν προλάβει ο χρήστης να το κλείσει από το app switcher,
- κάθε αποθήκευση έχει timestamp ώστε να κερδίζει πάντα η πιο πρόσφατη θέση,
- παλιά κολλημένη τιμή «5» δεν υπερισχύει πλέον μιας νεότερης αποθήκευσης,
- παραμένουν οι ερωτήσεις 1–600, Previous/Next, logo, checkpoints και offline mode.

GitHub: αντικατάστησε μόνο
- index.html
- service-worker.js

Μετά Commit changes και περίμενε το deploy.
