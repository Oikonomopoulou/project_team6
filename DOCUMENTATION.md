Η αρχική σκέψη ήταν να επεξεργαστούμε την ετήσια καταγραφή-λίστα του 2021 με τα δολοφονημένα τρανς άτομα (TvT_TMM_TDoR2021_Namelist DATA) από το ΤΜΜ, η οποία ήταν και η πιο πρόσφατη μέχρι στιγμής. Παρόλα αυτά, υπήρχαν πάρα πολλές κενές τιμές και γενικότερα προβλήματα ως προς την ανάγνωση μέσω Jupyter Notebook τα οποία καθιστούσαν την ανάλυση των δεδομένων αρκετά δύσκολη. 
Γι΄αυτό αποφασίσαμε να επιλέξουμε ποιες μεταβλητές χρειαζόμασταν για το data story μας και να τις συμπεριλάβουμε σ'ένα καινούργιο αρχείο excel, με σκοπό να φαίνονται οργανωμένες και εύκολα αναγνώσιμες.

Οι μεταβλητές:
Age: Ηλικία δολοφονημένων τρανς ατόμων
Occupation: Επάγγελμα δολοφονημένων τρανς προσώπων
Country: Χώρα-τόπος περιστατικού εγκλήματος
CoD: Τρόπος που εκτελέστηκαν οι δολοφονίες

Υπάρχαν αρκετές κενές τιμές (nan) και διπλότυπα στο πρώτο excel, τα οποία προσπαθήσαμε να τα αντιμετωπίσουμε με την βοήθεια του Tabula και του Google Spreadsheets. Στην συνέχεια, αποφανθήκαμε, πως η καλύτερη λύση για ένα ομοιόμορφο και αναγνώσιμο τόσο από εμάς όσο και από το αναγνωστικό κοινό είναι να καταγράψουμε σε ένα νέο excel γραπτώς την κάθε περίπτωση από 01.01.2021 έως και  30.09.2021. 

Κατά την διάρκεια της αναλύσης παρατήρησαμε πως κάποια δεδομένα όπως για παράδειγμα τα αίτια θανάτου και το επάγγελμα αναφέρονταν ως not reported. Παρόλα αυτά, τα συμπεριλάβαμε ως μία ανεξάρτητη μεταβλητή στα ραβδογράμματα που δημιουργήσαμε στην συνέχεια για να μην πέσουμε στην παγίδα της υποκαταγραφής.
