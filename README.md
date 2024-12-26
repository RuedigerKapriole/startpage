# startpage
a simple startpage for a newtab plugin or just as new startpage in a browser

this html-file is for a new tab or a startpage in generel. if you want to add it, use a newtab-override-plugin in your browser for example. You can change the file as you want. For changing the links and names, change the name inside the <a>-tag so, right here <a href="https://github.com/RuedigerKapriole">*here*</a>. The Link is changeable inside the "" in the href-part of the <a>-tag.

  
The Page could look like this, but you can change the picture/gif and the text.
  
![demo](https://user-images.githubusercontent.com/74026255/123331849-16ad2000-d540-11eb-82c2-71d4286634dd.png)

  
# FAQ
  
How do I change something?
  
  -If you want to change something, you need to download and open the index.html-file with a text-editor. Inside the text-editor, you will replace the text "your-text" with you site-name and the "your-link"-text with you webadress like https://www.github.com/RuedigerKapriole.
  
  
  -If you want to change a color, simply look inside the <style>-tag which starts with "<style>" and ends with "</style>". Inside of this tag, you'll find a line where it says "html {". After this line, look out for background-color which is set to #e4d8cb normaly. You can change this color to every color you want with using a hex-picker-tool in the internet. This will change the color of the background. If you want to change the color of a specific text, you'll need to look inside the <body>-tag for the text you want to change. You need to look for the class="#". Finde the class-name and look for this name inside the <style>-tag. Inside the <style>-tag, you'll then find the class-name and after it a "{". ex.: "misc {". Inside of it you'll find a "color". Change this color hex-code to the color you want.
