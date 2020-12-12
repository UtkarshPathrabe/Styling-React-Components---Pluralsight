React Components Styling
========================

Q01. What makes traditional CSS styles potentially non-deterministic in their resolution?  
A. Asynchronous additions of new stylesheets in the global namespace  
B. Unpredictable resolution of selector order  
C. Changing rules regarding the cascade across browsers  
D. Styles appearing in the head or body element of the page  
Answer: Asynchronous additions of new stylesheets in the global namespace  

Q02. How do inline styles ensure isolation?  
A. By usage of a naming convention like BEM  
B. By namespacing of classnames  
C. By applying all styles directly to an element via the style prop  
D. By avoiding reuse of any selectors within a project  
Answer: By applying all styles directly to an element via the style prop  

Q03. How can hover states be accomplished via inline styles?  
A. By nesting the hover state in the style prop object  
B. By using React state and mouse event props  
C. By using the :hover selector  
D. By using the ampersand to associate the hover rule with the CSS selector  
Answer: By using React state and mouse event props  

Q04. Which is NOT an advantage of using a CSS-in-JS library compared to inline styles?  
A. Writing CSS in a CSS stylesheet  
B. Writing CSS in the CSS syntax  
C. Isolation of styles within components  
D. Colocation of styles with components  
Answer: Colocation of styles with components  

Q05. What is the proper syntax for importing a CSS stylesheet into your JavaScript file via Webpack?  
A. `@import "mystyles.css";`  
B. `<link rel="stylesheet" href="mystyles.css" />`  
C. `import './mystyles.css';`  
D. `document.head.append('mystyles.css');`  
Answer: `import './mystyles.css';`  

Q06. What does a CSS module import look like in React?  
A. `@import "mystyles.css";`  
B. `ReactDOM.import('./mystyles.css')`  
C. `import css from './mystyles.css'`  
D. `import "./mystyles.css"`  
Answer: `import css from './mystyles.css'`  

Q07. What is the proper syntax for referring to a CSS module from within a component?  
A. `className="selectorName"`  
B. `style={css.selectorName}`  
C. `className="css.selectorName"`  
D. `className={css.selectorName}`  
Answer: `className={css.selectorName}`  

Q08. Which is NOT a module bundler that can be used for building React apps?  
A. Webpack  
B. Parcel  
C. Rollup  
D. Radium  
Answer: Radium  

Q09. What module bundler is create-react-app built on?  
A. Webpack  
B. Rollup  
C. Parcel  
D. Browserify  
Answer: Webpack  

Q10. What Webpack loader order allows for PostCSS preprocessing?  
A. cssnext-loader  
B. postcss-loader  
C. style-loader  
D. css-loader  
Answer: postcss-loader  

Q11. How do CSS modules avoid name unintended style overrides?  
A. By hashing selector names to be unique in the global namespace  
B. By evaluating the styles a runtime without building them  
C. By ensuring the most specific selectors are last in the cascade  
D. By building components so the styles are converted to inline styles  
Answer: By hashing selector names to be unique in the global namespace  

Q12. What are the native React props for styling elements?  
A. styles and classNames  
B. styles and css  
C. style and class  
D. style and className  
Answer: style and className  

Q13. Using Parcel, what is the only config file required to build a React project using PostCSS?  
A. babel.config.js  
B. parcel.config.js  
C. postcss.config.js  
D. .browserslistrc  