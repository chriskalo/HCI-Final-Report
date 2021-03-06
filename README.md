# Τελική αναφορά του μαθήματος Επικοινωνία Ανθρώπου-Υπολογιστή
### Ονοματεπώνυμο:Καλογιάννης Χριστόδουλος
### Αριθμός Μητρώου:Π2017077

Η αναφορά αυτή αφορά την εργασία οπικοποίησης δεδομένων στο μάθημα "Επικοινωνία ανθρώπου υπολογιστή". Παρακάτω, ακολουθούν τα βήματα τα εργαλεία και οι τρόποι επίλυσης κάθε ερωτήματος της εργασίας με εικόνες και gifs που απεικονίζουν τα αποτελέσματα απο τις  προσθήκες τις αλλαγές όπως επίσης και τους κώδικες που χρησιμοποιήθηκαν. Επιπλέον, στην αναφορά περιλαμβάνονται τα συμπεράσματα στα οποία κατέληξα μέσω της ενασχόλησής μου με την συγκεκριμένη εργασία όπως επίσης και η βιβλιογραφία που χρησιμοποιήθηκε.

#### [Link αποθετηρίου](https://github.com/chriskalo/D3js-US-educational-attainment)
#### [Εκτελέσιμο link](https://chriskalo.github.io/D3js-US-educational-attainment/)




## Εισαγωγή
Στόχος της παρούσας εργασίας είναι η επεξεργασία μίας web σελίδας σκοπός της οποίας είναι η οπτικοποίηση δεδομένων.Ειδικότερα, με την χρήση των γλωσσών html,css και javascript έπρεπε να κάνουμε κάποιες αλλαγές στην ιστοσελίδα που αφορούσαν την μορφοποίηση της το περιεχομενό της και την λειτουργικοτητά της.Η εργασία χωρίστηκε σε 2 παραδοτέα. Το πρώτο είχε 5 ερωτήματα ενώ το δεύτερο 3 με σαφώς διαβαθμισμένη δυσκολία.
Τα ερωτήματα που περιείχε το πρώτο παραδοτέο είχαν ως στόχο την αλλαγή των χρωμάτων και στα 3 γραφήματα την αντικατάσταση των διεπαφών των κουμπιών των γραφημάτων με άλλα της επιλογής μας την δυνατότητα να ακούγεται κάποιος ήχος της επιλογής μας όταν διέρχεται το ποντίκι πάνω απο κάποια επιλογή στο μενού την προσθήκη text to speech και τέλος την εφαρμογή responsive design στην σελίδα έτσι ώστε να προσαρμόζεται σε οθόνες διαφορετικών διαστάσεων.Τα ερωτήματα που περιείχε το δεύτερο παραδοτέο είχαν ως στόχο την τροποποίηση του κώδικα έτσι ώστε κάθε στιγμή να είναι εμφανές μόνο ένα από τα 3 γραφήματα, την αντικατάστηση κάθε γραφήματος με κάποιο άλλο διαδραστικό γράφημα της D3js και τέλος σε μια καινούργια σελίδα, την τοποθέτηση αντίστοιχων 3 νέων διαδραστικών γραφημάτων της D3js της επιλογής μας, τα οποία θα οπτικοποιούν καινούργια στατιστικά δεδομένα που θα βρούμε από κάποια επίσημη στατιστική αρχή.Απο όλα τα παραπάνω, αυτά τα οποία δεν κατάφερα να υλοποιήσω ήταν να κάνω responsive τα διαγράμματα της σελίδας ενώ το μενού και τα κείμενα κατάφερα να τα κάνω να προσαρμόζονται σωστά σε κάθε οθόνη χωρίς να αντιμετωπίσω κάποιο πρόβλημα.Επιπλέον, δεν μπόρεσα να κάνω το δεύτερο ερώτημα απο το δεύτερο παραδοτέο καθώς ήταν αρκετα υψηλής δυσκολίας.Σε αυτή την αναφορά περιλαμβάνονται εικόνες και gifs με όλες τις αλλαγές-προσθήκες που έχω κάνει στα πλαίσια της υλοποίησης αυτής της εργασίας όπως επίσης αναφέρονται τα συμπεράσματα τα εργαλεία  οι πηγές και το υλικό που χρησιμοποίησα.



