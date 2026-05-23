Diagrammes UML — fichiers à déposer dans ce dossier
==================================================

Schéma d'architecture (un seul fichier) :
  architecture.png     — Schéma en couches (gauche→droite), style dessin technique
  architecture.mmd       — Source Mermaid à coller sur mermaid.live

Diagrammes de séquence :

  seq_auth.png         — Inscription et connexion client
  seq_reservation.png  — Recherche 3D, réservation et paiement
  seq_whatsapp.png     — Concierge WhatsApp / IA
  seq_checkin.png      — Check-in et check-out réception
  seq_backoffice.png   — Back-office administrateur

Recommandation export (diagrammes de séquence) :
  - Format paysage (A4 horizontal) ou ratio large (ex. 1600×900)
  - Police lisible, lifelines rapprochées, peu d'espace vide vertical
  - Dans Enterprise Architect : Diagram → Layout → compact
  - Hauteur max ~900 px pour tenir sur une page PDF avec la légende

Le rapport redimensionne automatiquement (max 68 % de la hauteur de page).

Après ajout des images : pdflatex main.tex (deux passes)
