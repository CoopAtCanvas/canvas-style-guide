#CSS Code Standards


## Table of contents

1. [Principles](#principles)
2. [Whitespace](#whitespace)
3. [Formatting](#formatting)
4. [Formatting](#comments)


<a name="principles"></a>
##1. Principles

> "Part of being a good steward to a successful project is realizing that
> writing code for yourself is a Bad Idea™. If thousands of people are using
> your code, then write your code for maximum clarity, not your personal
> preference of how to get clever within the spec." - Idan Gazit

* Don't try to prematurely optimize your code; keep it readable and understandable.
* All code in any code-base should look like a single person typed it, even when 
  many people are contributing to it.
* Strictly enforce the agreed-upon style.
* If in doubt when deciding upon a style use existing, common patterns.


<a name="whitespace"></a>
## 2. Whitespace

* Configure your IDE to use soft-tabs with a two space indent. Spaces are the only 
  way to guarantee code renders the same in any person's environment.
* Add a space after the : in property declarations.
* Separate each ruleset by a blank line.
* Place individual selectors on a single line.
* Place closing braces of selectors on their own line.
* Include a space after each comma in comma-separated property or function values.
* Place all selectors on their own line for readability and more accurate error handling.
* Large blocks of single declarations can use a single-line format. In this case, a 
  space should be included after the opening brace and before the closing brace.

<a name="formatting"></a>
## 3. Formatting

* Always use #HEX color codes, unless using rgb/rgba.
* Do not specify units for 0 values.
* Try to limit use of shorthand declarations to instances where you must explicitly set 
  all the available values.
* Arrange your selector’s properties in alphabetical order. This will ensure a simple 
  and intuitive arrangement that is easily recognisable, simple to locate properties, 
  and easy to recognize duplicates on     long selectors. Sublime: ctrl + F5
* Use px for font-size, because it offers absolute control over text. Additionally, 
  unit-less line-height is preferred because it does not inherit a percentage value of 
  its parent element, but instead is     based on a multiplier of the font-size.
* Use ems for all other values.
* Use double (“”) rather than single (‘’) quotation marks

<a name="comments"></a>
## 4. Comments 

```css
/* ==========================================================================
   Section comment block
   ========================================================================== */

/* Sub-section comment block
   __________________________________________________________________________ */

/* Basic comment */
```
