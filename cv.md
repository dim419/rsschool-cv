# Dmitry Dvoretskov
---
## My Contact Info
---
* Location: Minsk, Belarus
* Phone, Telegram: +375 29 669-60-56
* Email: 6696056@gmail.com
* GitHub: dim419
## About Me
---
At this stage, I work as a specialist in the field of inspection of building structures. The specifics of my work is connected with the implementation of construction drawings, the calculation of the strength of structures. 
My strengths: 
* I always bring my goals to the end. 
* Desire to acquire new knowledge and develop.
## Skills
* HTML
* CSS
* JavaScript (basic knowledge)
* Python (basic knowledge)
* Git/GitHub
* AutoCAD
## Code examples
```
def shape_coefficient1(): 
    """
       Roof snow load shape coefficient
    """
    ang = float(txt0_1.get())
    if ang <= 30:
        mu1 = 0.8
    elif ang < 60:
        mu1 = round(0.8*(60-ang)/30, 3)
    elif ang >= 60:
        mu1 = 0
    txt1_1.delete(0, END)
    txt1_1.insert(INSERT, mu1)
```        
