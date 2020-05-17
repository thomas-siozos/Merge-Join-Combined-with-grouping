# Merge-Join-Combined with grouping

Στόχος του project είναι να συνενώσει τα αρχεία που παίρνει ως εισόδους
με βάση το πρώτο πεδίο τους το οποίο είναι ένας μοναδικός identifier για κάθε
τίτλο. Για κάθε τίτλο που εμφανίζεται και στα δύο αρχεία εισόδου, εμφανίζονται
τα πεδία identifier και primaryTitle που βρίσκονται στο αρχείο title.basics.tsv
και για κάθε εναλλακτικό τίτλο του στο title.akas.tsv, τον εναλλακτικό τίτλο
και σε παρένθεση τις περιοχές στις οποίες χρησιμοποιείται ο εναλλακτικός τίτλος.
Το αποτέλεσμα είναι ένα tab seperated αρχείο εξόδου. Το project διαβάζει τα
αρχεία και βγάζει αποτελέσματα χωρίς να φορτώσει όλα τα δεδομένα στην μνήμη.

## Data

Τα δεδομένα χρησιμοποιούνται από την βάση της IMDB (Internet Movie Database).<br/>
[link](https://www.imdb.com/interfaces/)

## Running the project

Τα data πρέπει να βρίσκονται σε φάκελο "data". Μέσα στον φάκελο τους φακέλους:
* title.akas.tsv
* title.basics.tsv<br/>
Οι οποίοι βρίσκονται στα δεδομένα της βάσης.

## Output File

![GitHub Logo](result.png)
Format: ![Alt Text](url)
