# Responsive Menu for React

This is a responsive menu for React applications, with the capability to include dropdown menus, the repo includes and example on using React Router 'react-router-dom' library to showcase the menu's functionality, however, the Menu component itself doesn't make use of the React Router library, it only provides the URL, based on the menu objects passed from the App.js component.


## Description

Downoload the Menu Folder which includes 2 files, menu.css and Menu.js. Or alternatively, download the whole repo, to examine usage within App.js that imports the Menu.
Menu.js is the component file, you can import this into your react component using import, for instance, in the current example hierarchy, I created a folder called Menu, in which I included the Menu.js and menu.css files, I'm importing using using `import Menu from './Menu/Menu'` inside App.js in order to import the Menu component.
Then you can use the Menu component in your App component:

Target:
- A responsive and reusable menu component
- Menu will have two states, for desktop and for mobile
- breakpoints should be customizable
- Can take drop down submenus, 1 level


Structure:

- Parent Menu component:

    Desktop:
    - Brand
    - Regular menu items
    - Dropdown parent menu items
    - Dropdown container for each dropdown parent, show/hide

    Mobile:
    - Brand
    - Hamburger Button:
        - Button icon changes to X
        - Modal Menu moves in (direction customizable)
        - Menu items same as desktop version
     - X Button:
        - Menu Modal moves out opposite direction
        - Button icon changes to hamburger button
    - Modal Menu:
        - Regular menu items
        - Dropdown parent menu items
        - Drop down container for each dropdown parent, pushes in from top, pushes out
     
