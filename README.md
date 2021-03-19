## Install Extensions
- Live Sass Compiler
- Live Server

## Notes
- Below in footer list of VS Code -> *Watch Sass* -> .scss file needs to be watched -> when saving will 'compile' to .css
- *!* in html file to emmet html body in index.html (alternative to *html*)
- https://wwww.w3schools.com/
- Ctrl-Shift-i -> Activates Developer Tools in Chrome
- Duplicate Line -> Alt-Shift-ArrowDown
- Ctrl-B -> Toggle Explorer/Browser in IDE -> enable/disable
- https://fonts.google.com -> to embed fonts
- in CSS:
     .mobile-menu{
        cursor: pointer;
    }
-> changes pointer to 'finger/hand'
- Instruction:
    :root {
        --primary-color:#007af3;
    }
-> to declare variables -> can be used like this:
            span{
            color:var(--primary-color);
        }
to scope for specific type, use i.e.: 
    input[type="submit"]{
            background-color: #f2f2f2;
    }

- To order items based on scree size, use:
    ul.features-list{
        display:grid;
        grid-template-columns: repeat(auto-fit, minmax(19rem, 1fr));
    }

- Responsive instruction in SCSS: *@media only screen and (min-width: nnnnpx) {}*
