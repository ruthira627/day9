interface Payment {
    void pay(double amount);
}

class UPI implements Payment {
    public void pay(double amount) {
        System.out.println("UPI Payment: Rs." + amount);
    }
}

class CreditCard implements Payment {
    public void pay(double amount) {
        System.out.println("Credit Card Payment: Rs." + amount);
    }
}

class Wallet implements Payment {
    public void pay(double amount) {
        System.out.println("Wallet Payment: Rs." + amount);
    }
}

public class Main {
    public static void main(String[] args) {
        Payment p;

        p = new UPI();
        p.pay(500);

        p = new CreditCard();
        p.pay(1000);

        p = new Wallet();
        p.pay(300);
    }
}
