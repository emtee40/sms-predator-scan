# Συχνές ερωτήσεις και απαντήσεις

## Τι είναι το Predator;

Το Predator της εταιρείας Cytrox, είναι ένα λογισμικό παρακολούθησης (spyware) που μπορεί να αποκτήσει απόλυτο έλεγχο στις κινητές συσκευές που μολύνει. Αυτό συμπεριλαμβάνει πρόσβαση σε προσωπικά μηνύματα και αρχεία, ηχογράφηση κλήσεων, καθώς και παρακολούθηση του περιβάλλοντος μέσω κάμερας και μικροφώνου, ακόμα και όταν η συσκευή φαίνεται απενεργοποιημένη. Η μόλυνση μπορεί να λάβει χώρα, όταν η συσκευή-στόχος ανοίξει μια μολυσμένη διαδικτυακή διεύθυνση, που μπορεί να έχει αποσταλεί από άγνωστο αριθμό μέσω SMS. Τέτοια SMS αποστάλθηκαν το 2021 στον δημοσιογράφο Θανάση Κουκάκη και στον πολιτικό Νίκο Ανδρουλάκη. 

Μπορείτε να διαβάσετε ένα σύντομο χρονικό της υπόθεσης [στον εξής σύνδεσμο](https://mailchi.mp/insidestory.gr/nphlh7jzcb-1339247), και ένα αναλυτικότερο χρονικό [στον εξής σύνδεσμο](https://insidestory.gr/article/predator-stin-ellada-hroniko-ton-apokalypseon?token=E36120MB1L), σε περιγραφή του Inside Story.

## Πώς δουλεύει η εφαρμογή SMS Predator Scan;

Η εφαρμογή σκανάρει όλα τα μηνύματα SMS στην εξεταζόμενη συσκευή, για την παρουσία συνδέσμων URL προς οποιαδήποτε από τις 326 κακόβουλες διευθύνσεις που δημιουργήθηκαν από την Cytrox, πιθανότατα για επιθέσεις του Predator. Οι διευθύνσεις αυτές [παρέχονται](https://github.com/AmnestyTech/investigations/tree/master/2021-12-16_cytrox) από το τεχνικό τμήμα της Διεθνούς Αμνηστίας, συλλέχθηκαν σε συνεργασία με την Meta (ιδιοκτήτρια Facebook) και την Google, και ενημερώθηκαν πιο πρόσφατα στις 23-5-2022. 

Μπορείτε να δείτε την λίστα των διευθύνσεων ελληνικού ενδιαφέροντος [στον εξής σύνδεσμο](https://insidestory.gr/article/neo-logismiko-kataskopeias-predator-kai-oi-doyleies-stin-ellada?token=V2Q30SQ9U2#:~:text=%CE%99%CF%83%CF%84%CE%BF%CF%83%CE%B5%CE%BB%CE%AF%CE%B4%CE%B5%CF%82%20%CE%B5%CE%BB%CE%BB%CE%B7%CE%BD%CE%B9%CE%BA%CE%BF%CF%8D%20%CE%B5%CE%BD%CE%B4%CE%B9%CE%B1%CF%86%CE%AD%CF%81%CE%BF%CE%BD%CF%84%CE%BF%CF%82).

## Η εφαρμογή μου έβγαλε πράσινο αποτέλεσμα με 0 εντοπισμούς. Μπορώ να είμαι σίγουρος ότι δεν παρακολουθούμαι;

Όχι. Το αποτέλεσμα αυτό θα πει μόνο ότι δεν υπάρχει αυτήν τη στιγμή SMS στην συσκευή σας που να αναφέρει κάποια από τις γνωστές 326 κακόβουλες διευθύνσεις. Τα σενάρια όπου θα μπορούσε να έχει λάβει χώρα απόπειρα μόλυνσης με το Predator, χωρίς η εφαρμογή να βρίσκει σχετική ένδειξη, είναι τα εξής:

* αφού λάβατε το επίμαχο SMS, το διαγράψατε.
* λάβατε το επίμαχο SMS, ανοίξατε το σχετικό σύνδεσμο, η συσκευή σας μολύνθηκε, και μετέπειτα, οι χειριστές του Predator έσβησαν το SMS. Δε συνέβη κάτι τέτοιο στην περίπτωση μόλυνσης Κουκάκη, αλλά δεν αποκλείεται να συνέβη σε άλλες περιπτώσεις, μετά τη γνωστοποίηση της υπόθεσης.
* έγινε απόπειρα μόλυνσης μέσω άλλης οδού, όπως με διαδικτυακό μήνυμα (π.χ. email, Messenger, Viber, WhatsApp).
* έγινε χρήση κάποιας άλλης κακόβουλης διεύθυνσης, που δεν έχει εντοπιστεί μέχρι στιγμής ώστε να προστεθεί στη λίστα. Αυτό δε θεωρείται ιδιαίτερα πιθανό για τις παλιότερες επιθέσεις, λόγω των ευρειών μεθόδων εντοπισμού που χρησιμοποίησαν οι Meta και Google.

Ευρύτερα, η εφαρμογή δεν ελέγχει για απόπειρες μόλυνσης με άλλα λογισμικά παρακολούθησης. Για έναν συνολικό αυτοματοποιημένο έλεγχο, μπορείτε να χρησιμοποιήσετε λογισμικά antivirus (σύνδεσμοι προτάσεων: [Android](https://www.tomsguide.com/best-picks/best-android-antivirus) και [iOS](https://www.techradar.com/best/best-iphone-antivirus-app)). Μέχρι στιγμής, κατά τη γνώση μας, καμιά εταιρεία δεν έχει επιβεβαιώσει την δυνατότητα του λογισμικού προστασίας της να εντοπίζει αυτόματα το Predator, αλλά τα λογισμικά αυτά μπορούν να εντοπίσουν σειρά άλλων spyware.

## Η εφαρμογή μου έβγαλε κόκκινο αποτέλεσμα με εντοπισμό επίθεσης. Τι να κάνω;

Καταρχάς, ανατρέξτε στο συνολικό μήνυμα ή μηνύματα που υποδεικνύει η εφαρμογή, ώστε να επιβεβαιώσετε ότι όντως πρόκειται για ύποπτο μήνυμα, χωρίς όμως να ανοίξετε το σύνδεσμο ή συνδέσμους που περιλαμβάνονται. Έπειτα, μπορείτε [να επικοινωνήσετε](https://cyberalert.gr/) με την Διεύθυνση Δίωξης Ηλεκτρονικού Εγκλήματος. Επίσης, μπορείτε [να επικοινωνήσετε](mailto:insidestoryeditorial@mailfence.com) με τεχνικούς του Inside Story, ώστε να εξετάσουν σε βάθος την συσκευή σας. Αν έχετε ανοίξει τον ύποπτο σύνδεσμο ή συνδέσμους, χρησιμοποιήστε άλλη συσκευή για τις εν λόγω επικοινωνίες.

## Μπορούν να εκτεθούν τα SMS μου κατά τον έλεγχο της εφαρμογής;

Όχι. Η εφαρμογή δεν επιτελεί άλλη εργασία πέρα από τον έλεγχο των SMS για τις προαναφερόμενες κακόβουλες διευθύνσεις, δεν κρατάει αντίγραφα των SMS, και δεν συλλέγει δεδομένα κανενός τύπου. Ο έλεγχος λαμβάνει χώρα τοπικά και η εφαρμογή δεν επικοινωνεί με κανέναν εξωτερικό server. Η εν λόγω [πολιτική απορρήτου](https://support.google.com/googleplay/android-developer/answer/10787469?hl=en) έχει δηλωθεί στο Play Store και έχει επαληθευτεί από τεχνικούς της Google, πριν από την δημοσίευση της εφαρμογής.

## Επιτρέπεται η επαναχρησιμοποίηση του κώδικα της εφαρμογής;

Ο κώδικας είναι διαθέσιμος στο [παρόν αποθετήριο GitHub](https://github.com/an-ko-7/sms-predator-scan), υπό την άδεια ανοικτού κώδικα MIT.

## Είναι η εφαρμογή διαθέσιμη και για κινητές συσκευές Apple (λειτουργικό σύστημα iOS);

Μέχρι στιγμής όχι, καθώς το iOS δεν επιτρέπει πλήρη πρόσβαση στα SMS για καμιά εξωτερική εφαρμογή. Ωστόσο, είναι υπό εξέταση η ανάπτυξη μιας πιο χειροκίνητης εφαρμογής για iOS, που θα μπορούσε να λειτουργεί με βάση [φίλτρα spam](https://developer.apple.com/documentation/sms_and_call_reporting/sms_and_mms_message_filtering), στα οποία [παρέχει πρόσβαση](https://9to5mac.com/2022/06/15/sms-filtering-api-more-categories-ios-16/) το iOS.

## Ποιος ανέπτυξε την εφαρμογή;

Η εφαρμογή αναπτύχθηκε από τον Ανδρόνικο Κουτρουμπέλη, fact-checker με τα [Ελληνικά Hoaxes](https://www.ellinikahoaxes.gr/), τα οποία συνεργάζονται με την Meta για την αντιμετώπιση της παραπληροφόρησης στις πλατφόρμες της (Facebook, Instagram). Το Inside Story συμμετείχε συμβουλευτικά κατά την διαδικασία ανάπτυξης. Για απορίες, ευρήματα ή τεχνικές επισημάνσεις, μπορείτε να επικοινωνήσετε με τον Ανδρόνικο στην εξής ασφαλή διεύθυνση: <an.koutroumpelis@proton.me>.
