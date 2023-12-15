# AILearningNote

```python
# 定义装饰器
def ai_decorator(AILearning):
    def wrapper():
        print("Before function call")
        AILearning()
        print("After function call")
    return wrapper

# 使用装饰器
@ai_decorator
def hello_world():
    print("Hello, World!")

# 调用带有装饰器的函数
hello_world()
