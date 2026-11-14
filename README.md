# madrasa-manager-updates

Mises à jour de Madrasa Manager (installateurs uniquement — aucun code source).

Le logiciel installé chez les clients vérifie ce dépôt au démarrage et toutes les 4 heures,
télécharge la dernière version publiée dans **Releases** et propose de l'installer.

## Vidéos tutoriels (tutorials.json)

Tous les logiciels installés lisent le fichier **tutorials.json** (au démarrage, puis toutes les 6 heures).
Mettez-y le lien YouTube de chaque vidéo : tous les centres les voient dans **Tutoriels** et avec le bouton « ▶ Tutoriel ».

Pour modifier : ouvrez `tutorials.json`, cliquez sur le crayon ✏️ (Edit), collez les liens entre les guillemets, puis **Commit changes**.
Exemple : `"payment": "https://youtu.be/AbCdEfGh123",`
Un lien vide (`""`) = pas encore de vidéo. Les liens doivent commencer par https://.

| Clé | Tutoriel |
|---|---|
| `first_setup` | Installation et réseau |
| `school_identity` | Nom et logo de l’école |
| `levels_subjects` | Niveaux et matières |
| `users` | Comptes utilisateurs |
| `add_student` | Inscrire un élève |
| `students_list` | Liste et recherche d’élèves |
| `student_profile` | Fiche élève |
| `attendance` | Faire l’appel |
| `teachers` | Ajouter un enseignant |
| `groups` | Créer un groupe |
| `group_print` | Imprimer la liste ou la feuille d’appel |
| `timetable` | Planning des séances |
| `payment` | Encaisser un paiement |
| `debts` | Dettes et « Tout régler » |
| `receipt_format` | Format des reçus |
| `cancel_slip` | Annuler un bon |
| `monthly` | Forfait mensuel |
| `discounts` | Réductions (fratrie, gratuit…) |
| `reminders` | Rappels de séance |
| `absences` | Avertir des absences |
| `burst` | Envoi en rafale « Tout envoyer » |
| `broadcast` | Liste de diffusion |
| `announce` | Annoncer une séance (ajout, report, annulation) |
| `debt_reminders` | Rappels d’impayés du mois |
| `templates` | Modèles de messages |
| `settlement` | Payer un enseignant |
| `cash` | Caisse et retraits |
| `expenses` | Dépenses du centre |
| `dashboard` | Tableau de bord du directeur |
| `reports` | Rapport du mois et export Excel |
| `backup` | Sauvegardes et restauration |
| `ext_backup` | Copie automatique sur clé USB / Google Drive |
| `sync_pc` | PC du secrétariat synchronisé |
| `audit` | Journal d’audit |
| `forgot_password` | Mot de passe oublié |
| `licence` | Licence et activation |
| `updates` | Mises à jour automatiques |
| `autostart` | Démarrer avec Windows |