## Σύντομη ανάλυση σχετικών έργων και εργαλείων
Για την εκπόνηση της εργασίας χρησιμοποιήθηκαν διάφορες μεθόδοι αλλά και εργαλεία. Αρχικά, μελετήθηκαν παρόμοιες εργασίες απο προηγούμενα έτη οι οποίες με βοήθησαν να καταλάβω το πως πρέπει να εντάξω τον δικό μου κώδικα στον ήδη υπάρχον αλλα και το πώς πρέπει να κάνω διαχείρηση των αρχείων που χρειάστηκαν όπως για παράδειγμα αρχεία mp3 για το mouseover ή .javascript για τυχόν συναρτήσεις που πρόσθεσα κλπ. Εκτός απο την μελέτη προηγούμενων εργασιών μελέτησα την σύνταξη των γλωσσών προγραμματισμού(html,css,javascript) καθώς ήταν απαραίτητη η κατανόηση του τρόπου λειτουργίας τους αφού για την επεργασία του site μπορούσες να απαντήσεις στα ερωτήματα μόνο με την χρήση κώδικα. Η μελέτη των γλωσσών αυτών έγινε σε site όπως το w3school το οποίο σου δίνει την δυνατότητα εκτός απο την αναλυτική θεωρία  να δοκιμάζεις αλλά και να τροποποιείς έτοιμα παραδείγματα με στόχο την εξοικείωση σου με την γλώσσα αλλα και την αντίληψη των δυνατοτήτων της. Άλλα παρόμοια site στα οποία απευθύνθηκα ήταν το wlearn το Academy of Code και το javascript.com. Απο λογισμικό για την συγγραφή κώδικα χρησιμοποίησα το notepad++ καθώς με διευκόλυνε για την διαχείρηση πολλών αρχειων την άμεση προβολή των αλλαγών που πραγματοποιούσα καθώς επίσης και την συγγραφή "όμορφου" κώδικα αφού παρέχονται λειτουργικότητες όπως στοίχιση των εντολών αποφεύγοντας έτσι συχνά συντακτικά λάθη.


## Μέθοδος και τεχνικές ανάπτυξης
Οι μέθοδοι και οι τεχνικές ανάπτυξης που ακολούθησα για την υλοποίηση της εργασίας οπτικοποίησης δεδομένων είναι οι εξής : 
### Βήμα 1
Αρχικά, μελέτησα προηγούμενες παρόμοιες εργασίες οπτικοποίησης δεδομένων του μαθήματος βλέποντας την μεθοδολογία με την οποία γίνεται προσθήκη αρχείων και κώδικα. Στην συνέχεια, διάβασα απο διάφορα site την σύνταξη της κάθε γλώσσας καθώς ήταν απαραίτητο για την κατανόηση του κώδικα που έπρεπε να προσθέσω έιτε ήταν html είτε css είτε javascript. Τα site στα οποία απευθύνθηκα περισσότερο ειναι τα εξής : 
   
* w3school
* academy of code
* wlearn
* javascript.com

### Βήμα 2
Εφόσον τελείωσα την μελέτη σχετικά με προηγούμενες παρόμοιες εργασίες και την εκμάθηση της βασικής σύνταξης των γλωσσών ξεκίνησα την αναζήτηση σχετικά με τα ερωτήματα της εργασίας. Ειδικότερα : 
#### ΠΑΡΑΔΟΤΕΟ 1
α. Για το πρώτο ερώτημα βρήκα ότι οι αλλαγές των χρωμάτων στο κάθε γράφημα γίνεται απο το javascript αρχείο του στο οποίο πρέπει να αλλάξεις τους δεαεξαδικούς αριθμούς όπου ο κάθε ένας αντιπροσωπεύει ένα χρώμα. Έτσι λοιπόν τα αρχεία στα οποία άλλαξα τα χρώματα ηταν τα :

