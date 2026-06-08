interface Notification {
    void sendNotification();
}

class EmailNotification implements Notification {
    public void sendNotification() {
        System.out.println("Email Notification Sent");
    }
}

class SMSNotification implements Notification {
    public void sendNotification() {
        System.out.println("SMS Notification Sent");
    }
}

class PushNotification implements Notification {
    public void sendNotification() {
        System.out.println("Push Notification Sent");
    }
}

public class Main {
    public static void main(String[] args) {
        Notification n;

        n = new EmailNotification();
        n.sendNotification();

        n = new SMSNotification();
        n.sendNotification();

        n = new PushNotification();
        n.sendNotification();
    }
}
