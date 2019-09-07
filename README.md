# TEST-A-STATIC-HTML-PAGE
Using any python test framework, write a test that makes sure that https://www.google.com/ is up. The goal is not to test the content of the page but rather make sure that the page is available.  Provide instructions how to run your test. Part of this assignment is to see how you would hand off production code to your fellow engineers. Your solution will be reviewed by the engineers you would be working with if you joined Also Energy. We are interested in seeing your real-world design, coding, and testing skills. If you have any questions, please, email them to the person who sent you the challenge

# write-html.py

f = open('helloworld.html','w')

message = """<html>
<head></head>
<body><p>Hello World!</p></body>
</html>"""

f.write(message)
f.close()
Mac Instructions

# write-html-2-mac.py
import webbrowser

f = open('helloworld.html','w')

message = """<html>
<head></head>
<body><p>Hello World!</p></body>
</html>"""

f.write(message)
f.close()

#Change path to reflect file location
filename = 'file:///Users/username/Desktop/programming-historian/' + 'helloworld.html'
webbrowser.open_new_tab(filename)

# write-html-2-windows.py

import webbrowser

f = open('helloworld.html','w')

message = """<html>
<head></head>
<body><p>Hello World!</p></body>
</html>"""

f.write(message)
f.close()

webbrowser.open_new_tab('helloworld.html')
