
nlist = [2, 3, 5, 6, 7, 12, 90]
found = False
search_term = int(input("Enter a search term: "))  
positions = []

# Loop to search through each data element
for x in range(len(nlist)):
    # Check if the item is in the list
    if search_term == nlist[x]:  
        found = True
        positions.append(x) 

# Output to see if the data element is in the list
if found:
    print(f"{search_term} found in positions: {positions}")  # Changed to search_term
else:
    print("Not found data item.")

    
        
