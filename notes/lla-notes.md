# Little Linux Assistant Notes

Here are a few notes that we might want to keep in mind when it comes to handling development of **Little Linux Assistant**. 

Notes are separated by category and will be updated periodically. 

### Git Branches 

The development of this project is separated into three branches: 

- **dev**
- **testing**
- **main**

Stuff gets worked on in the **dev** branch, and is tested. If the tests are satisfactory, then the code is merged over to the **testing** branch and tested further. If everything checks out correctly, then we can move that code over to the **main** branch for production. 

So, code moves as follows: 

> **dev** -> **testing** -> **main** 

It is important to keep this development flow in mind so we don't accidentally break something across branches. 

### Libraries

One of the most important things we are working on in this project is the development of handy libraries for LLA to use. Currently, these include *News*, *Weather*, and *Minigames*, where we can pull functions from the libraries and use them in the main parts of the program. 

We will keep developing and implementing new libraries for this project to take advantage of as time goes on. 

### Future Ideas: 

These are just some ideas that I think we can probably work into the project as time goes on. These would make the project a lot more accessible to people, and maybe that much more helpful. 

I am adding them to this list and then going back over and prioritizing them from top to bottom - more helpful things on top, less important things on bottom. 

**_Future Ideas List for LLA_**: 

- The GUI port using either *PySimpleGUI* or *GTK*. 
- Add an ability for the user to open applications on their computer.
- Add an ability to perform web searches from LLA. 