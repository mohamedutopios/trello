### Tableau Trello : Recrutement RH Complet

#### Scénario :

L'entreprise TechInnov recrute un développeur Full Stack. Le responsable RH, Sarah, coordonne le recrutement via Trello avec l'aide du directeur technique (Marc) et de la chargée de recrutement (Lina). Le processus commence le 1er juin et doit être finalisé avant le 15 juillet.

#### Configuration du tableau :

##### Listes :

1. **Candidatures reçues** (du 1er juin au 10 juin)

   * Cartes avec CV joints.
   * Étiquettes : compétences clés (JavaScript, Java, Angular, React).
   * Checklist : Validation des prérequis (expérience, diplôme requis).
   * Automatisation Butler : Notification Slack à Lina dès ajout d'une nouvelle candidature.

2. **Pré-sélection** (du 11 juin au 15 juin)

   * Cartes déplacées automatiquement après validation initiale.
   * Checklist : vérification du parcours, prise de rendez-vous pour entretien téléphonique.
   * Date d'échéance automatique fixée à 48 heures après déplacement dans la liste.

3. **Entretien Téléphonique** (du 16 juin au 22 juin)

   * Membres assignés automatiquement : Lina.
   * Checklist : questions techniques préliminaires, intérêt du candidat, disponibilité.
   * Date d'échéance automatique fixée à 3 jours après entrée dans la liste.
   * Automatisation Butler : Rappel automatique 24h avant l'entretien téléphonique.

4. **Entretien Technique** (du 23 juin au 30 juin)

   * Membres assignés automatiquement : Marc.
   * Checklist : Test technique envoyé, résultats reçus, analyse des résultats.
   * Automatisation Butler : Envoi automatique du test technique dès que la carte entre dans la liste.
   * Commentaires utilisés pour feedback technique détaillé.

5. **Entretien RH final** (du 1er juillet au 8 juillet)

   * Membres assignés automatiquement : Sarah.
   * Checklist : culture d'entreprise, prétentions salariales, références.
   * Power-Up : Calendrier intégré pour gérer les rendez-vous.
   * Automatisation Butler : Calendrier mis à jour automatiquement dès fixation de l'entretien.

6. **Offre faite** (du 9 juillet au 12 juillet)

   * Checklist : Proposition salariale envoyée, négociations éventuelles.
   * Automatisation Butler : Notification Slack à Sarah si la carte reste plus de 48h sans déplacement.

7. **Candidature acceptée / refusée** (date limite : 15 juillet)

   * Étiquettes spécifiques (vert pour accepté, rouge pour refusé).
   * Automatisation Butler : Archiver automatiquement les cartes après 7 jours dans cette liste.

#### Exemple concret :

* **Candidat : Julien Moreau**

  * Carte créée le 2 juin dans « Candidatures reçues ».
  * Étiquettes : JavaScript, React.
  * CV joint.
  * Lina reçoit une notification Slack immédiatement.
  * Le 11 juin, la carte est automatiquement déplacée vers « Pré-sélection » après vérification initiale par Lina.
  * Une date d’échéance automatique est ajoutée pour le 13 juin.
  * Lina effectue l’entretien téléphonique le 16 juin, carte déplacée vers « Entretien Technique ».
  * Marc reçoit automatiquement une notification et le test technique est envoyé automatiquement.
  * Résultats positifs reçus le 27 juin, commentaire ajouté par Marc.
  * Carte transférée automatiquement vers « Entretien RH final » le 1er juillet.
  * Sarah réalise l’entretien final le 4 juillet.
  * Offre envoyée le 9 juillet, carte déplacée vers « Offre faite ».
  * Julien accepte l’offre le 11 juillet, carte déplacée vers « Candidature acceptée » avec une étiquette verte.

#### Power-Ups utilisés :

* **Calendrier** : visualisation des échéances et des entretiens.
* **Google Drive** : intégration des tests techniques et documents liés aux candidats.
* **Slack** : notifications automatiques vers le canal de recrutement pour chaque déplacement de carte significatif.

#### Automatisations Butler :

* Notifications Slack automatiques lors de mouvements importants des cartes.
* Attribution automatique des membres aux étapes spécifiques.
* Déplacements automatiques des cartes selon les critères définis.
* Dates d'échéance automatiques et rappels.

#### Bonnes pratiques :

* Utiliser systématiquement les checklists pour un suivi précis des étapes.
* Attribuer clairement chaque carte à un responsable.
* Employer des étiquettes de couleur pour une identification rapide.
* Joindre les fichiers directement aux cartes pour un accès facilité.
* Utiliser les commentaires pour fournir un feedback continu et structuré.
