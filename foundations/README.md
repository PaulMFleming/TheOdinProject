### Create a clone of the Google search page 

* Task: Make the page look like the Google search page
* Project does not need to have search funcionality. It simply needs to look like Googles search page

### Built Using

* HTML 5
* CSS custom properties
* Flexbox
* [Font-Awesome Icons](https://fontawesome.com/v5.15/icons/search)

### Key Takaways

* Use a container/wrapper div to space the nav container and footer content evenly
* Set the body and container height to 100% and use flexbox to space everything
* Set a margin on the body to get content to fill the page

```
html,
body {
    height: 100%;
    margin: 0;
}

#page-wrapper {
    text-align: center;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}
```