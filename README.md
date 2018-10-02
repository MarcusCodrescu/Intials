# Intials
from random import *

melody = []
chords = []

CMP = ['c','d','e','g','a','r','r']
CMC = ['C','Dm','Em','F','G','Am']

length = 20
for i in range(length):
  if i%4 == 0:
    c = randint(0,len(CMC)-1)
    chords.append(CMC[c])
  r = randint(0,len(CMP)-1)
  melody.append(CMP[r])
  
print melody
print chords

n = 20
l = [randint(0,n) for i in range(n)]
print l
