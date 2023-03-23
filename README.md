# animalDio


 public class Main {

    public static void main(String[] args)  throws IOException {
        Scanner sc = new Scanner(System.in);

        String AN1,AN2,AN3;

        AN1 = sc.nextLine();
        AN2 = sc.nextLine();
        AN3 = sc.nextLine();

        if ((AN1.equals("vertebrado")) && (AN2.equals("ave"))  && (AN3.equals("carnivoro"))) {
            System.out.println("aguia\n");
        }

        if ((AN1.equals("vertebrado")) && (AN2.equals("ave"))  && (AN3.equals("onivoro"))) {
            System.out.println("pomba\n");
        }

        if ((AN1.equals("vertebrado")) && (AN2.equals("mamifero"))  && (AN3.equals("onivoro"))) {
            System.out.println("homem\n");
        }

        if ((AN1.equals("vertebrado")) && (AN2.equals("mamifero"))  && (AN3.equals("herbivoro"))) {
            System.out.println("vaca\n");
        }

        if ((AN1.equals("invertebrado")) && (AN2.equals("inseto"))  && (AN3.equals("hematofago"))) {
            System.out.println("pulga\n");
        }

        if ((AN1.equals("invertebrado")) && (AN2.equals("inseto"))  && (AN3.equals("herbivoro"))) {
            System.out.println("lagarta\n");
        }

        if ((AN1.equals("invertebrado")) && (AN2.equals("anelideo")) && (AN3.equals("hematofago"))) {
            System.out.println("sanguessuga\n");
        }

        if ((AN1.equals("invertebrado")) && (AN2.equals("anelideo")) && (AN3.equals("onivoro"))) {
            System.out.println("minhoca\n");
        }
    }
} 
