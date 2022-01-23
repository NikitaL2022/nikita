Q1. What do you think each section does here? What commands can you run?
Lit is the software we rely on to program and 2.0.2 is the version. devDependencies define components and their versions for the project. You can use the components in the project, but i doon't know if they can be run in the command line. 

Q2. The "demo" for your hello-world element is found in index.html. Reading this code, what does it do and how does it work? What HTML is making your script load to show a demo? How is this file rendering HTML via JavaScript?
This is the first file being called when accessing the website. It imports html and render classes from Lit. Imports JavaScript file. Everything in script tags loads components and displays demo.

Q3. The Definition of your element is in your-element-name.js, while the class JS object is found in src/YourElementName.js. Why do you think they put these in two separate files?
The class file gives instructions how to create object. The definition file is how to call/use the class file.
 
Q4: Try to explain what Lit is providing to the repo. What's so special about what Lit is providing that I'd be so bold to say it changes how the web is developed, forever? 
Helps by eliminating common tasks and allowing to focus on functionality only. For example 
render(
      html`
        <la-la .title=${title}>
          some light-dom
        </la-la>
      `,
      document.querySelector('#demo')
    ); //does all required HTML tags
