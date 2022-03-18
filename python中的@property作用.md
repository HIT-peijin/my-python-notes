property ——> 属性
我们知道人的身高和臂长大致呈1:1的关系，现在我们想通过一个人的身高求得一个人臂长，可以像下面的方法或得

class Person(object):
    def __init__(self):
        self.height = 175
        
    def arm_length(self):
        return self.height
    
person = Person()
person.arm_length()
