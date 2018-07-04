import matplotlib.pyplot as plt
import csv 
import numpy as np
from pylab import *
from matplotlib.font_manager import FontProperties

i=0
x=[42.7, 16.4, 47.2, 42.4, 52.4]
y=[42.23, 42.23, 42.23, 42.23, 42.23]
n=['Teaching','Int. Outlook','Research','Citation','IndustryInc']
fig, ax = plt.subplots()
ax.scatter(y, x)
ax.set_xlim(0,100)
ax.set_ylim(0,100)

for i, txt in enumerate(n):
    ax.annotate(txt, (y[i],x[i]))
plt.xlabel('IISc Overall', fontsize=16)
plt.ylabel('IISc-Metrics', fontsize=16)
plt.plot([0, 100], [0, 100], 'r', lw=1)
plt.show()

