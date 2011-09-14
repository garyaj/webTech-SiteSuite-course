##### Plagiarised from Lea Verou's [Organizing a university course on modern Web development](http://leaverou.me/2010/07/organizing-a-university-course-on-modern-web-development/)
-   **Introduction**
    -   Web application architecture
    -   How the HTTP protocol works
        -   **Objectives:** to give a simple explanation of how the web works
        -   **Process:** Lecture with slides; student explores web page via browser
        -   **Outcome:** Student can open an HTML document in a browser as source code
                     and name or indicate the various features of the document.

-   A small web application example (an AJAX shopping cart)
    in order for the students to get an idea about how everything clicks together
    -   **Objectives:** to give a more detailed explanation of how the web works
    -   **Process:** Lecture with slides; student explores web page via browser
    -   **Outcome:** Student can open an HTML document and indicate the
                 various parts of the document.

-   **HTML(5)**
    -   **Objectives:** to explain and demonstrate sufficient information about the
        structure and content of an HTML document to allow a student to create
        and deploy a simple HTML web page on a web server.
    -   **Process:** Lecture with slides; demonstration; student explores and edits simple web pages via browser
    -   **Outcome:** Student can create and deploy a simple, unstyled, HTML document to a web server for display 
        in a browser. 

    -   Basic structure of an HTML document
        -   **Objectives:** to explain the structure of an HTML document
        -   **Process:** Lecture with slides; student creates a simple web page via browser
        -   **Outcome:** Student can create a simple HTML document and display it
            on a browser
    -   Content model, block vs inline elements
        -   **Objectives:** to explain how the content model works and the
            differences between block and inline elements 
        -   **Process:** Lecture with slides; demonstration of online document;
                     student adds block and inline elements to existing
                     document
        -   **Outcome:** Student can create a simple HTML document containing block
            and inline elements
    -   Basic HTML elements
        -   headings & paragraphs
        -   lists (ordered, unordered, definition lists)
        -   tables
        -   grouping elements (div & span)
            -   **Objectives:** to explain and demonstrate some HTML display
                elements
            -   **Process:** Lecture; demonstration ; student creates an HTML
                document containing these elements and explores their effects
            -   **Outcome:** Student is able to create and display an HTML document
                containing the basic HTML display elements.

    -   Doctypes, the HTML5 doctype
        -   A brief history of HTML
        -   Modern simplification
    -   HTML Validation
        -   What is validation, how to do it, why we do it.
            -   **Objectives:** to explain why validation is important in HTML
            -   **Process:** Lecture with slides; student runs a validator on a simple
                web page via browser and makes corrections until valid.
            -   **Outcome:** Student can create a valid HTML document.
    -   HTML forms
        -   How forms work, GET vs POST
        -   Form controls, shared attributes
        -   The various input types (+ the new ones HTML5 brings)
        -   Other form controls (buttons, <select\> lists, textareas)
        -   Basic form accessibility (labels & fieldsets)
            -   **Objectives:** to explain HTML forms and the various form elements
            -   **Process:** Lecture with slides; student creates a simple web form 
            -   **Outcome:** Student can create a simple web form and run it

-   **CSS**
    -   **Objectives:** to explain and demonstrate Cascaded Style Sheets
    -   **Process:** Lecture with slides; demonstration; student explores CSS elements in a web page via browser
    -   **Outcome:** Student can explain or indicate in HTML documents CSS selectors, inheritence, the box model, CSS properties;
                 student can add CSS elements to an existing HTML document to
                 obtain various nominated styling effects.
    -   CSS standards
    -   CSS rules
    -   Validation
    -   Adding CSS to a page (linking/embedding methods)
    -   Media targeting (The media attribute, @media rules, media queries)
    -   CSS selectors
        -   Introduction to the DOM
        -   Basic selectors (Universal selector, Type selector, Class
            selector, Id selector)
        -   Classes vs Ids
        -   Attribute selectors (all 6)
        -   Pseudo-classes (including most of the CSS3 ones)
        -   Pseudo-elements
        -   Simple selectors & simple selector sequences
        -   Combinators (all 4)
        -   Selector grouping
    -   Cascading & Inheritance
        -   The problem: Conflicts
        -   Specificity
        -   Origin
        -   !important
        -   Inheritance
        -   The special value *inherit*

    -   Properties & values
        -   Keywords
        -   Numerical values & units
        -   Colors (including CSS3 colors)
        -   How shorthands work
        -   Unsupported values & providing fallbacks

    -   Box model
        -   width & height
        -   Block level & inline level elements (reminder from the HTML
            lectures)
        -   The *display* property
        -   border
        -   padding
        -   margin

    -   Positioning
        -   The *position* property
        -   Positioning types (absolute, relative, fixed)
        -   z-index
        -   float
        -   Problems with floats, the *clear* property

    -   Generated content
        -   ::before and ::after
        -   Static generated content
        -   Dynamic generated content (attributes & counters)


