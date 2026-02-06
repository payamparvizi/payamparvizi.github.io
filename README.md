# Gautham Vasan's Academic Website

- Hosted on Github using a Jekyll template borrowed from [Abhishek Das](https://abhishekdas.com/). 

## Local preview
1. Install Ruby using Homebrew for MacOS
2. Jekyll serve setup for Github Pages:
```bash
gem install bundler webrick jekyll
bundle add webrick 
bundle addjekyll
```

3. Host locally:
```bash
bundle exec jekyll serve
```
4. You should see a message like this:

```bash
(base) gautham@Ryuk-MacBook gauthamvasan.github.io % bundle exec jekyll serve
Configuration file: /Users/gautham/src/gauthamvasan.github.io/_config.yml
            Source: /Users/gautham/src/gauthamvasan.github.io
       Destination: /Users/gautham/src/gauthamvasan.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
                    done in 0.534 seconds.
 Auto-regeneration: enabled for '/Users/gautham/src/gauthamvasan.github.io'
    Server address: http://127.0.0.1:4000
```
