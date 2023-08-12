# extra


Start site locally

```
bundle install
bundle exec jekyll serve
```

Render PDF files from asciidoc source

```
sudo gem install asciidoctor-pdf
asciidoctor-pdf $(ls booksource/*.asciidoc) -D pdfs
```