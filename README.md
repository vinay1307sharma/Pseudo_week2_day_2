Q21. What is printed? 
function modify(x) 
x = x + 10 
return x 
a = 5 
modify(a) 
print(a) 

Q22. Output? 
function update(arr, i) 
arr[i] = arr[i] + 5 
arr = [1, 2, 3] 
update(arr, 1) 
print(arr[1]) 

Q23. Output of the code: 
x = 100 
function check() 
x = 50 
print(x) 
check() 
print(x) 

Q24. What will be the output? 
a = 10 
function test() 
global a 
a = a + 5 
test() 
print(a) 

Q25. Trace the output: 
function modify(x) 
x = x * 2 
return x 
x = 4 
x = modify(x) 
print(x) 

Q26. What is printed? 
x = 5 
function demo(x) 
x = x + 1 
print(x) 
demo(x) 
print(x) 

Q27. Predict the output: 
function add(val) 
val = val + 10 
a = 3 
add(a) 
print(a) 

Q28. What will be the output? 
function fun(x) 
y = x + 10 
return y 
y = 5 
z = fun(y) 
print(y, z) 

Q29. Scope analysis – What’s printed? 
x = 1 
 
function outer() 
    x = 2 
    function inner() 
        print(x) 
    inner() 
 
outer() 
 
Q30. Output? 
x = 10 
 
function show() 
    print(x) 
    x = 20 
 
show() 
 
Q31. Predict the result: 
function increment(x) 
    x = x + 1 
    return x 
 
a = increment(2) 
b = increment(a) 
print(b) 
 
Q32. What’s the final value of x? 
 
x = 10 
function change() 
    x = x + 5 
 
change() 
print(x) 
 
Q33. Trace this code: 
 
val = 2 
 
function mul() 
    val = val * 2 
    return val 
 
print(mul()) 

Q34. Output of this recursive update: 
 
function recUpdate(a) 
    if a > 10 
        return a 
    return recUpdate(a + 2) 
 
print(recUpdate(4)) 

Q35. What is printed? 
function f(a, b) 
    a = a + b 
    b = a - b 
    a = a - b 
    print(a, b) 
 
x = 3 
y = 5 
f(x, y) 
print(x, y)
