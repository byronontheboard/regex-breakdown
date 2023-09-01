# __<p style="color: #FFC0CB">Matching Regex Hex Values</p>__

## __<p style="color: #FFC0CB">Summary<p>__
__<p>Using this Regex for reference: <span style="color: #FFC0CB">/^#?([a-f0-9]{6}|[a-f0-9]{3})$/</span></p>__  

    Here we will be discussing the regular expression mentioned above, and how it can be utilized to match a Hex Value with its Regex Components.

    Below I will give a brief breakdown of each of these Regex Components in order to provide a better understanding on this topic.

----
## __<p style="color: #FFC0CB">Table of Contents</p>__

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)
----
## __<p style="color: #FFC0CB">Regex Components</p>__

### *<p style="color: #FFC0CB">Anchors</p>*
    When it comes to the Anchors in a Regex string, we will be specifically looking at the caret(^), and the dollar($).
    
    - The caret(^) anchor will represent the beginning of the string. 
    
    - The dollar($) anchor will represent the end of the string.
<br>

    Thus, everything in between ^ and $ will be what the Regex engine will find.  
<br>

----
### *<p style="color: #FFC0CB">Quantifiers</p>*
    When it comes to the Quantifiers in a Regex string, we will be specifically looking at the question(?), and the braces({n}).

    - The question(?) quantifier will represent a conditional within the Regex, that being that it will match any preceding character either 0 or 1 time(s).

    - The braces({n}) quantifier will simply represent the number of characters that we will require.

----
### *<p style="color: #FFC0CB">OR Operator</p>*
    When it comes to the OR(|) Operator regarding this specific Regex, the OR(|) is telling the it to either look for a Hex Value consisting of {6} characters OR of {3}. 

----
### *<p style="color: #FFC0CB">Character Classes</p>*
    When it comes to the Character Classes for this Regex, you will want to take a look at the [a-f0-9].
<br>

    This section indictates that the characters should be consisting of letters from a to f and 0 to 9.

    - Letters(a-f): a, b, c , d, e, & f.

    - Numbers(0-9): 0, 1, 2, 3, 4, 5, 6, 7, 8, & 9.

----
### *<p style="color: #FFC0CB">Flags</p>*
    When it comes to Flags with Regex, they are basically for advanced searching. For this example, the carot(^) and dollar($) permits the expression to cross mulitple lines of code.

----
### *<p style="color: #FFC0CB">Grouping and Capturing</p>*
    When it comes to Grouping and Capturing for an expression, we use the parenthese(()). The parenthese groups together the regular expression between them.

    For our example, the carot(^) and dollar($) also are key components to capturing and grouping this expression as well.

----
### *<p style="color: #FFC0CB">Bracket Expressions</p>*
__<p>Refering back to our snippet: <span style="color: #FFC0CB">/^#?([a-f0-9]{6}|[a-f0-9]{3})$/</span></p>__ 

    When it comes to Bracket Expressions with our example of Hex Values, 
----
### *<p style="color: #FFC0CB">Greedy and Lazy Match</p>*

----
### *<p style="color: #FFC0CB">Boundaries</p>*

----
### *<p style="color: #FFC0CB">Back-references</p>*

----
### *<p style="color: #FFC0CB">Look-ahead and Look-behind</p>*

----
## __Author__

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
