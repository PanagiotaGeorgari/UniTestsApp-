## Gitlab Link 
https://gitlab.com/sweng-group/2024-25/team04
 *Ομάδα 4 - Εφαρμογή διαγωνισμάτων πολλαπλής επιλογής*

## *Σύντομη περιγραφή απαιτήσεων*

Το σύστημα θα υποστηρίζει την μελέτη μαθημάτων ενός πανεπιστημιακού τμήματος μέσω διαγωνισμάτων πολλαπλής επιλογής και σωστού-λάθους.Ο καθηγητής δημιουργεί τα ερωτήματα και οι φοιτητές τα συμπληρώνουν.

* Ο **καθηγητής** έχει την δυνατότητα να:
  
  * κάνει εγγραφή στην εφαρμογή
  * κάνει είσοδο στην εφαρμογή
  * δημιουργεί μαθήματα του τμήματος (ένα ή περισσότερα)
  * δημιουργεί τράπεζα ερωτήσεων για τα μαθήματα  που έχει δημιουργήσει παρέχοντας τρία επίπεδα δυσκολίας ( χαμηλό ,μεσαίο ,υψηλό)
  * παρακολουθεί την επίδοση των φοιτητών 

* Ο **φοιτητής** έχει την δυνατότητα να:
  * κάνει εγγραφή στην εφαρμογή
  * κάνει είσοδο στην εφαρμογή
  * συμπληρώσει διαγωνίσματα του μαθήματος που ενδιαφέρεται να εξασκηθεί σε αυτό επιλέγοντας πλήθος ερωτήσεων και τον βαθμό δυσκολίας τους.
    

* Το **σύστημα** επιλέγει τυχαία  ερωτήματα από την τράπεζα λαμβάνοντας υπόψιν τις ερωτήσεις που έχει απαντήσει λάθος ο φοιτητής μέχρι στιγμής ή και καθόλου προκειμένου να τις εμφανίσει.



* Το **σύστημα** με βάση το ποσοστό των  ερωτήσεων που έχουν απαντηθεί σωστά κατατάσσει τους φοιτητές και εμφανίζει τα αποτελέσματα στον καθηγητή.

## *Διάγραμμα περιπτώσεων χρήσης*



![Εναλλακτικό κείμενο](docs/images/usecase_digramr2.png "περιγραφή") 

# Έχουμε τις εξής παριπτώσεις χρήσης
1. [ΕΙΣΟΔΟΣ ΣΤΗΝ ΕΦΑΡΜΟΓΗ](docs/markdown/use_case_login_in_app.md)
2. [ΕΓΓΡΑΦΗ ΣΤΗΝ ΕΦΑΡΜΟΓΗ ΩΣ ΚΑΘΗΓΗΤΗΣ](docs/markdown/use_case_register_as_professor.md)
3. [ΔΙΑΧΕΙΡΙΣΗ ΜΑΘΗΜΑΤΟΣ](docs/markdown/use_case_subject_management.md)
4. [ΔΙΑΧΕΙΡΙΣΗ ΤΡΑΠΕΖΑΣ ΕΡΩΤΗΣΕΩΝ](docs/markdown/usecase_questions_management.md)
5. [ΕΓΓΡΑΦΗ ΣΤΗΝ ΕΦΑΡΜΟΡΓΗ ΩΣ ΦΟΙΤΗΤΗΣ](docs/markdown/usecase_register_as_student.md)
6. [ΤΥΧΑΙΑ ΕΠΙΛΟΓΗ ΕΡΩΤΗΣΕΩΝ](docs/markdown/usecase_random_questions.md)
7. [ΠΑΡΑΚΟΛΟΥΘΗΣΗ ΕΠΙΔΟΣΗΣ ΦΟΙΤΗΤΩΝ](docs/markdown/usecase_success.md)
8. [ΣΥΜΠΛΗΡΩΣΗ ΔΙΑΓΩΝΙΣΜΑΤΟΣ](docs/markdown/usecase_test_creation.md) 

