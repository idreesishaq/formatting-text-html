# formatting-text-html


In this repository I have described some more useful html tags for better control regarding formatting text.
like 
* displaying code 
* ignore spaces and indentation
* start text on a new line 
* subcript
* superscript
* small text
### 1. `<code>`
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

* one more example of css code, to display on the web browser.
```
<p>
    We can write <code> {color:green;} </code> in our CSS, and it will apply to anything up as an elements.
    
</p>
```

### 2. `<br>`
* <br\> tag is for **line break**.
* Sometimes we want line break. but html ignores extra lines. As shown in the below we want each verse to be started at new line. as we have written. but html consider the whole bunch of lines as one paragraph and will display without line breaks. Furthermore, we cannot encapsulate each line within the paragraph element `<p> </p>`. because these are not seperate paragraphs. We just wanna line break at the end of each line, something that browsers will respect.

```
<p>
    Baa, baa black sheep,
    have you any wook?
    Yes sir, yes sir, three bags full!
    One for the master,
    one for the dame,
    and one for the little boy
    who lives down the lane.
</p>


<cite>- Rudyard Kipling</cite>

```
* So, putting `<br>` tag at the end of each line, where we want line breaks.

```
<p>
    Baa, baa black sheep, <br>
    have you any wook? <br>
    Yes sir, yes sir, three bags full! <br>
    One for the master, <br>
    one for the dame, <br>
    and one for the little boy <br>
    who lives down the lane. <br>
</p>


<cite>- Rudyard Kipling</cite>
```


