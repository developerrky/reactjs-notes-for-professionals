# What is ReactJS?
ReactJS is an open-source, component based front end library responsible only for the view layer of the application. It is maintained by Facebook.

React is a JavaScript library for building composable user interfaces. This means that we can build a user interface by composing items called components. A component is an element that contributes to building a user interface. It could be a textbox, a button, a whole form, a group of other components, and so on. Even the entire application's user interface is a component. So, React encourages the creation of components to build a user interface; it's even better if these components are reusable.

Since the library deals with user interfaces, you may wonder which presentational design patterns React was inspired by: Model-ViewController, Model-View-Presenter, Model-View-ViewModel, or something else. React is not bound to a specific presentational pattern. React implements the View part of the most common patterns, leaving developers free to choose the best approach to implement the model, the presenter, and everything else they need to build their application. This
aspect is important, since it allows us to classify it as a library, not as a framework; therefore, comparisons with frameworks such as Angular may throw up some inconsistencies.

The most powerful thing about React is that can be used in the client, server, mobile applications, and even VR applications.

Companies such as Airbnb, Microsoft, Netflix, Disney, Dropbox, Twitter, PayPal, Salesforce, Tesla, and Uber are extensively using React in their projects.

# React Developer Tools
There are several developer tools that can be installed as browser extensions or addons that you may find useful as well:
- i) **react-detector** - react-detector is a Chrome extension that lets you know which websites are using
React and which are not.
- ii) **show-me-the-react** - This is another tool, available for Firefox and Chrome, that detects React as you
browse the internet.
- iii) **React developer tools** - This is a plugin that can extend the functionality of the browser’s developer tools.
It creates a new tab in the developer tools where you can view React elements. If you prefer Chrome, you can install it as an extension; you can also install it as an add-on for Firefox.

# Installation of React
Fortunately, we can use create-react-app, a command-line interface (CLI) tool that allows us to set up a React-based application without needing to configure any of the aforementioned tools. It is based on Node.js and provides commands to set up and modify a React application in an immediate way.

In order to install create-react-app, you need Node.js installed on your machine. You can install the CLI by typing the following command in a console window: 
```npm install -g create-react-app```

After installation, you can verify whether it is properly installed by typing the following command:
```create-react-app --version```
If all is OK, the installed version of create-react-app will be shown.
