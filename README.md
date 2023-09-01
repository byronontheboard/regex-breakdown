# __<p style="color: #FFC0CB">Matching REGEX Hex Values</p>__

## Acceptance Criteria

### ***GIVEN*** a regex tutorial:
***WHEN*** I open the tutorial,
- [x] ***THEN*** I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile.

***WHEN*** I click on the links in the table of contents,
- [x] ***THEN*** I am taken to the corresponding sections of the tutorial.

***WHEN*** I read through each section of the tutorial,
- [x] ***THEN*** I find a detailed explanation of what a specific component of the regex does.

***WHEN*** I reach the end of the tutorial,
- [x] ***THEN*** I find a section about the author and a link to the author’s GitHub profile.

----
## __<p style="color: #FFC0CB">What is REGEX?</p>__
    REGEX(otherwise known as a regular expression) is a character sequence that can match specific patterns of text(usually used to validate specific pattern or strings). 

    These regular expressions utilize standard letters, numbers and general characters, as well as special characters of text.

### __<p>Using this REGEX for reference: <span style="color: #FFC0CB">/^#?([a-f0-9]{6}|[a-f0-9]{3})$/</span></p>__  

    Here we will be discussing the regular expression mentioned above, and how it can be utilized to match a Hex Value with its REGEX Components.

    Below I will give a brief breakdown of each of these REGEX Components in order to provide a better understanding on this topic.

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
- [About Me](https://github.com/byronontheboard/regex-breakdown/blob/main/README.md#about-me)
----
## __<p style="color: #FFC0CB">REGEX Components:</p>__

### *<p style="color: #FFC0CB">Anchors</p>*
    When it comes to the Anchors in a REGEX string, we will be specifically looking at the caret(^), and the dollar($).
    
    The caret(^) anchor will represent the beginning of the string. 
    
    The dollar($) anchor will represent the end of the string.
<br>

    Thus, everything in between ^ and $ will be what the REGEX engine will find.  

### *<p style="color: #FFC0CB">Quantifiers</p>*
    When it comes to the Quantifiers in a REGEX string, we will be specifically looking at the question(?), and the braces({n}).

    The question(?) quantifier will represent a conditional within the REGEX, that being that it will match any preceding character either 0 or 1 time(s).

    The braces({n}) quantifier will simply represent the number of characters that we will require.

### *<p style="color: #FFC0CB">OR Operator</p>*
    When it comes to the OR(|) Operator regarding this specific REGEX, the OR(|) is telling the it to either look for a Hex Value consisting of {6} characters OR of {3}. 

### *<p style="color: #FFC0CB">Character Classes</p>*
    When it comes to the Character Classes for this REGEX, you will want to take a look at the [a-f0-9].
<br>

    This section indictates that the characters should be consisting of letters from a to f and 0 to 9.

    Letters(a-f): a, b, c , d, e, & f.

    Numbers(0-9): 0, 1, 2, 3, 4, 5, 6, 7, 8, & 9.

### *<p style="color: #FFC0CB">Flags</p>*
    When it comes to Flags with REGEX, they are basically for advanced searching. For this example, the carot(^) and dollar($) permits the expression to cross mulitple lines of code.

### *<p style="color: #FFC0CB">Grouping and Capturing</p>*
    When it comes to Grouping and Capturing for an expression, we use the parenthese(()). The parenthese groups together the regular expression between them.

    For our example, the carot(^) and dollar($) also are key components to capturing and grouping this expression as well.

### *<p style="color: #FFC0CB">Bracket Expressions</p>*
__<p>Refering back to our snippet: <span style="color: #FFC0CB">/^#?([a-f0-9]{6}|[a-f0-9]{3})$/</span></p>__ 

    When it comes to Bracket Expressions with our example, we are sprecifically looking at the:

    [a-f0-9]

    This Bracket Expression is indicating that we are looking for two strings that include two Character Classes(as covered earlier) regardin the alphabet(a-f) and integers(0-9).

### *<p style="color: #FFC0CB">Greedy and Lazy Match</p>*
    When it comes to Greedy and Lazy matches, it is actually pretty straightforward in terms of understanding. 

    Greedy: This means to search for a match with the longest possible string. It is also good to know that quantifiers in general, are Greedy by default.

    Lazy: This means to search for a match with the shortest possible string.
----
## __<p style="color: #FFC0CB">About Me</p>__

My name is __Byron Thomas__, and I am currently enrolled in the __UC Davis Coding Bootcamp__. 
<br>
If you'd like to follow more of my journey on becoming a Full Stack Web Developer, please feel free to checkout my GitHub at __[byronontheboard](https://github.com/byronontheboard)__.

### *<p style="color: #FFC0CB">GitHub</p>*
[![My Skills](https://skillicons.dev/icons?i=github)](https://github.com/byronontheboard)
