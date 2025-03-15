# Lab 5
## Content Style

- [My website on Pages](https://jefftam79.github.io/lab5/)

### The Content Covered:
1. Style Element 
2.  Font Family
3. Font Size 
4. Font Weight 
5. Font-Style 
6. Font-Variant 
7. Font 
8. Text-Align 
9. Text-Decoration 
10. Text-Transform
11. Text-Indent
12. Margin-Top
13. Margin-Right
14. Margin-Bottom
15. Margin-Left
16. Max-Width
17. Padding
18. Margin
19. Display: Flex
20. Border-Bottom
21. Border-Top
22. Border-Radius
23. Nav Element
23. Nav A
24. Nav Li
25. List-Style-Type
26. Nav Ul
27. Background-Color
28. Display
29. Pseudo-Classes
30. Nav a:link
31. Nav a:visited
32. Nav a:hover
33. Nav a:active

### HTML Tag Cheat Sheet
<table>
    <thead>
        <tr>
            <th>Syntax</th>
            <th>Description</th>
            <th>Example</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <pre><code>&lt;style&gt;&lt;/style&gt;</code></pre>
            </td>
            <td>A tag used to define CSS styles within an HTML document.</td>
            <td>
                <pre><code>&lt;style&gt;
    body {
        background-color: lightgray;
    }
&lt;/style&gt;</code></pre>
            </td>
        </tr>
        <tr>
            <td><code>font-family</code></td>
            <td>Specifies the font of the text.</td>
            <td><pre><code>p { font-family: Arial, sans-serif; }</code></pre></td>
        </tr>
        <tr>
            <td><code>font-size</code></td>
            <td>Defines the size of the font.</td>
            <td><pre><code>h1 { font-size: 24px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>font-weight</code></td>
            <td>Determines the thickness of the font.</td>
            <td><pre><code>strong { font-weight: bold; }</code></pre></td>
        </tr>
        <tr>
            <td><code>font-style</code></td>
            <td>Defines the style of the font (normal, italic, oblique).</td>
            <td><pre><code>em { font-style: italic; }</code></pre></td>
        </tr>
        <tr>
            <td><code>font-variant</code></td>
            <td>Controls text appearance, such as small caps.</td>
            <td><pre><code>p { font-variant: small-caps; }</code></pre></td>
        </tr>
        <tr>
            <td><code>font</code></td>
            <td>Shorthand for setting font-related properties.</td>
            <td><pre><code>p { font: italic bold 16px Arial, sans-serif; }</code></pre></td>
        </tr>
        <tr>
            <td><code>text-align</code></td>
            <td>Aligns text to left, right, center, or justify.</td>
            <td><pre><code>h1 { text-align: center; }</code></pre></td>
        </tr>
        <tr>
            <td><code>text-decoration</code></td>
            <td>Controls text underline, overline, and line-through.</td>
            <td><pre><code>a { text-decoration: none; }</code></pre></td>
        </tr>
        <tr>
            <td><code>text-transform</code></td>
            <td>Changes the capitalization of text.</td>
            <td><pre><code>p { text-transform: uppercase; }</code></pre></td>
        </tr>
        <tr>
            <td><code>text-indent</code></td>
            <td>Indents the first line of a paragraph.</td>
            <td><pre><code>p { text-indent: 20px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>margin-top</code></td>
            <td>Sets the top margin of an element.</td>
            <td><pre><code>div { margin-top: 10px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>margin-right</code></td>
            <td>Sets the right margin of an element.</td>
            <td><pre><code>div { margin-right: 10px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>margin-bottom</code></td>
            <td>Sets the bottom margin of an element.</td>
            <td><pre><code>div { margin-bottom: 10px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>margin-left</code></td>
            <td>Sets the left margin of an element.</td>
            <td><pre><code>div { margin-left: 10px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>max-width</code></td>
            <td>Sets the maximum width an element can be.</td>
            <td><pre><code>div { max-width: 600px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>padding</code></td>
            <td>Sets the space between an element’s content and border.</td>
            <td><pre><code>div { padding: 10px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>margin</code></td>
            <td>Shorthand property for setting margins.</td>
            <td><pre><code>div { margin: 10px 20px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>display: flex</code></td>
            <td>Defines a flex container.</td>
            <td><pre><code>div { display: flex; }</code></pre></td>
        </tr>
        <tr>
            <td><code>border-bottom</code></td>
            <td>Sets the bottom border of an element.</td>
            <td><pre><code>h1 { border-bottom: 2px solid black; }</code></pre></td>
        </tr>
        <tr>
            <td><code>border-top</code></td>
            <td>Sets the top border of an element.</td>
            <td><pre><code>h1 { border-top: 2px solid black; }</code></pre></td>
        </tr>
        <tr>
            <td><code>border-radius</code></td>
            <td>Rounds the corners of an element.</td>
            <td><pre><code>div { border-radius: 10px; }</code></pre></td>
        </tr>
        <tr>
            <td><code>background-color</code></td>
            <td>Sets the background color of an element.</td>
            <td><pre><code>body { background-color: lightblue; }</code></pre></td>
        </tr>
        <tr>
            <td><code>display</code></td>
            <td>Determines how an element is displayed.</td>
            <td><pre><code>div { display: inline-block; }</code></pre></td>
        </tr>
        <tr>
            <td><code>list-style-type</code></td>
            <td>Defines the appearance of list bullets or numbers.</td>
            <td><pre><code>ul { list-style-type: square; }</code></pre></td>
        </tr>
        <tr>
            <td><code>pseudo-classes</code></td>
            <td>Used to define a special state of an element.</td>
            <td><pre><code>a:hover { color: red; }</code></pre></td>
        </tr>
        <tr>
            <td><code>nav a:link</code></td>
            <td>Styles unvisited links in a navigation bar.</td>
            <td><pre><code>nav a:link { color: blue; }</code></pre></td>
        </tr>
        <tr>
            <td><code>nav a:visited</code></td>
            <td>Styles visited links in a navigation bar.</td>
            <td><pre><code>nav a:visited { color: purple; }</code></pre></td>
        </tr>
        <tr>
            <td><code>nav a:hover</code></td>
            <td>Changes the style when the mouse hovers over a link.</td>
            <td><pre><code>nav a:hover { color: red; }</code></pre></td>
        </tr>
        <tr>
            <td><code>nav a:active</code></td>
            <td>Styles the link when it is clicked.</td>
            <td><pre><code>nav a:active { color: green; }</code></pre></td>
        </tr>
    </tbody>
</table>


