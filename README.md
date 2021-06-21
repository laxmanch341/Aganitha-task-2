# Aganitha-task-2
class X:

    def __init__(self):
    
        self.name=self.__class__.__name__

        
    def execute(self):
        print(self.name)
        

    def shutdown(self):
        print(self.name)



obj=X()

obj.execute()

obj.shutdown()

    
        
