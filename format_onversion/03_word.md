# Convert to A WORD Document

## Copy and Paste

After exporting as an HTML document, you can manually copy the content of the HTML page (in your browser), paste it into a WORD document, and save it.


## Use a Tool

You need to install a Markdown editor first. Taking the Pandoc as an example, open the command line mode, go to the directory where the Markdown document is located, and execute the following command to convert the current Markdown document to a Word document:

```
pandoc -o hello.html hello.md
```