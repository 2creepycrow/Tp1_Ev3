# Tp1_Ev3
trying to trasform a testing project to maven
   
   ### In first place clone the project and locate at the folder with the following comands:
   
         $ git clone https://github.com/2creepycrow/Tp1_Ev3.git
         $ cd Tp1_Ev3

   ### Execute the following command to compile the "JunitTestSuite.java", with the path from the  ".jar" of junit. 
   
        $ javac -cp ~/misjars/junit/*:. JunitTestSuite.java 
       
   ### once compiled, we proceed to execute the following command, it will allow us to check if the tests executed correctly, and if its not like that it will show us the errors.
   
        $ java -cp ~/misjars/junit/*:. org.junit.runner.JUnitCore JunitTestSuite
   
   ### it must return us the results:
   
        alumnado@A121PC08:~/Escritorio/git$ java -cp ~/misjars/junit/*:. org.junit.runner.JUnitCore JunitTestSuite
        JUnit version 4.8.1
        .....
        Time: 0,007

        OK (5 tests)
        