# Styling webpages

### 1. Why CSS?
>CSS is a language that describes the style of an HTML document.
>CSS describes how HTML elements should be displayed.

### 2. How to add CSS to HTML?
>Explain different ways you can add css to html code.

### 3. Give examples for **CSS Selectors**
>CSS selectors are used to "find" (or select) HTML elements based on their element name, id, class, attribute, and more.


**The element Selector**

>You can select all ```<p>``` elements on a page like this (in this case, all ```<p>``` elements will be center-aligned, with a red text color):

```CSS
p {
  text-align: center;
  color: red;
}
```

**The id Selector**

>To select an element with a specific id, write a hash (#) character, followed by the id of the element.

```CSS
#para1 {
  text-align: center;
  color: red;
}
```

**The class Selector**

>To select elements with a specific class, write a period (.) character, followed by the name of the class.

```CSS
.center {
  text-align: center;
  color: red;
}
```

### 4. CSS Combinators

>A combinator is something that explains the relationship between the selectors.

+ Explain different CSS Combinators

+ For example, there are four different combinators in CSS:
    + descendant selector (space)
    + child selector (>)
    + adjacent sibling selector (+)
    + general sibling selector (~)

+ What are Pseudo-classes? Explain syntax.


### 6. What is Specificity?

>If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out.
 
+ Explain Specificity Hierarchy, show how to calculate Specificity.
+ Explain Specificity Rules.

### 5. Explain Box model in CSS

+ What is CSS Box Model?
>All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.
+ Explain why is it important?
+ Explain concepts like Padding, Border and Margin with examples.
+ illustrate examples using inspector tool.

+ Exlpain CSS position Property, like position, left, top, 
+ illustrate 
```CSS
position: static|absolute|fixed|relative|sticky|initial|inherit;
```

+ CSS Box Sizing
    + What is CSS Box Sizing
    + What happens without the CSS box-sizing Property?
    + With the CSS box-sizing Property?