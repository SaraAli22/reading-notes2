# Links
Links are created using the a element. Users can click on anything between the opening a tag and the closing /a tag. You specify
which page you want to link to using the href attribute.
![image](https://i1.wp.com/css-tricks.com/wp-content/uploads/2018/09/nested-links.png?ssl=1)

* Links are created using the a element.

* The a element uses the href attribute to indicatethe page you are linking to.

* If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.

 * You can create links to open email programs with an email address in the "to" field.

* You can use the id attribute to target elements within a page that can be linked to.
![image](https://crossfadedotblog.files.wordpress.com/2017/07/table-html-with-links_green-bk.jpg?w=907&h=426&crop=1)
![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQD5gl-mYv4qEJdtQps_wSTSLkEh-aNo2yiPA&usqp=CAU)

# Layout

* div elements are often used as containing elements to group together sections of a page.

* Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

* The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

* Pages can be fixed width or liquid (stretchy) layouts.

* Designers keep pages within 960-1000 pixels wide,and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

* Grids help create professional and flexible designs.

* CSS Frameworks provide rules for common tasks.

* You can include multiple CSS files in one page.

HTML layouts provide a way to arrange web pages in well-mannered, well-structured, and in responsive form or we can say that HTML layout specifies a way in which the web pages can be arranged. Web-page layout works with arrangement of visual elements of an HTML document.

Web page layout is the most important part to keep in mind while creating a website so that our website can appear professional with the great look. You can also use CSS and JAVASCRIPT based frameworks for creating layouts for responsive and dynamic website designing.

![image](https://static.javatpoint.com/htmlpages/images/html-layouts.png)

# Function
Generally speaking, a function is a "subprogram" that can be called by code external (or internal in the case of recursion) to the function. Like the program itself, a function is composed of a sequence of statements called the function body. Values can be passed to a function, and the function will return a value.

Every function in JavaScript is a Function object. See Function for information on properties and methods of Function objects.

To return a value other than the default, a function must have a return statement that specifies the value to return. A function without a return statement will return a default value. In the case of a constructor called with the new keyword, the default value is the value of its this parameter. For all other functions, the default return value is undefined.

The parameters of a function call are the function's arguments. Arguments are passed to functions by value. If the function changes the value of an argument, this change is not reflected globally or in the calling function. However, object references are values, too, and they are special: if the function changes the referred object's properties, that change is visible outside the function.
## Defining functions
 function name([param[, param[, ... param]]]) {
   statements
}

* name
The function name.
* param
The name of an argument to be passed to the function.
* statements
The statements comprising the body of the function.
 var myFunction = function() {
    statements
}

Invoking a Function.
Functions execute when the function is called. This process is known as invocation. You can invoke a function by referencing the function name, followed by an open and closed parenthesis: ().

# 6 Reasons for Pair Programming
![image](data:image/jpeg;base64,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)
## Definition
Pair programming consists of two programmers sharing a single workstation (one screen, keyboard and mouse among the pair). The programmer at the keyboard is usually called the “driver”, the other, also actively involved in the programming task but focusing more on overall direction is the “navigator”; it is expected that the programmers swap roles every few minutes or so.
## Also Known As
More simply “pairing”; the phrases “paired programming” and “programming in pairs” are also used, less frequently
## and now the reasons are :
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness