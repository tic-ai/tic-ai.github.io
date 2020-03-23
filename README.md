# How to run
- Add jupyter file into `content` folder
- Run :
`pelican content -s publishconf.py && ghp-import output -b master && git push origin master `

# Change theme
- Select theme which you like at http://www.pelicanthemes.com/
- Find that name in `pelican-themes` folder at `dev` branch
- Change value of `THEME` in `pelicanconf.py` file at `dev` branch
- Run above commands
