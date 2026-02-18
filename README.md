Cette application représente comment le  multi-pages fonctionne. Il montre comment passer d'un écran à l'autre et comment organiser des données complexes

<img width="1920" height="1080" alt="Screenshot (119)" src="https://github.com/user-attachments/assets/02905257-f621-4392-94b5-2c9b6468eb6d" />

<img width="1920" height="1080" alt="Screenshot (120)" src="https://github.com/user-attachments/assets/6e8b3e95-cf69-4ba8-a8b0-6c57ad940353" />
<img width="1920" height="1080" alt="Screenshot (121)" src="https://github.com/user-attachments/assets/d7fc7946-5451-4000-8e9a-42913c971111" />

* Explication des composants :
* 
1. Le voyage entre les pages (Navigator)

Navigator.push : Permet d'aller vers une nouvelle page. Imaginez que vous posez une nouvelle feuille de papier par-dessus la précédente.

MaterialPageRoute : Gère l'animation de transition (la page qui glisse du bas ou du côté).

Navigator.pop : Sert à revenir en arrière (enlever la feuille du dessus). C'est ce qui se passe quand vous cliquez sur la petite flèche de retour ou le bouton "Annuler" du dialogue.

2. Les listes et le passage de données
ListView.builder : C'est un outil très puissant. Au lieu de créer 20 pages manuellement, il génère une liste infinie à partir d'un seul modèle. C'est très efficace pour la mémoire du téléphone.

Transfert d'info : Quand vous cliquez sur un élément, le code envoie le nom de cet élément (itemName) à la page DetailPage. La page sait alors exactement ce qu'elle doit afficher.

3. Les fenêtres de dialogue (showDialog)
Dans la page des paramètres, vous utilisez une alerte de confirmation :

Elle interrompt l'utilisateur pour lui demander une confirmation avant une action grave (effacer les données).

* Captures de l'app :

  <img width="1920" height="1080" alt="Screenshot (99)" src="https://github.com/user-attachments/assets/d4fd04dc-9e70-4fbd-a97b-4a2d2b012108" />
<img width="1920" height="1080" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/5811f903-aafd-476e-b039-954757a04df0" />
<img width="1920" height="1080" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/fde42f7c-818f-4f13-9755-05a00a978da6" />
<img width="1920" height="1080" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/4abcb350-4a3e-4418-a008-0e8f3f219ac4" />
<img width="1920" height="1080" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/1c5a2d55-b368-418f-9ef1-70ed84d1d091" />


C'est un Widget qui s'affiche "flottant" au-dessus du reste de l'application.
