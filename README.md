# dhanush
helo
2

3
--- greatest of three numbers ---
4

5
#!/bin/bash
6
echo "Enter the first number:"
7
read a
8
echo "Enter the second number:"
9
read b
10
echo "Enter the third number:"
11
read c
12
if [ $b -gt $a ] && [ $b -gt $c ]
13
then
14
echo "The Greater Number is:" $a
15
elif [ $b - gt $a ] && [ $b -gt $c ]
16
then
17
echo "The greater Nmuber is:" $b
18
else
19
echo "The Greater Number is:" $c
20
fi
21

22
--- summation of "N" numbers---
23

24
#!bin/bash
25
echo "enter the limit:"
26
read a
27
sum = 0
28
for ((i=0;i<=a;i++))
29
do
30
sum=$((sum+i))
31
done
32
echo "Sum upto" $a "Numbers is:"$sum}
33

34

35
--- Arithmetic Operations ---
36

37
#!/bin/bash
38
echo "Arithmetic Operation you want to perform :"
39
read n
40
echo "Enter a number 1:"
41
read a
42
echo "Enter a number 2:"
43
read b
44
if [ $n == 1 ]
45
then
46
ans=expr $a + $b
47
echo "$a +$b = $ans"
48
elif [ $n == 2 ]
49
then
50
ans=expr $a - $b
51
echo "$a - $b = $ans"
52
elif [ $n == 3 ]
53
then
54
ans = expr $a /* $b
55
echo "$a x $b = $ans"
56
elif [ $n == 4 ]
57
then
58
ans=expr $a / $b
59
echo "$a / $b = $ans"
60
fi
61

62
--- factorial ---
63

64

65
#!bin/bash
66
echo "Enter a Number:"
67
read n
68
fact=1
69
for ((i=1;i<n+1;i++))
70
do
71
fact=$((fact*i))
72
done
73
echo "Factorial of" $n "is:" $fact
74

75

76
--- fibonacci ---
77

78
#!bin/bash
79
echo "limit:"
80
read n
81
a=0
82
b=1
83
for ((i=0;i<n;i++))
84
do
85
echo -n " $a"
86
fibo=$((a+b))
87
a=$b
88
b=$fibo
89
done
