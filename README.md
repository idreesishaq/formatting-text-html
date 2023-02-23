# formatting-text-html


In this repository I have described some more useful html tags for better control regarding formatting text.
like 
* displaying code 
* ignore spaces and indentation
* start text on a new line 
* subcript
* superscript
* small text
1. ### `<code>`
* The code tag is used when we want our code to stand out and should be looked like a code. Then we encapsulated our html or css code between the `<code> </code>`.
* The code tag is an **inline elemnent**.
* The code tag  changes the style of fonts to monospace, thats exactly we want our code to look.
* but using the code tag is not enough as it only switchs the fonts. Therefore to tackle this problem we <br>use html entities like <br>
(< = "\&lt"; and \> = "\&gt;")

**Note: It won't preserve our code in html. it'll execute the html elements**
```
<code>
  <h1>Heading 1</h1>
  <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, </p>
</code>
```

**So instead of less than and greater than sign in html elements we will use html entities.**
```
<code>
  &lt;h1&gt; Heading-1 &lt;/h1&gt;
  &lt;p&gt; Lorem ipsum dolor sit amet, consectetur adipiscing elit, &lt;/p&gt;
</code>
```
This is how html shows the code on the web page instead of being executed.
