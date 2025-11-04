
#linear search
nlist = [2, 3, 5, 6, 7, 12, 90]
found = False
searchterm = int(input("Enter a search term"))

#create a loop to search through each data
for x in range(len(nlist)):
    # check to see if the item is in the list
    if (searchterm == nlist[x]):

        found = True
# Outputs to see if the data element is in the list      
if (found == True):
    print("found data item")
else:
    print("not found data item")
    
        
        
    
