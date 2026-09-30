# La Nouvelle Zélande🥝
* {
  /* Pour que les tailles soient correctes */
  box-sizing: border-box;
}

body {
  /* Pour coller le menu au bord, sans espace */
  margin: 0;
}

.menu {
  /* Pour que le menu reste en place quand on scroll */
  position: fixed;
  /* Pour que le menu ne soit pas sur le texte et que ce dernier puisse être sélectionné */
  width: 0px;
}

main {
  /* Pour que le texte ne soit pas sous le menu */
  margin-left: 50px;
  width: 500px;
  text-align: justify;
}

#hamburger {
  /* Pour que la checkbox ne s'affiche pas */
  display: none;
}

#hamburger-logo {
  /* Pour que le curseur soit un pointeur */
  cursor: pointer;
  background: black;
  width: 200px;
  display: block;
  color: white;
  /* Pour que le menu hamburger s'affiche toujours */
  text-align: right;
  /* Pour que le menu hamburger soit "rangé" par défaut */
  transform: translateX(-168px);
  padding: 10px;
}

nav {
  display: flex;
  flex-direction: column;
  background: black;
  overflow: hidden;
  width: 200px;
  /* Pour que les liens soient "rangés" par défaut */
  transform: translateX(-200px);
}

#hamburger-logo,
nav {
  /* Pour qu'il y ait une animation */
  transition: 0.7s;
}

/* Lorsque #hamburger est coché, le #hamburger-logo et le nav qui sont dans le même parent changent de propriété */
#hamburger:checked ~ #hamburger-logo,
#hamburger:checked ~ nav {
  /* Changement de la position pour afficher les menus */
  transform: translate(0);
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px;
}

nav a:hover {
  background: #444;
}
## <ins>Histoire</ins>
La Nouvelle-Zélande est un pays d'Océanie composé de nombreuses îles, dont deux principales: l'Ile du Sud et l'Ile du Nord. Sa capitale est Wellington et les langues officielles sont l'Anglais et le Maori. Ce pays est aujourd'hui très attractif, principalement pour [ses paysages](Dossier/Second_page), et est également très visé pour les backpackers et les étudiants erasmus.
## Culture
List:
1. item 1
2. item 2

![image](tatouage_maori.jfif)

<p align="center">
  <img src="./tatouage_maori.jfif" width="237" height="323">