* script_1
* script_2
* script_3

β. Για το δεύτερο ερώτημα σχετικά με την αντικατάσταση στις διεπαφές των κουμπιών αφού κατάλαβα ότι η αλλαγή γίνεται απο το αρχείο style.css βρήκα το μπλόκ κώδικα που τροποποιεί τις διεπαφές στα κουμπιά και άλλαξα το περίγραμμα τους το χρώμα τους και το είδος του δείκτη του ποντικιού όταν βρίσκεται επάνω σε ένα απο αυτά.

γ. Για το τρίτο ερώτημα έκανα έρευνα για το πώς μπορώ να βάλω να ακούγεται ήχος όταν το ποντίκι βρίσκεται επάνω απο οποιαδήποτε επιλογή στο μενού. Βρήκα μια συνάρτηση javascript την οποία ανέβασα στο github και την καλείς απο το αρχείο index.html. Μαζί με την συνάρτηση ανέβασα και ένα mp3 αρχείο το οποίο ακούγεται κάθε φορά που το ποντίκι διέρχεται πάνω απο μία επιλογή στο μενού. Για να επιτευχθούν αυτές οι λειτουργίες τοποθέτησα την ιδιότητα onmouseover στα στοιχεία του μενού με την οποία καλείτε και η συνάρτηση.

δ. Για το τέταρτο ερώτημα βρήκα ότι υπάρχει η βιβλιοθήκη responsive voice την οποία έκανα include στο index.html αρχείο. Αφού την έκανα include χρησιμοποίησα τις ιδιότητες onmouseover και onmouseleave με τις οποίες καλούσα τις συναρτήσεις : 

* responsiveVoice.speaκ();
* responsiveVoice.cancel();

ε. Για το πέμπτο ερώτημα έκανα έρευνα σχετικά με τους τρόπους που μπορεί να γίνει μία ιστοσελίδα responsive με στόχο να προσαρμόζεται σε κάθε οθόνη. Κατάφερα να προσθέσω κώδικα στο αρχείο index.html ώστε να γίνουν responsive τα κείμενα της σελίδας και το μενού αλλά δεν κατάφερα να κάνω και τα γραφήματα responsive.

#### Παραδοτέο 2
α. Για το πρώτο ερώτημα μετά απο έρευνα κατάφερα να βρώ κάποια scripts τα οποία πρόσθεσα στο index.html στόχος τον οποίον είναι να φαίνεται κάθε φορά μόνο ένα απο τα διαγράμματα στην σελίδα. Με την τοποθέτηση της ιδιότητας onlick στα στοιχεία του μενού καλούσα την συνάρτηση showhide(); η οποία εμφάνιζε και έκρυβε τα αντίστοιχα διαγράμματα κάθε φορά.

β. Δεν κατάφερα να υλοποιήσω το δεύτερο ερώτημα και θεωρώ ότι ήταν αυτό το οποίο είχε τον μεγαλύτερο βαθμό δυσκολίας απο αυτή την εργασία.

γ. Για το τρίτο ερώτημα αρχικά πρόσθεσα στο μενού της σελίδας ένα κουμπί με όνομα "3 new charts" το οποίο οδηγεί τον χρήστη σε μία νέα σελίδα στην οποία υπάρχουν τα 3 νέα γραφήματα απο την d3.js. Τον κώδικα των γραφημάτων τον βρήκα στο codepen και στην συνέχεια για την εύρεση στατιστικών απευθύνθηκα στην σελίδα της ΕΛΣΤΑΤ. Στην συνέχεια, έκανα την σύνδεση των στατιστικών με τον κώδικα των γραφημάτων και εφάρμοσα responsive design(όχι στα διαγράμματα) στην σελίδα ώστε να φαίνεται σωστά σε οποιαδήποτε οθόνη. 

