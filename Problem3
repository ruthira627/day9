interface Device {
    void turnOn();
}

class Fan implements Device {
    public void turnOn() {
        System.out.println("Fan Turned ON");
    }
}

class Light implements Device {
    public void turnOn() {
        System.out.println("Light Turned ON");
    }
}

class AirConditioner implements Device {
    public void turnOn() {
        System.out.println("Air Conditioner Turned ON");
    }
}

public class Main {
    public static void main(String[] args) {
        Device d;

        d = new Fan();
        d.turnOn();

        d = new Light();
        d.turnOn();

        d = new AirConditioner();
        d.turnOn();
    }
}
