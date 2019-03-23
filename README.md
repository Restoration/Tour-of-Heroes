# Tour-of-Heroes

## Description
This repository is AngularJS Tutorials.  
The development to learn AngularJS.  

## Tutorial: Tour of Heroes
The Tour of Heroes tutorial covers the fundamentals of Angular.  
In this tutorial you will build an app that helps a staffing agency manage its stable of heroes.  

This basic app has many of the features you'd expect to find in a data-driven application. It acquires and displays a list of heroes, edits a selected hero's detail, and navigates among different views of heroic data.  

By the end of the tutorial you will be able to do the following:  

- Use built-in Angular directives to show and hide elements and display lists of hero data.
- Create Angular components to display hero details and show an array of heroes.
- Use one-way data binding for read-only data.
- Add editable fields to update a model with two-way data binding.
- Bind component methods to user events, like keystrokes and clicks.
- Enable users to select a hero from a master list and edit that hero in the details view.
- Format data with pipes.
- Create a shared service to assemble the heroes.
- Use routing to navigate among different views and their components.
  
[https://angular.io/tutorial](https://angular.io/tutorial)

# What's AngularJS
Angular is open source softweare which was developed by Google and user community. Angualar is MVW framework. It means Model-View-Whatever. The Angular develop complcated web application for frontend to easy. It can also data binding, DI etc.


##  Install angular
```
$ npm install -g @angular/cli
```
You can't name `app` for project.
```
$ ng new my-app
$ cd my-app
$ ng serve --open
```

```
$ vim  ./src/app/app.component.ts
```

```javascript
export class AppComponent {
  title = 'My First Angular App!';
}
```

```
$ vim src/app/app.component.css
```

```css
h1 {
  color: #369;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 250%;
}
```


