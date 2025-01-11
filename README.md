# La libft

## 📚 Introduction

Bon faut bien commencer quelque part, et la **libft** c'est pas mal comme starter dans le monde du dév, littéralement la caisse a outils du C a 42 regroupant des fonctions utilitaires pour simplifier et accélérer le développement des projets suivant et puis on va pas refaire des strlen toutes les 2 secondes après tout.

Pour les paumer comme moi ça a eu plusieurs utilité , déjà comprendre que les librairie c'est pas magique et qu'il y'a des mecs avec des dégaine de savant fou, probablement super vieux (voir mort) maintenant, qui se sont casser le cul a inventer la roue pour qu'on ai pas a le faire, merci a eux (la bise surtout 😘).&#x20;

Ensuite ça ma appris comment on subissait la doc au moyen age du code, bah wai avant gpt on pleurait probablement du sang en s’éclatant les yeux sur des site sans css tout moche ou directement dans le terminal comme des bon fou furieux juste pour comprendre ce que fessait une fonction a un seul paramètre et qui return un int, ptn c'est fou penser y 2 secondes.

Plus sérieusement ça donne une vrais compression sur l'importance des vérification constantes et des tests unitaire, ce qui est la base de ma façons de dév depuis ce projet, Je fait une fonction j’essaye de la détruire par tout les moyens et si après moult tests elle est toujours debout je passe a la suivante et je recommence, de sorte a se que mon code reste toujours bien solide, si ça casse c'est dans mon taff le plus récent et c'est le but, avoir une base solide qui se renforce avec le temps au lieu d'un château de carte foireux.

## 📌 Table des Matières

- 📍 [Fonctionnalités](#fonctionnalités)
  - 🚩 [Partie Obligatoire](#partie-obligatoire)
  - 🚩 [Partie Bonus](#partie-bonus)
  - 🚩 Ajouts Personnels
- 📍 [Installation](#installation)
- 📍 [Utilisation](#utilisation)
- 📍 Dépendances
- 📍 [Liens vers les dépôts supplémentaires](#liens-vers-les-dépôts-supplémentaires)
- 📍 Contributeurs

## 📋 Fonctionnalités

### - Partie Obligatoire

🎯 La partie obligatoire regroupe les fonctions les plus courantes de la libc, réécrites pour s’approprier leur fonctionnement.

Rien d'original ici c'est du vu et revu mais ça donne des idées sur comment au fur et a mesure des projet suivant, on peut standardiser des fonctions pour leurs donner une grande flexibiliser et avoir un outils polyvalent facilement :

- **Gestion des chaînes** :
  - ✨ `ft_strlen`, `ft_strdup`, `ft_strjoin`, `ft_substr`, `ft_strtrim`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strmapi`, `ft_striteri`
- **Conversion** :
  - ✨ `ft_atoi`, `ft_itoa`
- **Tests de caractères** :
  - ✨ `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- **Manipulation de la mémoire** :
  - ✨ `ft_memset`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_bzero`, `ft_calloc`
- **Manipulation de fichiers** :
  - ✨ `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### - Partie Bonus

🎯 La partie bonus est centrée sur la gestion des listes chaînées.

Franchement c'est une introduction très nul je trouve, pas de vrais mise en situation, difficile a tester pour le niveau qu'on est sensé avoir et pas claire sur l'étendue des possibilité que les structures et listes offres, c'est vraiment dommage, j'ai du attendre push-swap pour bien comprendre c'est 2 outils qui sont incroyable :

- **Création et manipulation** :
  - 🌟 `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`, `ft_lstsize`, `ft_lstlast`
- **Gestion mémoire et itération** :
  - 🌟 `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

### - Ajouts Personnels

🎯 Pour répondre à des besoins spécifiques, plusieurs fonctions additionnelles que j'ai ajoutées. 🛠️

Alors vous moquer pas elles on été faite parfois a l’arrache, pour des cas particulier et elle sont des fois redondante avec une fonction déjà existante aux qu'elle je n'ai pas penser sur le coup :

- **Mathématiques** :
  - 🧮 `ft_absolute_nbr`, `ft_atoi_base`, `ft_atol`
- **Validation et vérifications** :
  - 🧮 `ft_isint`, `ft_isnbr`, `ft_isexa`, `ft_verif_extension`
- **Gestion des chaînes et tableaux** :
  - 🧮 `ft_count_n`, `ft_countuntil`, `ft_countwords`, `ft_contain_n`, `ft_countain_double`
- **Manipulation de mémoire** :
  - 🧮 `ft_memlcpy`, `ft_strndup`
- **Erreurs et sorties** :
  - 🧮 `ft_exit`

## ⚙️ Installation

Pour compiler et utiliser la bibliothèque **libft** :

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/Gregory-Marquiset/gm_libft.git
   cd gm_libft
   ```

2. Compilez la bibliothèque :

   ```bash
   make
   ```

3. Incluez le fichier `libft.h` dans vos projets et compilez-les avec `libft.a` :

   ```bash
   cc -Wall -Wextra -Werror -L. -lft_bns mvotre_code.c 
   ```

## 🚀 Utilisation

1\. Ajoutez `#include "libft.h"` dans vos fichiers source.

2\. Compilez votre projet en liant la bibliothèque **libft**. 3.

Profitez des fonctions utiles de cette magnifique bibliothèque !

## 🔗 Dépendances

Normalement aucune, mais je peut me tromper, je ne suis que presque parfait après tout.

## 📥️ Liens vers les dépôts supplémentaires

Certains projet suivant on été ajouter pour plus de possibilité, **get\_next\_line** et **ft\_printf**, sont disponibles mais pas détailler ici, il le sont dans leurs repos respectif :

- [get\_next\_line Repository](https://github.com/<votre-utilisateur>/get_next_line)
- [ft\_printf Repository](https://github.com/<votre-utilisateur>/ft_printf)

## ✍️ Créateur, contributeurs principale et homme fart du projet

- Gregory **Marquiset** aka **gmarquis**

---

## 📖 Note :

- Merci de consulter le wiki pour des détails techniques et des conseils sur les différentes fonctions, tout peut êtres modifier ou supprimer a tout moment profiter en temps que c'est la mes poulets.
- La bibliothèque est mise a jour si j'en ressent le besoin ou que je voie une propal intéressante.

  Alors n’hésite pas à ouvrir une issue ou une pull request que je pourrait ignorer comme le plus bg de t'est crush qui te lâche un vu.

**Et le bisous ma gueule, c'est important.**

