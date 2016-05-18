# Lien

Markdown supporte deux types de liens: inline et de référence.

Dans les deux styles , le texte du lien est délimité par des [crochets] .

Pour créer un lien de type inline , utilisez des parenthèses immédiatement après la fermeture du texte du lien. A l'intérieur des parenthèses , mettez l'URL à laquelle vous voulez que le lien vers le point , avec un titre optionnel pour le lien, entouré de guillemets . Par exemple:
```markdown
[Je suis un lien de type inline](https://www.google.com)

[Je suis un lien de type inline avec un titre](https://www.google.com "Accueil Google")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)
```

Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:
```markdown
This is [an example][id] reference-style link.
```

You can optionally use a space to separate the sets of brackets:
```markdown
This is [an example] [id] reference-style link.
```

Then, anywhere in the document, you define your link label like this, on a line by itself:
```markdown
[id]: http://example.com/  "Optional Title Here"
```

**GitHub** and **GitBook** supports URL autolinking. They will autolink standard URLs, so if you want to link to a URL (instead of setting link text), you can simply enter the URL and it will be turned into a link to that URL.


---

Here's a quiz about markdown links.

Select the valid links:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> The link text is delimited by [square brackets].

What are the correct informations from this link: ```[a link](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> Links can have 3 parts: the text, the url and a title.

---

