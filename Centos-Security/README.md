# CentOS Security slides using reveal.js [![Build Status](https://travis-ci.org/hakimel/reveal.js.svg?branch=master)](https://travis-ci.org/hakimel/reveal.js) <a href="https://slides.com?ref=github"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>

This slides are part of the Operative System Class, this was created using Revealjs,  a framework for easily creating beautiful presentations using HTML, 

### Full setup Slides
In order to run the presentation you will need to do: 

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)
2. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/hakimel/reveal.js.git
   ```
3. Navigate to the reveal.js folder
   ```sh
   $ cd reveal.js
   ```

4. Install dependencies
   ```sh
   $ npm install
   ```

5. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

6. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.

### Folder Structure

- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)

There is a pdf file which containst all the slides. 

## License

MIT licensed
