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
   ![myimage](.\assets\myimage.svg)
   ```

   

