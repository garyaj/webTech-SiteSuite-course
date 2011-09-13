-   Introduction
    -   Web application architecture
    -   How the HTTP protocol works

-   A small web application example (an AJAX shopping cart)
    in order for the students to get an idea about how everything clicks together
-   Markup languages
    -   SGML
    -   DTDs
    -   HTML and XHTML
        -   Basic structure of an (X)HTML document
        -   Content model, block vs inline elements
        -   Basic HTML elements
            -   headings & paragraphs
            -   lists (ordered, unordered, definition lists)
            -   tables
            -   grouping elements (div & span)

        -   Doctypes, the HTML5 doctype
        -   The incentives behind XHTML & the future ((X)HTML 5)
        -   (X)HTML Validation
        -   HTML forms
            -   How forms work, GET vs POST
            -   Form controls, shared attributes
            -   The various input types (+ the new ones HTML5 brings)
            -   Other form controls (buttons, <select\> lists, textareas)
            -   Basic form accessibility (labels & fieldsets)

        -   Working with Multimedia (old methods, HTML5 video & audio
            elements, comparison)

    -   XML and XPath, XQuery, XSLT

-   CSS
    -   CSS standards
    -   CSS rules
    -   Validation
    -   Adding CSS to a page (linking/embedding methods)
    -   Media targeting (The media attribute, @media rules, media
        queries)
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
        -   XML namespaces & CSS

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
        -   The *display*property
        -   border
        -   padding
        -   margin

    -   Positioning
        -   The *position*property
        -   Positioning types (absolute, relative, fixed)
        -   z-index
        -   float
        -   Problems with floats, the *clear*property

    -   Generated content
        -   ::before and ::after
        -   Static generated content
        -   Dynamic generated content (attributes & counters)


-   JavaScript
    -   Adding JS to a document
    -   Separation of concerns
    -   A first, annotated, example (a simple script that generates
        tables of content from <h2\> headings)
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

    -   Asynchronous execution
        -   Timeouts & Intervals
        -   Background workers

    -   Graphics creation (canvas)
    -   A brief mention of WebGL (we also showed the video of Google’s
        web based DOOM game)
    -   Best practices
        -   When JS is disabled
        -   Feature detection


-   Regular expressions
-   Ajax (including data interchange formats, like JSON, other
    async data transmission techniques, including dynamic script
    loading & JSONP, usability concerns)
-   SVG
-   Server side web development
    -   PHP (also covering OOP in PHP extensively)
    -   Database driven websites
    -   State & session management
    -   REST
    -   SOAP

-   Web application security

***Note:****For brevity reasons, the lists above do not include introductory stuff such as:*

-   *What’s X?*
-   *A brief history of X*
-   *Why use X?*
-   *etc*

#### Lessons learned

It’s very hard to momentarily change your mindset and try to
imagine that you live in a modern, fully standards-based web
development world, where old browsers, proprietary stuff, hacks and
compatibility workarounds have no place. A world where IE doesn’t
exist. However, it’s the world that all our material assumed, for
the reasons stated above. And it’s beautiful, so much that it
becomes addictive and makes you hate all these bugs &
incompatibilities that we have to face today even more.

### Homework

The students were given 3 assignments throughout the semester, each
covering:

-   1st assignment: HTML, CSS, XPath, XSLT
-   2nd assignment: JavaScript, Ajax, SVG
-   3rd assignment: Server side web dev + CSS, JavaScript, Ajax

These homeworks accounted for 30% of their final grade (10% each),
which probably should have been more.

We searched for exercises on these topics from other universities
but couldn’t find anything, so we made our own. I’ve translated
them, in case someone finds them useful, given that there’s a great
shortage of such material in the intertubes. You can get them
through the links below, along with their complementary files.

#### 1st assignment [[pdf](http://leaverou.me/wdclass/assignment1_en.pdf)] [[files](http://leaverou.me/wdclass/assignment1_en.zip)]

-   I think 1.A and 1.B are excellent exercises to make the
    students fully understand how CSS selectors work and avoid them
    resulting to only use the 4-5 basic ones just because they don’t
    understand the rest (like many web developers do). It’s a pity that
    many of them resulted to online scripts for the conversion (but
    luckily it was easy to spot: These answers were way more verbose
    than the corresponding “handmade” ones, and in some cases even
    incorrect!)
-   I also think 1.C is an excellent exercise for cascading &
    inheritance practice. Some of the cases were even quite tricky (for
    instance, the way specificity works for :not() or how grouping
    works if one of the selectors is invalid) and treated almost all
    factors that someone should know to predict which rule …overrules.
    It’s important however that the student justifies the answer,
    because otherwise they can just test it in a browser and write down
    the result, without understanding why.
-   I’m not sure yet if freeform questions were a good idea, but
    (hopefully) they got them to practice their critical thinking and
    do some research (we hadn’t presented :checked and :lang() in
    class). We didn’t expect many to get the 3rd one right, but we were
    pleasantly surprised.
