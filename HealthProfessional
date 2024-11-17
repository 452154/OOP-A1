public class HealthProfessional{
    // Instance variable
    private String id;
    private String name;
    // Default constructor
    public HealthProfessional() {}

    // Initialize the constructor of all instance variables
    public HealthProfessional(String id, String name) {
        this.id = id;
        this.name = name;
    }

    // A method to print all instance variables
    public void printInformation() {
        System.out.println("ID: " + this.id);
        System.out.println("Name: " + this.name);
    }
}

class GeneralPractitioner extends HealthProfessional {
    // Instance variables unique to general practitioners
    private String specialty;
    private int yearsOfExperience;

    // Default constructor
    public GeneralPractitioner() {}

    // A constructor with arguments that initializes all instance variables
    public GeneralPractitioner(String id, String name,String specialty, int yearsOfExperience) {
        super(id, name); // Call the argument constructor of the base class and set the specialty to "General Practitioner
        this.specialty = specialty;
        this.yearsOfExperience = yearsOfExperience;
    }

    // A method to print all instance variables
    @Override
    public void printInformation() {
        super.printInformation(); // Calling a method of the base class prints basic information
        System.out.println("Specialty: "+specialty);
        System.out.println("Years of Experience: " + yearsOfExperience);
        System.out.println("Description: Provide a range of services for patients.");
    }
}

class NursePractitioner extends HealthProfessional{
    private String specialty;
    private int yearsOfExperience;

    //Default constructor
    public NursePractitioner(){}

    // A constructor with arguments that initializes all instance variables
    public NursePractitioner(String id, String Name,String specialty, int yearsOfExperience){
        super(id, Name);
        this.specialty = specialty;
        this.yearsOfExperience = yearsOfExperience;
    }

    @Override
    public void printInformation() {
        super.printInformation();
        System.out.println("Specialty: "+specialty);
        System.out.println("Years of Experience: " + yearsOfExperience);
        System.out.println("Description: Nurse Practitioner can consult, treat, diagnose, and manage medical conditions.");
    }
}

class Appointment {
    //Create four instance variables
    public String patientName;
    public String patientPhone;
    private String Time;
    private HealthProfessional selectedHealthProfessional;

    // Default constructor
    public Appointment() {}

    // Initializes constructors for all instance variables
    public Appointment(String patientName, String patientPhone, String Time, HealthProfessional selectedHealthProfessional) {
        this.patientName = patientName;
        this.patientPhone = patientPhone;
        this.Time = Time;
        this.selectedHealthProfessional = selectedHealthProfessional;
    }

    // A method to print all instance variables
    public void printAppointmentInformation() {
        System.out.println("Patient Name: " + patientName);
        System.out.println("Patient Phone: " + patientPhone);
        System.out.println("Preferred Time Slot: " + Time);
        System.out.println("Select Doctor:" + selectedHealthProfessional);
        selectedHealthProfessional.printInformation();
    }
}













