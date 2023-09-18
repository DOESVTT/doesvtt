# How to maintain the github page

## Add new pages

1. add all new pages as .md file under the ./docs folder.
2. Add the new page name in the mkdocs.yml page
   1. nav: <newfilename>.md
3. commit your changes and the github page should do the rest

## Add new figures

1. all figures should go under the ./assets folder

2. Make sure that in the md file you are uploading, you refer to it as 

   ```markdown
   ![myimage](assets/myimage.svg)
   ```

3. wait for a while that github compiles all the file and the pages should be updated automatically

### Exception

In case you have dynamic links inside your .svg images, you cannot embed the picture as previously mentioned, you would need to copy the xml code from your svg file directly in your markdown file (right click on your svg file and open it in e.g. notepad or similar text editor) . then copy the code from <svg > 

## Embed youtube video

You can embed any youtube videos (preferably that we have produced) within the wiki pages.

Copy/pase the code below in your md file (or in the our_tools.md) and change the link of the video you want to embed into landing pages.

```markdown
![type:video](https://www.youtube.com/embed/Wnd3roUk2IE) 
```

