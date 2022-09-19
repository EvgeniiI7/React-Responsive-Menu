# Responsive Menu for React
```
This is a responsive menu for React applications with the capability to include dropdown menu,
using React Router 'react-router-dom' library to showcase the menu's functionality,
however, the Menu component itself doesn't make use of the React Router library,
it only provides the URL, based on the menu objects passed from the App.js component.
```

Target:
- A responsive and reusable menu component
- Menu will have two states, for desktop and for mobile
- breakpoints should be customizable
- Can take drop down submenus, 1 level


Structure:

- Parent Menu component:

    Desktop:
    ```
    - Brand
    - Regular menu items
    - Dropdown parent menu items
    - Dropdown container for each dropdown parent, show/hide
    ```

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
 <img src="https://user-images.githubusercontent.com/88345845/190940952-8ecb9283-0abe-4a81-bb2c-5ad40f7f3492.png" width="500"/>
 <img src="https://user-images.githubusercontent.com/88345845/190940957-f90c6804-3757-44d2-bd54-7c7b5b586713.png" width="500"/>
 <img src="https://user-images.githubusercontent.com/88345845/190940961-8b4ef83a-b438-451c-8a9d-695b6cf76f79.png" width="500"/>
 
