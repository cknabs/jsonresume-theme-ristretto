# Ristretto Theme

Ristretto is a [JSON Resume](https://jsonresume.org/) theme based on [Macchiato Theme](https://github.com/biosan/jsonresume-theme-macchiato).


> ***Currently it doesn't have any major style difference from its parent [Macchiato](https://github.com/biosan/jsonresume-theme-macchiato).***


### PDF output

To export your resume to PDF, you can use Puppeteer-CLI:

```
npm install -g puppeteer-cli
puppeteer --margin-top 0 --margin-right 0 --margin-bottom 0 --margin-left 0 --format A4 print resume.html resume.pdf
```

Also checkout [HackMyResume](), a powerful tool to build and analyze your JSON Resume.


## License

Available under the [MIT license](http://mths.be/mit).
