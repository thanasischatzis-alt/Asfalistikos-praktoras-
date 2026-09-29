FINAL v7 — iPhone/PWA RESUME FIX

Διορθώσεις:
- Δεν χρησιμοποιείται πλέον IntersectionObserver που μπορούσε να ξαναγράψει λάθος την Ερώτηση 5.
- Η τελευταία ερώτηση κρατιέται και σε ξεχωριστό resume key.
- Αν το παλιό lastQuestion έχει ήδη χαλάσει, το app ανακτά τη θέση από τις αποθηκευμένες απαντήσεις.
- Απενεργοποιείται το browser scroll restoration.
- Γίνεται επαναφορά της σωστής ερώτησης και μετά τη φόρτωση/pageshow.
- Το πραγματικό logo παραμένει.

GitHub: αντικατάστησε μόνο
1. index.html
2. service-worker.js

Μετά Commit changes, περίμενε το deploy, και άνοιξε μία φορά με internet.
