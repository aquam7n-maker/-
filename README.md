
# اولین برنامه پایتون - چاپ Hello, World!
print("Hello, World!")

# اجرای دستور print در خط فرمان پایتون
print("Hello, World!")

# استفاده از تورفتگی در دستور if
if 5 > 2:
    print("Five is greater than two!")

# کد با خطای تورفتگی (نمونه خطا)
# if 5 > 2:
# print("Five is greater than two!")  # این خطا می‌دهد

# نمونه‌های مختلف تورفتگی
if 5 > 2:
    print("Five is greater than two!")

if 5 > 2:
    print("Five is greater than two!")

# نمونه کد با خطای تورفتگی
# if 5 > 2:
#     print("Five is greater than two!")
#         print("Five is greater than two!")  # این خطا می‌دهد

# تعریف متغیرها در پایتون
x = 5
y = "Hello, World!"

# استفاده از کامنت‌ها
# This is a comment
print("Hello, World!")

print("Hello, World!")  # This is a comment

# کامنت برای جلوگیری از اجرای کد
# print("Hello, World!")
print("Cheers, Mate!")

# کامنت چند خطی
# This is a comment
# written in
# more than just one line
print("Hello, World!")

# استفاده از رشته چندخطی به عنوان کامنت
"""
This is a comment written in more than just one line
"""
print("Hello, World!")

# تعریف و تغییر نوع متغیرها
x = 5
y = "John"
print(x)
print(y)

x = 4      # x از نوع int است
x = "Sally"  # x اکنون از نوع str است
print(x)

# تبدیل نوع (Casting)
x = str(3)    # x برابر '3' خواهد بود
y = int(3)    # y برابر 3 خواهد بود
z = float(3)  # z برابر 3.0 خواهد بود

print(x)
print(y)
print(z)


# دریافت نوع داده متغیرها
x = 5
y = "John"
print(type(x))
print(type(y))


# تعریف رشته با نقل قول تکی و دوتایی
x = "John"
y = 'John'
print(x)
print(y)


# حساسیت به حروف بزرگ و کوچک
a = 4
A = "Sally"
print(a)
print(A)


# نام‌های متغیر قانونی
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"


# نام‌های متغیر چندکلمه‌ای
myVariableName = "John"  # Camel Case
MyVariableName = "John"  # Pascal Case
my_variable_name = "John"  # Snake Case


# اختصاص چندین مقدار به چندین متغیر
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)


# اختصاص یک مقدار به چندین متغیر
x = y = z = "Orange"
print(x)
print(y)
print(z)


# باز کردن (Unpacking) یک مجموعه
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)


# خروجی متغیرها
x = "Python is awesome"
print(x)

x = "Python"
y = "is"
z = "awesome"
print(x, y, z)

x = "Python"
y = "is"
z = "awesome"
print(x + y + z)