## Aποτελέσματα με λεζάντες σε ενδεικτικές οθόνες και animated gif
### Παραδοτέο 1
- [x] Αλλάξτε τα χρώματα στα 3 γραφήματα. 
#### Κώδικας πρώτου γραφήματος :
![πρώτο γράφημα](xromata1.png)

#### Πρώτο γράφημα :
![πρώτο γράφημα](diagramma1.png)
#### Κώδικας δεύτερου γραφήματος :
![δεύτερο γράφημα](xromata2.png)

#### Δεύτερο γράφημα :
![δεύτερο γράφημα](diagramma2.png)
#### Κώδικας τρίτου γραφήματος :
![τρίτο γράφημα](xromata3.png)

#### Τρίτο γράφημα :
![τρίτο γράφημα](diagramma3.png)
- [x] Αντικαταστήστε τις διεπαφές στα "κουμπιά" του 2ου και 3ου γραφήματος με άλλες της επιλογής σας. 
#### Κώδικας κουμπιών
![κώδικας κουμπιών](koumpia.png)
#### Κουμπιά πρώτου γραφήματος
![Κουμπιά πρώτου γραφήματος](koumpia1.png)
#### Κουμπιά δεύτερου γραφήματος
![Κουμπιά δεύτερου γραφήματος](koumpia2.png)
- [x] Όταν το ποντίκι διέρχεται επάνω από κάθε επιλογή του menu στην κορυφή της σελίδας, να ακούγεται κάποιος ήχος της επιλογής σας. 
#### Κώδικας που προστέθηκε
![κώδικας για το mouseover](hxos1.png)
![κώδικας για το mouseover](hxos2.png)
![κώδικας για το mouseover](hxos3.png)
![κώδικας για το mouseover](hxos4.png)
- [x] Όταν το ποντίκι διέρχεται πάνω από κάποια πρόταση/κείμενο της σελίδας ή περιοχή που περιλαμβάνει γραπτή πληροφορία (π.χ. κάποιο τμήμα γραφήματος), να ακούγεται αυτόματα η αφήγηση του κειμένου (text-to-speech).
#### Κώδικας που προστέθηκε
![κώδικας για το mouseover](responsive1.png)
![κώδικας για το mouseover](responsive2.png)
- [x] Εφαρμόστε responsive design στη σελίδα και κυρίως στο αρχικό menu έτσι ώστε να προσαρμόζεται σε οθόνες διαφορετικών διαστάσεων (π.χ. Bootstrap).
#### Κώδικας που προστέθηκε για responsive design
![responsive](responsive5.png)
#### Το αποτέλεσμα :
![responsive](responsive.gif)
### Παραδοτέο 2
- [x] Τροποποιήστε τον κώδικα και το μενού της εφαρμογής έτσι ώστε κάθε στιγμή να είναι εμφανές μόνο ένα από τα 3 γραφήματα, παραμένοντας πάντα στη σελίδα index.html.
#### Κώδικας που προστέθηκε
![Κώδικας που προστέθηκε](showhide1.png)
![Κώδικας που προστέθηκε](showhide.png)
![Κώδικας που προστέθηκε](showhide2.png)
#### Το αποτέλεσμα :
![το αποτέλεσμα](diagrammata.gif)
- [ ] Αντικαταστήστε το κάθε ένα από τα 3 γραφήματα με κάποιο άλλο διαδραστικό γράφημα της D3js. (Δεν το έκανα)
- [x] Σε μια καινούργια σελίδα, να τοποθετήσετε αντίστοιχα 3 νέα διαδραστικά γραφήματα D3js της επιλογής σας, τα οποία θα οπτικοποιούν καινούργια στατιστικά δεδομένα που θα βρείτε από κάποια επίσημη στατιστική αρχή (π.χ. ΕΛΣΤΑΤ, Eurostat κ.λπ.).
#### 3 νέα διαδραστικά γραφήματα D3js σε μια καινούργια σελίδα :
![3 νέα διαδραστικά γραφήματα D3js σε μια καινούργια σελίδα](newcharts.gif)

