# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications (true/false)true
-   Researched:True. React's intent is to efficiently render complex, dynamic applications as efficiently and dynamically as possible.
- React will only render on the server using Node.js (true/false)false
-   Researched:False. React will render from a variety of back-end sources.
- React is a full stack framework for modern web applications (true/false)false
-   Researched:False. React is the front end of the framework.
- React is a flexible library that plays the role of V in an MVC framework (true/false)false
-   Researched:True. React is the View component of the Model-View-Controller framework.
- You should always update a component's state directly using this.state (true/false)false
-   Researched:False. Use this.setState unless within the constructor.
- React is made up of encapsulated components that manage their own state (true/false)true
-   Researched:True
- React components render HTML (true/false)true
-   Researched:True

1b. Add an interesting TRUE fact about React to the list.
-Originally created at facebook

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: Dumb components only provide something to the parent. They do not have to track any intenal state. Smart components can have state to manage. The goal would be to have as few smart components as possible to simplfy the codebase.

  Researched answer:Dumb components are also called ‘presentational’ components because their only responsibility is to present something to the DOM. They will only contain a render function. Smart components will keep track of state and contain a constructor.The smart components do the heavy lifting and pass the data down to the presentational components as props. The difference matters to keep a clean structure.



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: It adds the folder to the dependencies.

  Researched answer: A package is a folder with code and a package.json file that describes the contents. When you want to use another package, you first need to add it to your dependencies. This means running yarn add [package-name] to install it into your project. This will also update your package.json and your yarn.lock so that other developers working on the project will get the same dependencies as you when they run yarn or yarn install.



4. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: State is a variable within the component. Props are variables passed to a child component.

  Researched answer:State contains variables within components, props are passed to child components and should not be changed by the child. State can be changed only while within the component, centralizing state managment in the parent.



5. How would you explain state to a friend who doesn't know code?

  Your answer: Replace the word state with status or something else that people associate with a property that can be changed, like "Where is your car parked?". The car has a location that can be found by anyone but to change the location the owner would have to move it and let everybody else know the new location.
