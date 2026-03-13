class Stack(object):

    def __init__(self):
        self.stack = []

    def push(self, item):
        self.stack.append(item)
        print "Pushed:", item

    def pop(self):
        if len(self.stack) == 0:
            print "Stack Underflow! Cannot pop."
            return
        item = self.stack.pop()
        print "Popped:", item
        return item


# -------- Main Program --------
s = Stack()

s.push(10)
s.push(20)
s.push(30)

s.pop()
s.pop()
s.pop()
s.pop()    # Underflow example


# STACK-ADT-
Practical program 