-   What I like in 3.A is that I believe it enforces the Separation
    of Concerns guideline, since they cannot alter the HTML file
    (something even professionals commonly do to get something done,
    the quick & dirty way…) so they **have** to move all presentation
    to the CSS file. It also contained a quite tricky part: Maintaining
    state without JavaScript, by utilizing the **:checked**
    pseudo-class and some combinators (a technique made popular quite
    recently by [Ryan Seddon](http://www.thecssninja.com/)). Obviously,
    this is not a good way to change views in a photo gallery (too much
    wasted bandwidth), but it was perfect as a CSS exercise. To my
    surprise, more than half of the students got it right, which
    indicates that we probably did a good job explaining CSS Selectors
    ![:)](http://leaverou.me/wp-includes/images/smilies/icon_smile.gif)

#### 2nd assignment [[pdf](http://leaverou.me/wdclass/assignment2_en.pdf)] [[files](http://leaverou.me/wdclass/assignment2_en.zip)]

-   I like exercise 1 because it teaches them how they can take
    somebody else’s work, extend it and make it more generic and
    useful. This is something that’s frequently done in web
    development. By the way, the deviation in the solutions was quite
    interesting. Others had implemented a recursive algorithm, others
    approached it in an Object Oriented manner and others took the
    classic iterative route.
-   Exercise 2 lets them practice event delegation, unobtrusive
    progressive enhancement via JavaScript, decisions to improve
    performance (and still, it’s unbelievable how many students made
    choices that were obviously terrible performance-wise. I still
    remember one script that created another DOM element
    **on every mouseover**!)
-   Exercise 3 combines many of the technologies they learned in
    the previous lectures. It also lets them practice their critical
    thinking by comparing the methods afterwards. Most students picked
    the CSS method, which would also be my choice, for such a simple
    bar chart (however, anything rational got full points, I don’t
    think there’s a correct answer here, it depends on many factors).
-   I like exercise 4 because it introduces them to the concept of
    writing JavaScript that is intended to be used by other developers,
    and not just in a particular project (along with 2 perhaps).
    However, none of the students fully understood what it was about.
    All of them fired the HTTP request when ajaxForm() was called and
    most of them also implemented callback() and errorCallback(), which
    wasn’t supposed to be their job.
-   Exercise 5, besides serving well as regular JavaScript
    practice, it also lets them learn more about cutting edge
    technologies such as **localStorage**, **Web databases** or
    **offline web apps**.

#### 3rd assignment [[pdf](http://leaverou.me/wdclass/assignment3_en.pdf)] [[files](http://leaverou.me/wdclass/assignment3_en.zip)]

In this assignment, the students practiced in PHP, combined
everything else they’ve learned and understood better how
everything clicks together to bring a fully-fledged web application
to life. We didn’t get many submissions, since most students were
busy with other assignments these days but most of the ones we got
were awesome, I had an extremely hard time picking the best one.

#### Lessons learned

-   Most mistakes are not very original: They tend to appear over
    and over again in unrelated assignments. Most of them are caused
    either by ambiguities in the description or because the student
    didn’t bother to read all of it. Also, the most frequent excuse for
    not doing something right is “it wasn’t in the description!”. So,
    they have to be as detailed as possible, including even stuff
    that’s obvious to someone more experienced.
-   Plagiarism is not a myth, but a real and frequent problem.
    Students copy from other students, from scripts posted online and
    from any source they can get their hands on.
    ![:(](http://leaverou.me/wp-includes/images/smilies/icon_sad.gif)
    However, only teaching the standards makes it much easier to spot
    (at least when it comes to copying from the internet) since most
    scripts posted online have to account for browser
    incompatibilities.

### Labs

We only held 3 hands-on lectures (2 hours each), due to time
availability issues of everyone involved in the course. I taught
the first 2 and another TA was responsible for the 3rd one. Details
below:

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

#### Lessons learned

-   Never provide downloadable slides with the things the students
    must write by themselves prior to the lecture. They’ll just
    copy-paste everything from the pdf, even if they have to fix
    spacing afterwards. If you absolutely have to, make sure the text
    is not selectable.
-   It takes students far more time to write code than you planned
    for
-   When the students don’t understand something, most of them
    won’t ask.
    ![:(](http://leaverou.me/wp-includes/images/smilies/icon_sad.gif)
    It’s best if you personally explain things to anyone having
    difficulties, but there’s usually not enough time for that

### Personal aftermath

-   I found out that I **love** teaching. Successfully helping a
    student with a problem they had or something they did not
    understand was sometimes enough to make my day. Preparing material
    for the course –although exhausting– was one of the most
    interesting and creative things I have ever done. Even the actual
    teaching is thrilling. It’s very challenging to try to keep the
    students’ interest, since most of them will resort to chatting with
    their buddies instead of paying attention way more easily than
    professionals would during a conference talk. However, if you
    manage to do so, it can be quite rewarding.
-   I **hate** grading. It’s boring, time-consuming, carries a lot
    of responsibility and you have to ensure every point you deduct is
    justified, because you might have to defend your judgement in case
    a student complains. Sometimes it can also freak you out completely
    (“OMGWTF, how could they understand it so wrong?? Why didn’t they
    ask?”) These strips sum it up perfectly (and with a good dose of
    humor):
