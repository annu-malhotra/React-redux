# React
  - gives access to how to organise UI in terms of composition of components
  - library to build rich internet application


User ----->   View ------> Model

View and Model needs to be loosely coupled, meaning the View should only be aware of the pulic information of model and not at all model calculation/logic.

This is 'Seperation of Concerns'.
 
 View synchronization logic involves 2 stategies:
 1. update existing DOM  -- 
      - adv : +efficient
      - disadv : imperative : write a lot of logic to make synchronize view
 2. Recreate the DOM fragment again and again from scratch for every change in model
      - adv : declarative : call render again and again 
      - disadv : inefficient
      
 
 Simplicity of declarative approach from startegy 2 and same time effficient as strategy 1, is what is delivered by REACT.
 
 React creates another level of abstraction in your browser, i.e objet based representation of html elements caled Virtual DOM.
 
 HTML ----> React DOM ----> browser DOM ----> Presentation
 
 React DOM updates only what is required to be changed and update only those DOM nodes.
      
 
