##### Plagiarised from Lea Verou's [Organizing a university course on modern Web development](http://leaverou.me/2010/07/organizing-a-university-course-on-modern-web-development/)

### Modern web technologies

**Objectives:** to explain, demonstrate and teach the skills of modern web development technologies<br />
**Process:** There are 4 parts to the course: HTML, CSS, Perl and JavaScript. Each part builds on the
             skills acquired in the previous part. There are 6 (usually 1.5 hour) sessions in each part
             beginning with a short lecture, followed by demonstration of the
             technologies discussed, followed by student practice in applying
             the technologies to a web page.<br />
**Outcome:** Student can create and/or enhance an HTML web page with technologies such as HTML, CSS, Perl, JavaScript.

-   **Introduction**

    **Objectives:** to give a simple explanation of how the web works<br />
    **Process:** Lecture with slides; student explores web page via browser<br />
    **Outcome:** Student can open an HTML document in a browser as source code
                    and name or indicate the various features of the document.

    -   Web application architecture
    -   How the HTTP protocol works

-   **A small web application example** (an AJAX shopping cart)
    in order for the students to get an idea about how everything clicks together
    
    **Objectives:** to give a more detailed explanation of how the web works<br />
    **Process:** Lecture with slides; student explores web page via browser<br />
    **Outcome:** Student can open an HTML document and indicate the
                 various parts of the document.

-   **HTML(5)**

    **Objectives:** to explain and demonstrate sufficient information about the
                structure and content of an HTML document to allow a student to create
                and deploy a simple HTML web page on a web server.<br />
    **Process:** Lecture with slides; demonstration; student explores and edits simple web pages via browser<br />
    **Outcome:** Student can create and deploy a simple, unstyled, HTML document to a web server for display 
                in a browser. 

    -   Basic structure of an HTML document

        **Objectives:** to explain the structure of an HTML document<br />
        **Process:** Lecture with slides; student creates a simple web page via browser<br />
        **Outcome:** Student can create a simple HTML document and display it
                on a browser

    -   Content model, block vs inline elements

        **Objectives:** to explain how the content model works and the
            differences between block and inline elements<br />
        **Process:** Lecture with slides; demonstration of online document;
                     student adds block and inline elements to existing
                     document<br />
        **Outcome:** Student can create a simple HTML document containing block
            and inline elements

    -   Basic HTML elements

        **Objectives:** to explain and demonstrate some HTML display elements<br />
        **Process:** Lecture; demonstration ; student creates an HTML
                document containing these elements and explores their effects<br />
        **Outcome:** Student is able to create and display an HTML document
                containing the basic HTML display elements.

        -   headings & paragraphs
        -   lists (ordered, unordered, definition lists)
        -   tables
        -   grouping elements (div & span)

    -   Doctypes, the HTML5 doctype
        -   A brief history of HTML
        -   Modern simplification
    -   HTML Validation

        **Objectives:** to explain why validation is important in HTML<br />
        **Process:** Lecture with slides; student runs a validator on a simple
                web page via browser and makes corrections until valid.<br />
        **Outcome:** Student can create a valid HTML document.

        -   What is validation, how to do it, why we do it.

    -   HTML forms

        **Objectives:** to explain HTML forms and the various form elements<br />
        **Process:** Lecture with slides; student creates a simple web form<br />
        **Outcome:** Student can create a simple web form and run it

        -   How forms work, GET vs POST
        -   Form controls, shared attributes
        -   The various input types (+ the new ones HTML5 brings)
        -   Other form controls (buttons, <select\> lists, textareas)
        -   Basic form accessibility (labels & fieldsets)

-   **CSS**

    **Objectives:** to explain and demonstrate Cascaded Style Sheets<br />
    **Process:** Lecture with slides; demonstration; student explores CSS elements in a web page via browser<br />
    **Outcome:** Student can explain or indicate in HTML documents CSS selectors, inheritence, the box model, CSS properties;
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

    **Objectives:** to impart a rudimentary knowledge of the Perl scripting
        language; to explain and demonstrate a simple Perl CGI script
        handler.<br />
    **Process:** Lecture with slides; demonstration; student explores the
        effects of changes on a simple Perl CGI script.<br />
    **Outcome:** Student can write a simple Perl script to solve an
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

    **Objectives:** to demonstrate and explain the syntax and properties of
        JavaScript in an HTML document<br />
    **Process:** Lecture with slides; demonstration; student explores JS in a web page via browser<br />
    **Outcome:** Student can add Javascript to an existing HTML to implement
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

Students are to complete an assignment for each section of the course:

-   1st assignment: Write an unstyled HTML page for a personal website
-   2nd assignment: Style the simple HTML page with CSS
-   3rd assignment: Handle a CGI form (input and reply)
-   4th assignment: Enhance a web page with various JavaScript behaviours.

#### 1st assignment [[pdf](http://leaverou.me/wdclass/assignment1_en.pdf)] [[files](http://leaverou.me/wdclass/assignment1_en.zip)]

#### 2nd assignment [[pdf](http://leaverou.me/wdclass/assignment2_en.pdf)] [[files](http://leaverou.me/wdclass/assignment2_en.zip)]

#### 3rd assignment [[pdf](http://leaverou.me/wdclass/assignment3_en.pdf)] [[files](http://leaverou.me/wdclass/assignment3_en.zip)]

### Labs

#### 1st lab [[final result](http://leaverou.me/wdclass/lab1/)]

Students write an HTML file for the single page personal
website of some fictional web developer and then use CSS to style
it in a certain way. The process is guided. The site is designed to
demonstrate many key CSS concepts & features at once.

#### 2nd lab [[final result](http://leaverou.me/wdclass/rating-widget/)] [[JS code](http://leaverou.me/wdclass/rating-widget/rating-widget.js)] [[incomplete JS code](http://leaverou.me/wdclass/rating-widget/rating-widget-incomplete.js)]

Students are given an HTML and a CSS file and they are to fill
in a .js file that has some parts missing (replaced by TODO
comments as placeholders) to complete a very simple ajax rating
widget.

<!--- vi:sw=4:ts=4:ai:et
-->
