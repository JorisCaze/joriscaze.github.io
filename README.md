# Description 
Personnal website hosted with [GitHub Pages](https://docs.github.com/en/pages) available at https://joriscaze.github.io/

Static website is built with [Hugo](https://gohugo.io/) static website generator and the formely *Academic* theme now replaced by [Wowchemy](https://wowchemy.com/).

For the sake of simplicity I still use the old version of the *Academic* theme, the theme is directly stored within the repository *theme/academic/*. Therefore no Git submodule or Hugo module are used.

# Memento to update website

Clone the repository locally:

```
$ git clone https://github.com/JorisCaze/joriscaze.github.io.git
```

To edit the content simply edit the desired markdown file in the *content/* folder.

Once done, you can check your website locally:

```
$ hugo server
```

Finally, the final is built under the *docs/* folder:

```
$ hugo
```

Commit and push changes to remote to update the web version.
