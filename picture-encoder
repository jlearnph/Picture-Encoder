#JLearnPH

from PIL import ImageGrab
from datetime import datetime
import os

try:
    im = ImageGrab.grabclipboard()
    date_now = str(datetime.now()).replace(':','-').split('.')[0]
    #PATH WHERE THE CURRENT FILE IS
    im.save(f'{os.path.dirname(os.path.abspath(__file__))}/{str(date_now)}.png','PNG') 
    #path = r'ENTER CUSTOM PATH HERE'
    #im.save(f'{path}/{str(date_now)}.png','PNG')
except:
    pass
