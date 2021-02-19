# televisaoappJAVA

package com.mycompany.televison;


public class Televisao {
    
    //atributos
    String marca;
    Boolean ligada;
    int volume;
    int canal;
    
    //metodos
    void ligar(){
        ligada = true;
        System.out.println("A TV " + marca + " esta ligada");
        ligada = false;
        
    }
    
    void aumentarVolume(){
        if(ligada){
            volume++;
            System.out.println("A TV "+ marca + " Esta com volume"+volume);
        }else{
            System.out.println("Ligue a TV" + marca);
        }
     
      
    }
    void avancarCanal(){
       if(ligada){
           canal++;
           System.out.println("A TV " +  marca + " esta no Canal" + canal);
       }else{
           System.out.println("Ligue a TV " +  marca);
       } 
    }  
}
