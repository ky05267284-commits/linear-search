
#linear search
nlist = [2, 3, 5, 6, 7, 12, 90]
found = False
count = 0
searchterm = int(input("Enter a search term"))
positions = []
#create a loop to search through each data
for x in range(len(nlist)):
    # check to see if the item is in the list
    if (searchterm == nlist[x]):
        found = True
        count += 1
        positions.append(x)

# Outputs to see if the data element is in the list      
if (found == True):
    print(f"Count {count} occurrences of {searchterm} found in positions {positions}")

else:
    print("not found data item")
    
        
