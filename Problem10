interface Exam {
    void evaluate();
}

class MCQExam implements Exam {
    public void evaluate() {
        System.out.println("MCQ Exam Evaluated");
    }
}

class CodingExam implements Exam {
    public void evaluate() {
        System.out.println("Coding Exam Evaluated");
    }
}

class VivaExam implements Exam {
    public void evaluate() {
        System.out.println("Viva Exam Evaluated");
    }
}

public class Main {
    public static void main(String[] args) {
        Exam e;

        e = new MCQExam();
        e.evaluate();

        e = new CodingExam();
        e.evaluate();

        e = new VivaExam();
        e.evaluate();
    }
}
