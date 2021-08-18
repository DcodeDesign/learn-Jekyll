# Jekyll

## install
    
### Requirement
- Ruby version 2.5.0 or higher, including all development headers (check your Ruby version using `ruby -v`)
- RubyGems (check your Gems version using `gem -v`)
- GCC and Make (check versions using `gcc -v`,`g++ -v`, and `make -v`)

### Install
    
    gem install jekyll
    
### Compilation
    bundle exec jekyll build
    jekyll build

## Other Install
    bundle add webrick

## Start server
    bundle exec jekyll serve --trace --watch
    bundle exec jekyll serve --trace --watch --force_polling
    
## Local Gems list
    gem list jekyll
    gem env

## Local bundle list 
    bundle list
    bundle info kramdown

## Unstall Jekyll
    gem install jekyll --user-install
    gem install jekyll

## Update
    bundle update jekyll