# Με τις σημαντικότερες από αυτες
1. [ ΕΓΓΡΑΦΗ ΣΤΗΝ ΕΦΑΡΜΟΓΗ ΩΣ ΚΑΘΗΓΗΤΗΣ](docs/markdown/use_case_register_as_professor.md)
2. [ΔΙΑΧΕΙΡΙΣΗ ΤΡΑΠΕΖΑΣ ΕΡΩΤΗΣΕΩΝ](docs/markdown/usecase_questions_management.md)
3. [ΤΥΧΑΙΑ ΕΠΙΛΟΓΗ ΕΡΩΤΗΣΕΩΝ](docs/markdown/usecase_random_questions.md)
4. [ΣΥΜΠΛΗΡΩΣΗ ΔΙΑΓΩΝΙΣΜΑΤΟΣ](docs/markdown/usecase_test_creation.md)
   

# Μη λειτουργικές απαιτήσεις
  [ΜΗ ΛΕΙΤΟΥΡΓΙΚΕΣ ΑΠΑΙΤΗΣΕΙΣ](docs/markdown/non_functionalrequirements.md)


# Διαγράμματα δραστηριότητας για τις σημαντικότερες περιπτώσεις χρήσης
1. ![ΕΓΓΡΑΦΗ ΣΤΗΝ ΕΦΑΡΜΟΓΗ ΩΣ ΚΑΘΗΓΗΤΗΣ](docs/images/r2_register_as_prpf_act.png)
2. ![ΔΙΑΧΕΙΡΙΣΗ ΤΡΑΠΕΖΑΣ ΕΡΩΤΗΣΕΩΝ](docs/images/r2_quest_manag_act.png)
3. ![ΤΥΧΑΙΑ ΕΠΙΛΟΓΗ ΕΡΩΤΗΣΕΩΝ](docs/images/random_choice_of_questions_act.png)
4. ![ΣΥΜΠΛΗΡΩΣΗ ΔΙΑΓΩΝΙΣΜΑΤΟΣ](docs/images/r2_test_creation_act3.png)
   ![ΣΥΜΠΛΗΡΩΣΗ ΔΙΑΓΩΝΙΣΜΑΤΟΣ](docs/images/r2_test_creation_act1.png)
   ![ΣΥΜΠΛΗΡΩΣΗ ΔΙΑΓΩΝΙΣΜΑΤΟΣ](docs/images/r2_test_creation_act2.png)




# Το Διάγραμμα πεδίου 
![διαγραμμα πεδίου](docs/images/r2_field.png)


# Το Διαγραμμα κλασεων
![διαγραμμα κλασεων ](docs/images/r3_classdiagram_final.png)


# Τα διαγράμματα ακολουθίας για την περιγραφή της δυναμικής όψης της λογικής του πεδίου 
![διαγραμμα ακολουθιας ](docs/images/sd_checkAns.png)
![διαγραμμα ακολουθιας ](docs/images/sd_choose_random_all_questions.png)
![διαγραμμα ακολουθιας ](docs/images/sd_delete_subject.png)
![διαγραμμα ακολουθιας ](docs/images/sd_setStatequestion.png)
![διαγραμμα ακολουθιας ](docs/images/sd_updateScore.png)
![διαγραμμα ακολουθιας ](docs/images/sd_update_subject.png)

# Coverage
![coverage ](docs/images/coverage.png)
# Διαγράμματα κλάσεων και ακολουθίας που αφορούν τη σχεδίαση όλων των αρμοδιοτήτων του λογισμικού (R4)
![διαγραμμα ακολουθιας ](docs/images/sd_createprofessoraccount.png)
![διαγραμμα ακολουθιας ](docs/images/sd_verificationLogin.png)
![διαγραμμα ακολουθιας ](docs/images/sd_createsubject.png)
![διαγραμμα ακολουθιας ](docs/images/sd_searchQuestion.png)
![διαγραμμα κλασεων ](docs/images/class_diagramloginActivity.png)
![διαγραμμα κλασεων ](docs/images/class_diagramCreatesubject.png)
![διαγραμμα κλασεων ](docs/images/class_diagramcreateQuestion.png)
![διαγραμμα κλασεων ](docs/images/class_diagramsingUpProfessorActivity.png)


# Δημιουργήθηκε απο
!Παναγιωτα Γεωργαρη (5ο εξάμηνο)
!Γεωργία Εμμανουέλα Μαρίνου (5ο εξάμηνο)


   











