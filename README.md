## Install Sass

```
gem install sass
```

### Make Diretectories

```
rake setup
```

### Complie Sass

```
sass assets/stylesheets/_bootstrap.scss dist/stylesheets/bootstrap.css
sass assets/stylesheets/_bootstrap.scss dist/stylesheets/bootstrap.min.css --style compressed
```
or 
```
rake compile
```
