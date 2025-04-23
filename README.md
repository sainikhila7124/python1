#write a program to swap two variables using AND and OR with a feasable empty bucket
a=2
b=1
t=a
a= (a|b) &b
b= (t|a) &t
print(a)
print(b)

output: 1
        2
----------------------------
#write a program to swap two variables using dictionaries
d = {'a' : 1, 'b' : 2}
d['a'],d['b'] = d['b'],d['a']
print(d)

output : {'a': 2, 'b': 1}