-   **Perl for web server side processing**
    -   **Objectives:** to impart a rudimentary knowledge the Perl scripting
        language; to explain and demonstrate a simpler Perl CGI script
        handler.
    -   **Process:** Lecture with slides; demonstration; student explores the
        effects of changes on a simple Perl CGI script.
    -   **Outcome:** Student can write a simple Perl script to solve an
        arithmetical problem; student can create and deploy a simple Perl CGI script for
        processing a web form.

    -   Introduction to Perl syntax
        - A whirlwind tour of Perl
    -   Data types: scalar, array, hash
    -   Subroutines
    -   Regular expressions
    -   Modules, esp. CGI.pm
    -   Web form processing with Perl

-   **JavaScript**
    -   **Objectives:** to demonstrate and explain the syntax and properties of
        JavaScript in an HTML document
    -   **Process:** Lecture with slides; demonstration; student explores JS in a web page via browser
    -   **Outcome:** Student can add Javascript to an existing HTML to implement
        nominated effects and/or appearances.

    -   Adding JS to a document
    -   Separation of concerns
    -   A first, annotated, example (a simple script that generates
        tables of content from &lt;h2> headings)
    -   Basic syntax rules (including semicolons & semicolon insertion)
    -   Variables
    -   Operators (including typeof, the comma operator, strict
        operators, differences of &&/|| in JS)
    -   Primitives (String, Number, Boolean, null, undefined)
    -   Conversion across primitives
    -   Objects
    -   The *in* & *delete* operators
    -   for…in loops
    -   Native objects for primitives (eg the literal 5 vs new
        Number(5))
    -   The global object
    -   Functions (including function expressions vs function
        declarations)
    -   *this* & changing execution context
    -   Arrays (including .forEach() traversal)
    -   Regular expressions in JavaScript
    -   OOP in JavaScript
        -   OOP concepts in JS
        -   Constructors
        -   Inheritance
        -   Encapsulation (private, priviledged & public properties)
        -   Method overloading
        -   JavaScript shortcomings when it comes to OOP
        -   for…in loops, inherited properties & [[Enumerable]],
            .hasOwnProperty()
        -   Type detection based on [[Class]] detection (using
            Object.prototype.toString())

    -   DOM
        -   Traversal
        -   Node types
        -   Selecting elements (getElementById, getElementsByClassName,
            getElementsByName, querySelector, using XPath to select elements)
        -   DOM Manipulation
        -   innerHTML, advantages & criticism

    -   Events
        -   Binding & Removing event handlers
        -   Traditional event binding
        -   Capturing & bubbling
        -   Event objects
        -   Event delegation
        -   Firing events
        -   Custom events
        -   What if there’s no mouse?

    -   Client side storage
        -   Cookies via HTTP headers, cookies in JavaScript
        -   Problems with cookies
        -   Web storage (localStorage, sessionStorage)
        -   Client-side databases

    -   BOM
        -   The window object, window names
        -   Opening new windows
        -   Cross-window communication
        -   Closing windows, Focusing on windows
        -   Cross-origin window communication
        -   *location* & it’s components
        -   The *history*, *screen* & *navigator* objects
        -   User Agent strings
        -   Why you shouldn’t use browser detection
        -   Built-in modal windows (alert, confirm, prompt)

    -   JavaScript & CSS
        -   CSS modification (className & classList, inline styles)
        -   *CSSStyleDeclaration* objects
        -   The document.styleSheets collection
        -   Switching stylesheets
        -   *StyleSheet* objects
        -   *CSSStyleRule* objects
        -   Computed style, getting the computed style

    -   Best practices
        -   When JS is disabled
        -   Feature detection

### Topics for later expansion

-   Ajax (including data interchange formats, like JSON, other
    async data transmission techniques, including dynamic script
    loading & JSONP, usability concerns)
-   SVG
-   Server side web development
    -   Database driven websites
    -   State & session management
    -   REST

### Assignments

The students were given an assignment for each section of the course:

-   1st assignment: Write an unstyled HTML page for a personal website
-   2nd assignment: Style the simple HTML page with CSS
-   3rd assignment: Handle a CGI form (input and reply)
-   4th assignment: Enhance a web page with various JavaScript behaviours.

#### 1st assignment [[pdf](http://leaverou.me/wdclass/assignment1_en.pdf)] [[files](http://leaverou.me/wdclass/assignment1_en.zip)]

#### 2nd assignment [[pdf](http://leaverou.me/wdclass/assignment2_en.pdf)] [[files](http://leaverou.me/wdclass/assignment2_en.zip)]

#### 3rd assignment [[pdf](http://leaverou.me/wdclass/assignment3_en.pdf)] [[files](http://leaverou.me/wdclass/assignment3_en.zip)]

### Labs

#### 1st lab [[final result](http://leaverou.me/wdclass/lab1/)]

The students had to write an HTML file for the single page personal
website of some fictional web developer and then use CSS to style
it in a certain way. The process was guided, in order to keep all
of them on the same track. The site was carefully designed to
demonstrate many key CSS concepts & features at once.

#### 2nd lab [[final result](http://leaverou.me/wdclass/rating-widget/)] [[JS code](http://leaverou.me/wdclass/rating-widget/rating-widget.js)] [[incomplete JS code](http://leaverou.me/wdclass/rating-widget/rating-widget-incomplete.js)]

The students were given an HTML and a CSS file and they had to fill
in a .js file that had some parts missing (replaced by TODO
comments as placeholders) to complete a very simple ajax rating
widget.

<!--- vi:sw=4:ts=4:ai:et
-->
