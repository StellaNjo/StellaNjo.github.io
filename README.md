# StellaNjo.github.io
my first website
- var _COUNT_PAGES = 32;
- let n = 1;

.book(style=`--pages: ${_COUNT_PAGES}`)
  .cover.page
    .cover-content
      h1 Alice in Wonderland
      img(src="https://thesonofthomp-static-resources.netlify.app/rabbit.png")
      h2 by Lewis Carroll

  while n <= _COUNT_PAGES
    .page(style=`--id: ${n++}`)
