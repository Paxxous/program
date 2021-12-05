# Source file snippet below

```python
#import stuff. You don't need to touch anything here...

from playsound import playsound
import requests
from tkinter import *
from PIL import ImageTk,Image
import threading
import time
import webbrowser
import random


#finished. Begin program





#define some functions for future use



def rock():
  root = Tk()
  root.title
  root.geometry('500x500')
  img = ImageTk.PhotoImage(Image.open('rock.jpeg'))
  img1 = ImageTk.PhotoImage(Image.open('rockraise.jpeg'))
  imag = Label(root, image=img)
  imag.pack()
  root.iconbitmap('thumb.ico')
  root.attributes('-topmost', True)


  def kill():
    root.destroy()

  def update():
    imag.config(image=img1)

  imag.after(1645, update)

  root.after(3000, kill)

  root.mainloop()

def popUp():
  root = Tk()
  root.title('Your cars extended warranty.')
  text = ['REEEEEEEEEEEEEEEEE', 'YOU AER AND IDOIT', 'HAH', 'WHy did you install this lol', 'idoit probably downloaded this from a discord message lol', '*burp*', 'HAH wasted.']
  root.iconbitmap('thumb.ico')
  root.attributes('-topmost', True)

  title = Label(root, text=random.choice(text))
  title.pack()

  root.mainloop()

def boom():
  
  playsound('boom.wav')

webpages = ['https://www.youtube.com/watch?v=8oUUrposxqw', 'https://www.youtube.com/watch?v=XHx2hAu6PTA', 'https://www.youtube.com/watch?v=ameTtKHP5SA', 'https://www.youtube.com/watch?v=_vBVGjFdwk4', 'https://www.youtube.com/watch?v=vysRzAXBByQ']

def spamtabs(v):
  for _ in range(v):
    y = threading.Thread(target=boom, args=())
    y.start()
    webbrowser.open(random.choice(webpages))
    

def susply():
  playsound('sussy.wav')


def susups(v):
  for _ in range(v):
    y = threading.Thread(target=boom)
    y.start()
    x = threading.Thread(target=popUp, args=())
    x.start()

def bothlol():
  susups(100)

def justlol():
  spamtabs(50)

def chaos():
  sounds = ['reverbfart.wav', 'bababooey.wav', 'wetfart.wav']
  while True:
    playsound(random.choice(sounds))


#finish defining programs



#main

#import media

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/umofemclSxKhSSDZ/e.wav')
file = open('boom.wav', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/VfKXZzPXTb1MxKCy/Rock_Eyebrow_Raise_Meme.wav')
file = open('sussy.wav', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/awuFrW2oZevYtiXU/mw1920_sddefault.jpg')
file = open('rockraise.jpeg', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/nAHJVaT6qJbcUIkf/mw1920_tenor.jpg')
file = open('rock.jpeg', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/OtP6uzAcjEQULqzO/amogus.ico')
file = open('thumb.ico ', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/qQ0arDGBkBTNtbwU/reverb.wav')
file = open('reverbfart.wav', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/Dxdfwy1WZXZxM6ea/babooey.wav')
file = open('bababooey.wav', 'wb')
file.write(f.content)

f = requests.get('https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/UvK0dgRxTRibGs9q/wetfart.wav')
file = open('wetfart.wav', 'wb')
file.write(f.content)
file.close()



#file.close()




#okay now thw actual stuf happen



z = threading.Thread(target=susply)
z.start()

x = threading.Thread(target=rock)
x.start()

time.sleep(1.799)

x = threading.Thread(target=chaos)
x.start()

susups(50)

time.sleep(.1)

spamtabs(50)

x = threading.Thread(target=bothlol)
x.start()

x = threading.Thread(target=justlol)
x.start()
```


