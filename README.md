

Student details

public class StudentDetails {
    private String name;
    private String yearOfBirth;
    private String studentNumber;
    private String course;
    private String favouriteUnit;
    private String vision;

    public StudentDetails(String name, String yearOfBirth, String studentNumber, String course, String favouriteUnit, String vision) {
        this.name = name;
        this.yearOfBirth = yearOfBirth;
        this.studentNumber = studentNumber;
        this.course = course;
        this.favouriteUnit = favouriteUnit;
        this.vision = vision;
    }

    public void displayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Year of Birth: " + yearOfBirth);
        System.out.println("Student Number: " + studentNumber);
        System.out.println("Course: " + course);
        System.out.println("Favourite Unit: " + favouriteUnit);
        System.out.println("Vision: " + vision);
    }

    public static void main(String[] args) {
        StudentDetails student = new StudentDetails("Juma", "5th June 1997", "21/04630", "Information Technology", "Java Programming", "Programmer");
        student.displayDetails();
    }
}
