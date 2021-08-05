def match(a, b):
    for i in range(min(len(a), len(b))):
        if a[i] != b[i]:
            return i
    return min(len(a), len(b))

n = int(input())
a = []
for _ in range(n):
    a.append(input().strip())


substring = a[0]
l = tuple(map(lambda x : match(substring, x), a[1:]))
print(substring[:min(l)])
