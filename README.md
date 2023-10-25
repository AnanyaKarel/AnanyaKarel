def tower_of_hanoi (n, source, auxilliary, target)
n==1 
print(f"move disk 1 from {source}to {target})
tower_of_hanoi (n-1, source, auxilliary, target)
print (f"move {n} from {source} to {target})
tower_of_hanoi (f"move {n-1} from {auxiliary}, {source}, {target}")
