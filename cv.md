# Belyaev Maxim 
![Belyaev Maxim](https://github.com/Roflianochka/curriculumVitae/assets/107355541/4758ee44-841b-439f-866b-40b8a78fd6b9)
## Contact information:
* Phone: +375445417858
* [*Telegram*](https://t.me/roooflianochka)
* Email: maximbealev831@gmail.com
## About me
Goal and Priorities: My goal is to excel as a Java and C# programmer and contribute to the development of innovative software solutions. I prioritize delivering high-quality code, collaborating effectively with team members, and continuously expanding my knowledge and skills in programming.
Strengths: I have a strong foundation in Java and C# programming languages. I possess excellent problem-solving abilities, attention to detail, and a passion for writing clean and efficient code.
Work Experience: Although I do not have professional work experience yet, I have actively engaged in personal projects and training to gain practical experience and enhance my programming skills.
## Skills
- **Programming Languages:** Java, C#
- **Frameworks:** Spring Boot, .NET Framework
- **Methodologies: Object-Oriented Programming (OOP), Agile Software Development
- **Version Control Systems:** Git
- **Development Tools:** IntelliJ IDEA, Visual Studio, Unity Editor
- **Game Development:** Unity
- **3D Modeling:** Blender
## Code Examples
```c#
//An example of using C# in a Unity project
using UnityEngine;

public class PlayerController : MonoBehaviour
{
    private float speed = 5f;
    
    void Update()
    {
        float horizontalInput = Input.GetAxis("Horizontal");
        float verticalInput = Input.GetAxis("Vertical");
        
        Vector3 movement = new Vector3(horizontalInput, 0, verticalInput) * speed * Time.deltaTime;
        transform.Translate(movement);
    }
}
```
```java
//Example that demonstrates a basic implementation of a "Student" class with properties and methods
public class Student {
    private String name;
    private int age;
    private String major;

    public Student(String name, int age, String major) {
        this.name = name;
        this.age = age;
        this.major = major;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public String getMajor() {
        return major;
    }

    public void setMajor(String major) {
        this.major = major;
    }

    public void displayInfo() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Major: " + major);
    }

    public static void main(String[] args) {

        Student student1 = new Student("John Doe", 20, "Computer Science");

        student1.displayInfo();
    }
}
```
## Work Experience
None
## Courses and Training
- Introduction to Java - Epam
- .NET Development - Epam
- BSUIR Java materials 
## English Level
- B2
