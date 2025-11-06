import time
import random
nlist = [sum(random.randint(1, 5) for _ in range(i)) for i in range(1, 1000)]
print(nlist)
start = time.time()
search_term = int(input("Enter a search term: "))
found = False
position = []

# Loop to search through each data element
for x in range(len(nlist)):
    # Check if the item is in the list
    if search_term == nlist[x]:  
        found = True
        position.append(x)

# Output to see if the data element is in the list
if found:
    print(f"{search_term}found in the position:{position}")  
else:
    print(f"{search_term}not found in the data list.")

end = time.time()
print(f"Time taken: {end-start}second")

    
        

