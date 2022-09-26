# Hyperlink-bilang-kit (hbk)
     
     Hyperlink-bilang-kit is a python framework for front-end web development . We are in development so things may  change often.
     
     Our aim is to provide a first class experience for front-end developers so that beginner who are absolutely new to
     web development can easily build any kind of website without the knowledge of html, css and javascript.
     
# Quick restart:

    * The following example can give an idea about h bk.
    
### Example :

     from hbk.screen import Screen
     from hbk.button import Button
     from hbk.input import Input
     from hbk.htmltemplate import Html
     
     loginpage = Screen()
     loginpage.addComponent([
           Input('Username :'),
           Input('Password :'),
           Button('Login'),
     ])
     
     Html('testinghbk.html',loginpage).save()
