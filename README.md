Plugin which allows embedding well-formed HTML content in a DITA topic inside a special <foreign outputclass="html-embed"> element.
The plugin works with both DITA OT 1.8 and 2.x.

Example of embedding a YouTube video:

The DITA structure:

    ....
    <foreign outputclass="html-embed"><![CDATA[
                <iframe width="420" height="315" src="https://www.youtube.com/embed/qepRkQxhTXQ" frameborder="0" allowfullscreen="true">
                </iframe>
                ]]></foreign>
    ....
    
is converted in the HTML output to:

      ...........
      <iframe width="420" height="315" src="https://www.youtube.com/embed/qepRkQxhTXQ" frameborder="0" allowfullscreen="true">
      </iframe>
      ............
