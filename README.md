public class Main {
    public static void main(String[] args) {
        
        int edad = 15;

        if (edad >= 18) {
            System.out.println("Puedes ver películas clasificación C (Adultos).");
        } else if (edad >= 15) {
            System.out.println("Puedes ver películas clasificación B15 (Adolescentes y adultos).");
        } else if (edad >= 12) {
            System.out.println("Puedes ver películas clasificación B (Para mayores de 12 años).");
        } else {
            System.out.println("Solo puedes ver películas clasificación A (Todo público).");
        }

        System.out.println("Fin de la consulta.");
    }
}