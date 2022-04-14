# 42 Québec Cursus - Libft

<br />
<div align="center">
	<a href="https://github.com/yanislabbe">
	<img src="images/success.png" alt="success" width="100" height="100">
	</a>
</div>


### À propos

- Créez votre propre bibliothèque contenant des fonctions utiles pour la suite de votre cursus.

### Considérations techniques

- Interdiction d'utiliser des variables globales.
- Si vous avez besoin de fonctions auxiliaires pour réaliser une fonction complexe, vous devez définir ces dernières en static dans le respect de la Norme. Ainsi, leur portée sera limitée au fichier concerné.
- Vous devez rendre tous vos fichiers à la racine de votre dépôt.
- Il est interdit de rendre des fichiers non utilisés.
- Chaque fichier .c doit être compilé avec les flags -Wall -Wextra -Werror.
- Vous devez utiliser la commande ar pour créer votre bibliothèque. L'utilisation de la commande libtool est interdite.
- Votre libft.a doit être créé à la racine de votre dépôt.

### Partie 1 - Fonctions de la libc

- Dans cette première partie, vous devez recoder un ensemble de fonctions de la libc telles que décrites dans leur man respectif sur votre système. Vos fonctions devront avoir exactement le même prototype et le même comportement que les originales. Seule différence, leur nom devra être préfixé par 'ft_fonctions'. Ainsi strlen devient ft_strlen.

- Vous devez recoder les fonctions suivantes. Elles ne nécessitent aucune fonction externe:

- [`isalpha`](http://manpagesfr.free.fr/man/man3/isalpha.3.html)
- [`isdigit`](http://manpagesfr.free.fr/man/man3/isalpha.3.html)
- [`isalnum`](http://manpagesfr.free.fr/man/man3/isalpha.3.html)
- [`isascii`](http://manpagesfr.free.fr/man/man3/isalpha.3.html)
- [`isprint`](http://manpagesfr.free.fr/man/man3/isalpha.3.html)
- [`strlen`](http://manpagesfr.free.fr/man/man3/strlen.3.html)
- [`memset`](http://manpagesfr.free.fr/man/man3/memset.3.html)
- [`bzero`](http://manpagesfr.free.fr/man/man3/bzero.3.html)
- [`memcpy`](http://manpagesfr.free.fr/man/man3/memcpy.3.html)
- [`memmove`](http://manpagesfr.free.fr/man/man3/memmove.3.html)
- [`strlcpy`](https://linux.die.net/man/3/strlcpy)
- [`strlcat`](https://linux.die.net/man/3/strlcpy)
- [`toupper`](http://manpagesfr.free.fr/man/man3/toupper.3.html)
- [`tolower`](http://manpagesfr.free.fr/man/man3/toupper.3.html)
- [`strchr`](http://manpagesfr.free.fr/man/man3/strchr.3.html)
- [`strrchr`](http://manpagesfr.free.fr/man/man3/strchr.3.html)
- [`strncmp`](http://manpagesfr.free.fr/man/man3/strcmp.3.html)
- [`memchr`](http://manpagesfr.free.fr/man/man3/memchr.3.html)
- [`memcmp`](http://manpagesfr.free.fr/man/man3/memcmp.3.html)
- [`strnstr`](https://www.freebsd.org/cgi/man.cgi?query=strnstr&sektion=3)
- [`atoi`](http://manpagesfr.free.fr/man/man3/atoi.3.html)

- Pour les deux fonctions suivantes, vous pourrez faire appel à la fonction mallo() :

- [`calloc`](http://manpagesfr.free.fr/man/man3/malloc.3.html)
- [`strdup`](http://manpagesfr.free.fr/man/man3/strdup.3.html)

### Partie 2 - Fonctions supplémentaires

- Dans cette seconde partie, vous devrez implémenter un certain nombre de fonctions absentes de la libc, ou qui y sont mais sous une forme différente.

- [`Fonctions supplémentaires`](https://github.com/yanislabbe/libft/blob/main/sujet.pdf)

### Partie bonus

- Implémentez les fonctions suivantes afin de manipuler vos listes aisément.

- [`Fonctions bonus`](https://github.com/yanislabbe/libft/blob/main/sujet.pdf)

## Auteur

- Yanis Labbé
