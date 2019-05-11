# Getting Started with Vue

This course gently introduces how to start developing with Vue to create web applications.

You will learn how to hone your Vue component skills, display data, present lists and inputs, handle user interactions in components, navigate between views, manage data and state, and get started with all of the key tools to make you efficient at developing with Vue.

## 1 - Getting Started with Vue

The learner will see what we will learn and build in the demos for this course. We’ll cover the requirements for Vue, how to set up your tools to code with Vue, and what recommended tooling you will need.

The learner will get the demo app from github and we’ll briefly explore how to create, build and serve a Vue app (deferring to the Vue CLI course for depth) and explore the basic structure of a Vue app and component files. Finally, we’ll share resources for Vue and the ecosystem.

### Getting Started Concepts

- Requirements
- Recommended/Key tooling
- Create, build and serve a new app
- Clone the demo app
- Walk through the demo app
- Resources

### Getting Started Demo

The learner will create a new Vue app, clone the demo app, and explore the demo app.

## 2 - Displaying Data and Responding to Events

You’ll learn how to bind data to input elements to display data and make your data models update when the users change values. You’ll get your first look at component data for storing models. You’ll learn how to use the v-model directive to bind to inputs for text, checkboxes, radios, select boxes, and textarea elements. You’ll learn how to capture and respond to user interactions including when a user enters text, moves focus away from an element, or clicks a button. You’ll use the v-on directive and its shortcuts along with modifiers to capture specific events. Finally, you’ll learn how to add styles based on data values.

### Data Concepts

- Create a Heroes component
- Create input elements
- Create hero model data
- Property and event bindings
- Binding data (interpolation, v-model, v-bind, v-text)
- Handling events (v-on)

### Data Demo

The learner will add a Heroes component, sample hero data, and create input elements to modify the people from the models. The learner will explore how the event handlers work, and add click handlers for buttons to save and cancel the changes. They will also learn how to capture when the ENTER key is pressed in a textbox to save the data.

## 3 - Displaying Lists and Conditional Content

You’ll learn how to show content that repeats for lists using the v-for directive while exploring its various options for using key and index values. You’ll also learn the difference between hiding and showing elements compared to adding or removing elements, with v-show and v-if, respectively.

### Displaying Concepts

- Conditionals (v-if)
- Looping and keys (v-for and :key)
- Hide/Show (v-show)
- Styling with class and styles

### Displaying Demo

The learner will add code to list the people, select them, and then display them in a master-detail view in the Heroes component. The learner will hide or show the details based on whether a person is selected or not. We will tease in how to handle a click event, which will be covered more in the next module. The learner will apply styling for showing which person was selected.

## 4 - Interacting within a Component

You’ll learn how to use the various features of a component including reactive data, computed properties, watchers, and methods. You’ll also learn how to tap into events (such as created) at key moments during the component’s lifecycle.

### Component Concepts

- Data
- Computed properties
- Watchers
- Methods
- Filters
- Tapping into life cycle events

### Component Demo

The learner will add watchers and computed properties that react to changes in hero data, seeing the difference in each. The learner will extend the reactive data concepts by adding new models and intentionally causing errors to understand its boundaries. Finally, the learner will use lifecycle events to get data for the component.

## 5 - Component Communication

You’ll learn how to create parent-child components and associate them with each other. You’ll learn how to pass data from the parent to the child and send events from the child to the parent. Finally, you’ll learn how to share common logic between components.

### Communication Concepts

- Props
- Child Components
- Mixins

### Communication Demo

The learner will add child components to break out the heroes list and hero details components. The learner will pass the selected hero from the parent to the child component to show the details, using Vue props. The learner will define and emit events from the child to the parent, and learn how to share common lifecycle and methods between components, without repeating code using mixins.

## Accessing Data with Http

You’ll learn how to make calls for data over http using the popular axios library and how to import and leverage modules in Vue apps.

### 6 - Http Concepts

- Http calls with axios
- API Proxies
- Importing javascript modules

### Http Demo

The learner will replace static hero data in the app with axios calls to JSON files (simulating API calls) using asynchronous operations. The learner will also leverage using 3rd party modules in their components and modules.

## 7 - Navigating Vue Apps with Routing

You’ll learn how to add routing to your app to navigate between different views. You’ll explore how to pass data between the routes, call the routes, and tap into routing events. Finally, you’ll learn how to use eager and lazily loaded routes.

### Routing Concepts

- Adding the router
- Defining routes
- Linking to routes
- Special routes
- Parameters
- Routing events
- Lazy loading

### Routing Demo

The learner will add routing to the app, define routes for the heroes and villains, and pass data using parameters. They will add logic to parse the parameters in components and see how this builds on their props learnings. They will also tap into routing events for coming and going between routes and add lazy loaded routes.

## 8 - Managing Data State with Vuex

You’ll learn how to add state management for your Vue app’s data to the app using Vuex. You’ll explore how to setup Vuex with its concepts and debug the single directional data flow from the state store to your app (then back to the store)

### Vuex Concepts

- Adding Vuex
- The store and state
- Mutations
- Actions
- Getters
- Modules

### Vuex Demo

The learner will add a Vuex store to the app to manage hero data. They will add the mutations to modify the state, the actions to fire off the intent to modify the data, and create getters to access the state in the components.