interface Ticket {
    void bookTicket();
}

class BusTicket implements Ticket {
    public void bookTicket() {
        System.out.println("Bus Ticket Booked");
    }
}

class TrainTicket implements Ticket {
    public void bookTicket() {
        System.out.println("Train Ticket Booked");
    }
}

class FlightTicket implements Ticket {
    public void bookTicket() {
        System.out.println("Flight Ticket Booked");
    }
}

public class Main {
    public static void main(String[] args) {
        Ticket t;

        t = new BusTicket();
        t.bookTicket();

        t = new TrainTicket();
        t.bookTicket();

        t = new FlightTicket();
        t.bookTicket();
    }
}
