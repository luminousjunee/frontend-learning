# HTML Learning Log of p1
In p1 (progress 1), I have learned the following:
<br><br>
- What Hyperlinks are
<br><br>
A hyperlink is a digital reference to data that a user can follow by clicking or tapping a button or link.
<br><br>
**How to create a hyperlink**
<br><br>
＜a＞＜/a＞ (The a inside the tag means anchor.)
<br><br>
To make the text a link, you'll need to add an href attribute inside the opening tag of ＜a＞, which now becomes ＜a href=""＞.
<br><br>
An attribute is typically a name value pair that modifies the behavior of an element. In this case, we're using href, which means "hypertext reference", meaning that the html is referencing something, for example, a link.
<br><br>
Inside the quotes of the href="", you can link a webpage or file.
<br><br>
＜a href=""＞YouTube＜/a＞
<br><br>
By link example, if I wanted the text "YouTube" to be a link to the youtube website, the line of code would become the following below:
＜a href="https://youtube.com/"＞YouTube＜/a＞
<br><br>
Another attribute that you can add by option, is target.
＜a href="https://youtube.com/" target="_blank"＞YouTube＜/a＞
<br><br>
The code of line above would open a new tab with youtube instead of the current tab you're in.
<br><br>
A title attribute displays additional information about an element as a tool tip.
<br><br>
For example, ＜a href="https://youtube.com/" target="_blank" title="Goes to youtube"＞YouTube＜/a＞
<br><br>
With the title attribute (title="Goes to youtube") inside the starting tag, if you hover over the text, it will display a tool tip with the text reading "Goes to youtube".
<br><br>
To add a file to a href, you'll simply need to add the location of the file. For example,
<br><br>
＜a href="lyrics.html" target="_blank" title="Goes to song lyrics"＞Song lyrics＜/a＞
<br><br>
Because my lyrics are in another folder, I'll need to place my location like this: ＜a href="../BroCode Learning/p1/index.html" target="_blank" title="Goes to song lyrics"＞Song lyrics＜/a＞
<br><br>
To email someone using hyperlinks, all you'll need to do is the following:
<br><br>
＜a href="mailto:example@xyz.com" target="_blank" title="Goes to your default email like gmail or hotmail and composes an email to: example@xyz.com"＞Email me＜/a＞
<br><br>
By changing the href to "mailto:email" (you don't need to change the target or title, it's up to you), this href will open your default email like gmail or hotmail and compose an email to "example@xyz.com".
# EXERCISE
By BroCode, my second exercise is to provide a link to the song from inside my song lyrics webpage. I have done this through p1 inside index.html in line 11 through 13.