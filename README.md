# WEB-STARTER-TEMPLATES
A collection of ready-to-use templates for every modern web development stack. Whether you're building with Tailwind CSS, Bootstrap, Node.js, Django, or Express.js, get started quickly with pre-configured setups.
# Bootstrap-simple-Template

<p>A minimal Bootstrap setup using npm and SASS,but without build tools. Perfect for quick prototyping and small projects</p>
  <pre>
  bootstrap-simple-template/
├── css/
│   ├── custom.css
│   ├── custom.css.map
│   └── styles.css
├── scss/
│   ├── css/
│   └── custom.scss
├── node_modules/
├── index.html
├── package-lock.json
└── package.json
  </pre>
  
### Install Sass globally
npm install -g sass

<p><b>Clone this repository</b></p>

 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES.git
cd Bootstrap-simple-Template

npm install --save-dev autoprefixer@10.4.20 bootstrap@5.3.3 postcss-cli@11.0.0 postcss@8.4.35 sass@1.63.6

sass --watch ./scss/custom.scss ./css/custom.css
