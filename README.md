# Practica_Estructura_De_Datos

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

package Triiborec
import java.io.*; 

class GFG { 
class Triborec { 

    static int prt_tribonacci(int n) 
    static int prt_Trib_R(int n) 
    { 

        if (n == 0 || n == 1 || n == 2) 
@@ -11,9 +12,9 @@ class GFG {
        if (n == 3) 
            return 1; 
        else
            return prt_tribonacci(n - 1) +  
                   prt_tribonacci(n - 2) + 
                   prt_tribonacci(n - 3); 
            return prt_Trib_R(n - 1) +  
                   prt_Trib_R(n - 2) + 
                   prt_Trib_R(n - 3); 
    } 

    static void printTrib(int n) 
@@ -25,8 +26,8 @@ class GFG {

    public static void main(String args[]) 
    { 
        int n = 10; 
        int n = 21; 

        printTrib(n); 
        printTribo(n); 
    } 
} 
