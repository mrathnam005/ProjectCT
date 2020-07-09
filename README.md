# ProjectCT
Sample demo project for learning 

class HelloWorld{

public static void main(String[] arg){
  System.out.println("HI Manirathnam");
  
   }
   

interface Vehicle{

 public void run();
 }
 
 class Bus implements Vehicle{
 
 public void run(){
  System.out.println("I am driving Bus");
   }
   
   }
   
   class App{
    public static void main(String[] arg){
      Vehicle v1 = new Bus();
      v1.run();
      }
      
      


