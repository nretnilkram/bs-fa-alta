## BS-FA-ALTA

* Bootstrap: 3.3.7
* FontAwesome: 4.7.0

### Install Sass

```
gem install sass
```

### Make Directories

```
rake sass:setup
```

### Delete dist Directories

```
rake sass:cleanup
```

### Delete and Create dist Directories

```
rake sass:reset
```

### Complie Sass

```
sass assets/stylesheets/_bootstrap.scss dist/stylesheets/bootstrap-fa-alta.css
sass assets/stylesheets/_bootstrap.scss dist/stylesheets/bootstrap-fa-alta.min.css --style compressed
```
or
```
rake sass:compile
```
