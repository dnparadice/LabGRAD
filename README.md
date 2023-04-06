# LabGRAD
This project is an attempt to port the Micrograd project to LabVIEW.

https://github.com/karpathy/micrograd

This project has a similar objective of Micrograd, which is to understand what is happening inside a Neuron in a Neural Net. 

# Requirements 
Before looking at any of the code in this repo, you will want to understand the Micrograd library. This is not too difficult because Andrej Karpathy (the author of Micrograd) has made an excellent video on Micrograd. 

https://www.youtube.com/watch?v=VMj-3S1tku0&t=6892s

# Observations
It's not easy to directly port Python to LabVIEW so the code does not follow exactly 'line for line' even so much as LabVIEW can follow Python 'line for line':
1) The Micrograd project uses Python's ability to pass method pointers to objects. You can't do this in LabVIEW so you have to do some other trick to get the same functionality. 
2) There is a dynamic vs static type issue that comes up in a few spots so even though both projects are Object Oriented, the class objects and methods don't look and function exactly the same. 

# Credits 
Thank you Andrej Karpathy! 
