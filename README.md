# my-githab
just testing githab
### 1. پایتون - تولید ASCII Art (شکل با متن)
```python
# ascii_art.py
def ascii_heart():
    heart = """
      **     **
    ****** ****** 
   ***************
    *************
     ***********
      *********
       *******
        *****
         ***
          *
    """
    print(heart)

if __name__ == "__main__":
    ascii_heart()
```

---

### 2. پایتون - ماشین حساب ساده
```python
# calculator.py
def calc():
    print("ماشین حساب ساده")
    a = float(input("عدد اول: "))
    op = input("عملگر (+, -, *, /): ")
    b = float(input("عدد دوم: "))

    if op == "+":
        print("نتیجه:", a + b)
    elif op == "-":
        print("نتیجه:", a - b)
    elif op == "*":
        print("نتیجه:", a * b)
    elif op == "/":
        if b != 0:
            print("نتیجه:", a / b)
        else:
            print("تقسیم بر صفر مجاز نیست!")
    else:
        print("عملگر نامعتبر است.")

if __name__ == "__main__":
    calc()
```

---

### 3. HTML + CSS - صفحه خوش‌آمدگویی
```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <title>خوش آمدید</title>
    <style>
        body {
            background-color: #f2f2f2;
            text-align: center;
            font-family: sans-serif;
        }
        h1 {
            color: #ff5733;
        }
    </style>
</head>
<body>
    <h1>به صفحه من خوش آمدید!</h1>
    <p>این یک صفحه ساده HTML است.</p>
</body>
</html>
```

---

### 4. جاوااسکریپت - نمایش ساعت زنده
```javascript
// clock.js
setInterval(() => {
    const now = new Date();
    console.clear();
    console.log("ساعت:", now.toLocaleTimeString());
}, 1000);
```
