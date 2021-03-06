# Creepy-Voices
ΔΠΜΣ "Τέχνες και Τεχνολογίες του Ήχου" 
Μάθημα :Μουσική Πληροφορική
Τελική εργασία
Τίτλος: Creepy voices
Διάρκεια: ~ 9':48"

Στόχος της παραπάνω εργασίας ήταν η κατανόηση της γλώσσας προγραμματισμού στο Supercollider μέσω συγκεκριμένων τεχνικών τις οποίες διδάχθηκα στο μάθημα της ΄’Μουσικής Πληροφορικής’’ και μέσω των videos του Eli Fieldsteel (SuperCollider Tutorial: 0. Introduction - Tutorial: 7) και η χρήση αυτής ως εργαλείο δημιουργίας και επεξεργασίας ήχων, εφέ και σύνθεσης μουσικών κομματιών.
Η βασική ιδέα ήταν η σύνθεση ενός μουσικού κομματιού χρησιμοποιώντας τις τεχνικές που διδάχθηκα καθώς και παραδείγματα κώδικα (αυτούσια ή παραμετροποιημένα) τα οποία αναζήτησα στην ιστοσελίδα sccode.org.

Τα βασικά στοιχεία αυτής της μουσικής σύνθεσης είναι η δημιουργία ανθρώπινης φωνής, drones, αέρα και stretching (Paul Stretching code). Αρχικά χρησιμοποίησα παραδείγματα από κώδικα τα οποία όπως προανέφερα βρήκα online στην ιστοσελίδα sccode.org ορισμένα από τα οποία παραμετροποίησα σύμφωνα με τις ανάγκες της σύνθεσης μου. Τα περισσότερα από τα παραδείγματα αυτά ανήκουν στην κατηγορία Synths.

Στόχος μου ήταν να δημιουργήσω μία μουσική σύνθεση βασισμένη στον αυτοσχεδιασμό με σκοπό να υπάρχει η δυνατότητα να αναπαραχθεί live (live coding) διαφοροποιώντας μόνο τις εντολές. Για το λόγο αυτό έβαλα μεταβλητές σε όλα τα παραδείγματα (x, y, z, e…) έτσι ώστε να έχω τη δυνατότητα ανά πάσα στιγμή να τα εμφανίσω στη σύνθεση μου.
Αυτοσχεδίασα κυρίως με τις εντολές .stop; , .free; , .wait(); , .play; και .release;. Τέλος για τις ανάγκες της εργασίας δημιούργησα ένα fork στο οποίο έβαλα τη σύνθεση μου με σκοπό να αναπαραχθεί αυτόματα.

Τα προβλήματα που αντιμετώπισα ήταν ότι οι εντολές ορισμένες φορές δεν λειτουργούσαν πάντα σε τυχαίες στιγμές παρόλο που δεν υπήρχαν συντακτικά λάθη στον κώδικα. Επίσης προσπάθησα στις φωνές να δημιουργήσω fade out με την εντολή x.xstop(); για μεταβλητή x και ενώ κατάφερα να πετύχω το fade out, για κάποιο λόγο ο ήχος δεν κατάφερα να τερματίσω εντελώς την αναπαραγωγή του ήχου. Τότε δοκίμασα μετά την παραπάνω εντολή να χρησιμοποιήσω την εντολή x.xtop; αλλά και πάλι δεν λειτούργησε.

Τέλος θα ήθελα να ευχαριστήσω τον καθηγητή μου Κ. Ιωάννη Ζάννο για τις γνώσεις τις οποίες μου πρόσφερε, τις ιδέες που μου έδωσε και τη βοήθεια του για την υλοποίηση της παραπάνω εργασίς καθώς και τους συμφοιτητές μου (Σοφία Εμμανουηλίδου, Αγάπη Ζάρδα, Άκη Κέμο, Γιάννη Μπαξεβάνη, Ηλία Μπαγλάνη, Νίκο Κανελλάκη, Γιάννη Λέφα, Βασίλη Κατσάκο, Δημήτρη Τσακηρίδη και Βαγγέλη Γιασιτζή) οι οποίοι ήταν πρόθυμοι να με βοηθήσουν σε όσα προβλήματα μου προέκυψαν.

Διαδικτυακές πηγές  
“Kepler 22-b Atmosphere.” Sccode.Org, wind whirles, sccode.org/1-4mJ. Accessed 4 Feb. 2021.

 “Alone in the Storm.” SuperCollider Code, grirgz, sccode.org/1-1WS. Accessed 3 Feb. 2021.
 
“Entities.” SuperCollider Code, grirgz, sccode.org/1-51P. Accessed 3 Feb. 2021.

“Esoteric Tweet.” SuperCollider Code, all n4tural, sccode.org/1-D. Accessed 2 Feb. 2021.

“Paulstretch for SuperCollider.” SuperCollider Code, jpdrecourt, sccode.org/1-5d6. Accessed 5 Feb. 2021.

“Re: Silly Voice.” SuperCollider Code, wondersluyter, sccode.org/1-4Vq. Accessed 13 Jan. 2021.