## Συμπεράσματα
Τα συμπεράσματα απο την εκπόνηση αυτής της εργασίας ήταν πολλά. Αρχικά, μελέτησα τις τρεις πιο διαδεδομένες γλώσσες για προγραμματισμό στο web και απέκτησα μια σχετική εμπειρία σε ότι έχει να κάνει με οπτικοποίηση δεδομένων. Είναι πολύ σημαντικό στις μέρες μας να μπορούμε να απεικονήσουμε όλα τα στατιστικά που δημιουργούνται απο την καθημερινότητα με σκοπό την εξαγωγή σημαντικών συμπερασμάτων και μέσω αυτής της εργασίας μπόρεσα να καταλάβω ένα κομμάτι του τομέα που ασχολείται με αυτό επαγγελματικά. Επιπλέον, μέσω αυτής της εργασίας έμαθα να ψάχνω σε βάθος στο διαδίκτυο με στόχο να απαντήσω στα ερωτήματα και αυτό είναι ωφέλιμο καθώς αποτελεί ένα σημαντικό επαγγελματικό εφόδιο. Σημαντικό είναι οτι έμαθα την βασική σύνταξη και λογική απο τρεις νέες γλώσσες οι οποίες μπορούν να χρησιμοποιηθούν σε πάρα πολλες εφαρμογές του web. Τέλος, έχω αποκτήσει μια σχετική εξοικείωση με το github το οποίο αποτελεί εργαλείο για χιλιάδες προγραμματιστές καθημερινά και αποτελεί σίγουρα ένα σημαντικό εφόδιο για όποιον ασχολείται με τον τομέα της πληροφορικής.

## Βιβλιογραφία και σύνδεσμοι σε σχετικές εργασίες
* [ΕΛΣΤΑΤ](http://www.statistics.gr/)
* [w3school](https://www.w3schools.com/default.asp)
* [javascript](https://www.javascript.com/)
* [wlearn](https://www.wlearn.gr/index.php/topmenu-118)
* [Academy of Code](https://www.academy-of-code.com/el/)
* [CodePen](https://codepen.io/)
* [Στατιστικά πρώτου γραφήματος ΕΛΣΤΑΤ](https://www.statistics.gr/el/statistics/-/publication/SPO09/2017)
* [Κώδικας πρώτου γραφήματος CodePen](https://codepen.io/belkins/pen/KNOapK)
* [Στατιστικά δεύτερου γραφήματος ΕΛΣΤΑΤ](http://www.statistics.gr/el/statistics?p_p_id=documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN&p_p_lifecycle=2&p_p_state=normal&p_p_mode=view&p_p_cacheability=cacheLevelPage&p_p_col_id=column-2&p_p_col_count=4&p_p_col_pos=1&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_javax.faces.resource=document&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_ln=downloadResources&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_documentID=345824&_documents_WAR_publicationsportlet_INSTANCE_qDQ8fBKKo4lN_locale=el)
* [Κώδικας δεύτερου γραφήματος CodePen](https://codepen.io/alingam/pen/rVjgEj)
* [Στατιστικά τρίτου γραφήματος ΕΛΣΤΑΤ](http://www.statistics.gr/documents/20181/44f27645-626c-4968-92c7-aa47a6c66c92)
* [Κώδικας τρίτου γραφήματος CodePen](https://codepen.io/jgarciaruiz/pen/WjMdVw)
* [responsive voice](https://responsivevoice.org/)
* [d3js](https://d3js.org/)
