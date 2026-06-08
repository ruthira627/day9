interface Account {
    void calculateInterest();
}

class SavingsAccount implements Account {
    public void calculateInterest() {
        System.out.println("Savings Interest = 4%");
    }
}

class FixedDeposit implements Account {
    public void calculateInterest() {
        System.out.println("FD Interest = 7%");
    }
}

class RecurringDeposit implements Account {
    public void calculateInterest() {
        System.out.println("RD Interest = 6%");
    }
}

public class Main {
    public static void main(String[] args) {
        Account a;

        a = new SavingsAccount();
        a.calculateInterest();

        a = new FixedDeposit();
        a.calculateInterest();

        a = new RecurringDeposit();
        a.calculateInterest();
    }
}
