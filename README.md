# java-pro1
hj
package javaproject;

public class arraysinmethods {
    public static void main(String args[]){
    	int array[]={1,2,3,4,5,6};
    	change(array);
    	
    	for(int y: array){
    		System.out.println(y);
    	}
    }
        public void static change (int x[]){
        	for(int cont=0; cont<x.length; cont++){
        		x[cont]+=6;
        	}
        }
}
