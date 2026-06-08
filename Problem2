interface User {
    void login();
    void logout();
}

class Student implements User {
    public void login() {
        System.out.println("Student Logged In");
    }

    public void logout() {
        System.out.println("Student Logged Out");
    }
}

class Faculty implements User {
    public void login() {
        System.out.println("Faculty Logged In");
    }

    public void logout() {
        System.out.println("Faculty Logged Out");
    }
}

class Admin implements User {
    public void login() {
        System.out.println("Admin Logged In");
    }

    public void logout() {
        System.out.println("Admin Logged Out");
    }
}

public class Main {
    public static void main(String[] args) {
        User u = new Student();
        u.login();
        u.logout();

        u = new Faculty();
        u.login();
        u.logout();

        u = new Admin();
        u.login();
        u.logout();
    }
}
