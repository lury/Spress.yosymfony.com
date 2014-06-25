## Spress web page

This is the git repo of Spress site: <http://spress.yosymfony.com>

**How to build?**
```
$ git clone https://github.com/yosymfony/Spress.yosymfony.com.git

$ cd Spress.yosymfony.com/

# Get plugins
$ php composer.phar update

# Build with Spress
$ spress site:build

# or with production environment options:
$ spress site:build --env=prod

$ cd _site/

php -S localhost:8080

```
