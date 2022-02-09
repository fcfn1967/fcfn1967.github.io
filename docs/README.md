#Dokumentation

## Verwendete Technologien

- [HTML5Boilerplate](https://html5boilerplate.com)
- [Schema.org](https://schema.org)
- [FontAwesome](https://fontawesome.com)
- [Fontello](https://fontello.com)
- [Fontsquirrel](https://www.fontsquirrel.com)
- [Oswald Font](https://github.com/vernnobile)
- [Montserrat Font](https://www.fontsquirrel.com/fonts/list/foundry/julieta-ulanovsky)
- [Jekyll](https://jekyllrb.com)

## Weitere Resourcen

- [Webmaster-Richtlinien von Google](https://developers.google.com/search/docs?hl=de)

## Strukturierte Daten
Die Inhalte werden optimalerweise strukturiert im Bereich "Frontmatter" abgelegt. Hierzu werden die Eigenschaftsnamen von schema.org verwendet. Um Probleme mit Jekyll zu vermeiden, wird statt "name" die Eigenschaft "title" verwendet.  

Die Basisdaten der Homepage werden in der Datendatei meta.yml abgelegt.

Personen werden in der Datei person.yml abgelegt. 

## Layout

Das default-Layout importiert folgende Komponenten:

-	head.html
-	header.html
- 	navigation.html
-  footer.html

Einzelne Teil des HEAD-Bereichs (Twittercards, Favicons, Schema.org) werden in Extradsateien abgelegt.

Die auf dem default-Layout basierenden Layouts sollten wie folgt aufgebaut sein:

	<main>
		...
	</main>
	
	<aside>
		...
	</aside°
	
Dies ermöglich später ein variables Design mit CSS.