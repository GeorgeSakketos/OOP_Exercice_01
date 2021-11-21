# OOP-Exercice-01

## Εντολή Μεταγλώττισης

g++ bookcase.cpp bookcart.cpp -o bookcase

## Δοκιμαστικές Τιμές Παράμετρων

./bookcase 10 7 4 5

./bookcase 25 17 13 8

./bookcase 6 26 23 9

./bookcase 5 26 23 14

## Πληροφορίες Και Αιτιολογήσεις

###### Πληροφορίες ######

**1.** Για να μην δημιουργηθούν errors απο τον τρόπο διαχείρισης των
       δεδομένων υπάρχει ένας προκαθορισμένος τρόπος υλοποίησεις
       τους μέσα στην κλάση Bookcase που λειτουργεί ως η "Βάση" 
       της βιβλιοθήκης.

###### Αιτιολογήσεις ######
**1.** Χρησιμοποιώ δυο συναρτήσεις για να τοποθετήσω και να 
       αφαιρέσω τα βιβλία στο σημείο που πρέπει να τοποθετηθούν 
       ώστε να γίνεται πιο εύκολο να γίνει κάποια αλλαγή στον 
       κώδικα σε περίπτωση  προβλήματος η αλλαγής της λειτουργεία 
       του προγράμματος.
       
Π.Χ.
Αμα ήθελα το ντουλάπι να έχει περισσότερα ράφια η διαφορετική κατασκευή 
δεν θα χρειαστεί να πειράξω τον κώδικα που διαχειρίζεται τα ράφια εκτός 
του ντουλαπιού.



