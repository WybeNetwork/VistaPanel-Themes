# Καλωσορίσατε στα θέματα για το VistaPanel (VistaPanel Themes)
Το πρότζεκτ περιέχει κάποια νέα θέματα για το VistaPanel, ένα περιβάλλον διαχείρισης Web Hosting δημιουργημένο από την iFastNet.

Στα θέματα περιλαμβάνονται τα δημοφιλή προεπιλεγμένα θέματα του PaperLantern (εκτός του Retro), κάποια επιπλέον τα οποία πρωτοεμφανίστηκαν την περίοδο της απόσυρσης του cPanel X3, και κάποια ειδικά σχεδιασμένα για το VistaPanel.

# Εγκατάσταση
Πρώτα, πρέπει να κατεβάσετε τους φακέλους και να τους τοποθετήσετε στην ιστοσελίδα σας. 

Σε περίπτωση που δεν θέλετε/μπορείτε να το κάνετε, τα θέματα είναι διαθέσιμα μέσω ενός δικού μας CDN, απλά αντικαταστήστε το `mydomain.com` κομμάτι του κώδικα με `vpt.cdn.wybenetwork.com`.

# Οδηγίες χρήσης και τοποθέτησης στο VistaPanel
Πρέπει να αντιγράψετε τον κώδικα που δίνεται παρακάτω στις "header" και "footer" τοποθεσίες των διαφημίσεων (control panel adverts), οι οποίες βρίσκονται στον πίνακα ελέγχου MyOwnFreeHost σας.

Ο κώδικας παρακάτω χρησιμοποιείται ως παράδειγμα, θα πρέπει να αντικαταστήσετε το "theme-name" σε αυτόν με το όνομα του θέματος που επιθυμείτε να χρησιμοποιήσετε.
You can find it's name written at the folder, and it is **case sensitive**.

## Για τα κανονικά θέματα 
```
<link rel="stylesheet" type="text/css" href="https://mydomain.com/theme-name/icon_spritemap.css">
<link rel="stylesheet" type="text/css" href="https://mydomain.com/theme-name/styles.css">
```

## Για τα θέματε Lite
```
<link rel="stylesheet" type="text/css" href="https://mydomain.com/theme-name/styles.css">
```

## Για τα θέματα LightSpace
```
<link rel="stylesheet" type="text/css" href="https://mydomain.com/theme-name/panel.css">
```  

Μόλις το κάνετε, θα εμφανίζεται στο panel. Συγχαρητήρια, μόλις αλλάξατε θέμα!  

# Κύρια ιστοσελίδα
Η ιστοσελίδα μας βρίσκεται στο https://wybenetwork.com/. **(Υπό Κατασκευή)**

Το CDN για τα θέματα είναι στο https://vpt.cdn.wybenetwork.com/.

Αναλυτικές οδηγίες βρίσκονται στο https://docs.wybenetwork.com/ **(Χωρίς Υποστήριξη Ελληνικών)**. Προσπαθήσαμε να το κάνουμε όσο πιο απλό :smile:

Discord:
https://discord.gg/zArW8kC

# Πνευματικά δικαιώματα και εύσημα
Copyright 2019-2021 Wybe Network. Ορισμένα δικαιώματα διατηρούνται, δείτε την [άδεια χρήσης](LICENSE.md) για περισσότερες λεπτομέρειες.

Τα εύσημα για τα θέματα ανήκουν στους:

[MAHOfficial](https://github.com/mahofficial) για την παροχή των cPanel και Gradient Blue themes

[Arcenas090](https://github.com/arcenas090) για τα Gradient Purple και Gradient Green Themes

[yagizhan49](https://github.com/yagizhan49) για το Gradient Red Theme

[Adam](https://github.com/adam/) για τα θέματε από το [Paper Lantern Customizations](https://github.com/CpanelInc/Paper_Lantern_Customizations)  

[einet](https://github.com/eiinet) για τα Light-Lite και Dark-Lite themes

[WoltBase](https://www.woltbase.com) για το δωρεάν Christmas theme
