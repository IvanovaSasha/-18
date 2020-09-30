# -18
практическая 18
public class Pr1818 { 
public static void main(String[] args) { 
Scanner a = new Scanner(System.in); 
 
System.out.print("Ввекдите массу вашего тела: "); 
double ves = a.nextDouble(); 
System.out.print("Ведите ваш рост в сантиметрах: "); 
double rost = a.nextDouble(); 
 
double Optves = rost - 100; 
 
if (Optves < ves) { 
double x = Optves - ves; 
System.out.println("Вам нужно похудеть на: " + x); 
} else if (Optves > ves) { 
double y = (ves - Optves) * (-1); 
System.out.println("Вам нужно похудеть на: " + y); 
} else { 
System.out.println("Ваш вес оптимальный"); 
} 
} 
} 
