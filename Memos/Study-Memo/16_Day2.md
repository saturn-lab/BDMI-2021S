# study memo week 2

#### 2017080040 松本博晓 16

---

## pyhon 

![image-20210302141200329](C:\Users\hiroaki\AppData\Roaming\Typora\typora-user-images\image-20210302141200329.png)



split 分割



list/ dictionary/ set

![image-20210302143943831](C:\Users\hiroaki\AppData\Roaming\Typora\typora-user-images\image-20210302143943831.png)



dicitionary can be used in values / keys 分开对应

![image-20210302144112190](C:\Users\hiroaki\AppData\Roaming\Typora\typora-user-images\image-20210302144112190.png)



## 1 想一想做一做 通讯录查询

![image-20210302150145048](C:\Users\hiroaki\AppData\Roaming\Typora\typora-user-images\image-20210302150145048.png)

## 2 想一想做一做 扑克牌大小比较



```python
import random

faces = [2,3,4,5,6,7,8,9,10,11,12,13,14]
my_face = random.choice(faces)
print(my_face)
your_face = random.choice(faces)
print('\n')
print(your_face)
if your_face > my_face:
    print('lose')
elif your_face == my_face:
    print('tie')
else :
    print('win')

```

## 3 想一想做一做 for循环

## 4 想一想做一做 while循环 石头剪刀布

---



## python 函数



def 



匿名函数 Lambda：没有函数名称的函数





__ init __  可以 初始化类



## 1 想一想做一做 面向对象 黑猫跳两次

```
class Cat():
    def __init__ (self,color):
        self.color=color //初始化

    def jump(self):
        print('jump!')

a_cat = Cat('black')
for i in range(2):  //jump 两次
    a_cat.jump()
```

![image-20210302154638001](C:\Users\hiroaki\AppData\Roaming\Typora\typora-user-images\image-20210302154638001.png)