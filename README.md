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
   
This is for QA part 


class Mobile{

 public void getInfo(){
 System.out.println("Mobile information is provided");
 
 }
 
 class MobileApp{
 
 public static void main(String[] arg){
 
   Mobile  m1 = new Mobile();
   m1.getInfo();
   
   }
   }
   
   class App{
    public static void main(String[] arg){
      Vehicle v1 = new Bus();
      v1.run();
      }
      
      class Threading extends Thread{
      
      public void run(){
      System.out.println("Thread running");
      }
      
      }
      
      class MainThread{
      
      public static void main(String[] arg){
      Threading t1 = new Threading();
      Thread  t = new Thread(t1);
      t.start();
      }
}
      



