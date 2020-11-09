import collections
s = "anappleisnotatomato"
print(collections.Counter(s).most_common(1)[0])
