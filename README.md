# Dict_Python
"""
#  Dictionary  = a changeble , unordered collection of unique key:Value paires 
#               Fast becouse of they use hashing , allowi us to accesss a value quickly    
"""
from multiprocessing.sharedctypes import Value


capitals ={'usa':'washingtondc',
            'india':'new dehli',
            'chaina':'beijing',
            'Russia':'moscow'
            
            }

capitals.update({'Germany':'bruven'})# add new
capitals.update({'USA':'Lassvega'})
capitals.pop('china')
capitals.clear()#this is for all clear 



print(capitals['Russia'])
print(capitals.get('germany'))
print(capitals.keys())# to print all the keys in dect
print(capitals.values())#to print all the Values 
print(capitals.items())# print all item 

for key, Value in capitals.items():
    print(key,Value)
