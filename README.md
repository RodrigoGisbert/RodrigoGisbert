package main;
public abstract class  Instrumentos {
     public abstract void sonido();
}

 class Guitarra extends  Instrumentos{
     @Override
     public void sonido() {
         System.out.println("Guitarra");
     }
 }

 class Saxofón extends  Instrumentos{
     @Override
     public void sonido() {
         System.out.println("Saxofon");
     }
 }

 class Piano extends  Instrumentos{
     @Override
     public void sonido() {
         System.out.println("Piano");
     }
 }
