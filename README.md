Campus Course & Records Manager (CCRM)
Project Overview
CCRM is a Java console application designed for university-level management of students, courses, enrollments, grading, and file operations. It provides an interactive CLI (Command Line Interface) to add, list, update, and deactivate students and courses; enroll students; record grades; view transcripts; and perform file import/export and backup tasks.

## Folder Structure

CCRM/
├── src/
│ └── edu/ccrm/
│ ├── cli/
│ ├── config/
│ ├── domain/
│ ├── service/
│ ├── io/
│ └── util/
├── students.csv
├── courses.csv
├── README.md
├── USAGE.md
├── requirements.md

How to Run
Java Version: Requires JDK 17 or higher.

Compile:
javac -d bin src/edu/ccrm/**/*.java

Run:
java -cp bin edu.ccrm.cli.Main
(Assuming the main CLI class is Main in edu.ccrm.cli package)

Evolution of Java (Short Summary)
1995: Java 1.0 released – "Write Once, Run Anywhere" (WORA) principle.

1998: Java 2 (J2SE) introduced with improved libraries and performance.

2004: Java 5 introduced generics, enhanced for-each loop, annotations.

2014: Java 8 added lambdas and Streams API for functional programming.

2017: Java 9 modularity system (Project Jigsaw).

2021: Java 17 became a long-term support (LTS) version.

2024: Recent versions focus on sealed classes, pattern matching, and performance.

Java ME vs SE vs EE Comparison

<img width="588" height="301" alt="image" src="https://github.com/user-attachments/assets/daa5b459-9c3a-4c9b-82dd-894bade3c1f4" />

JDK / JRE / JVM Explanation
JVM (Java Virtual Machine): Executes Java bytecode on any hardware platform; provides platform independence.

JRE (Java Runtime Environment): Includes JVM and standard libraries needed to run Java applications.

JDK (Java Development Kit): Includes JRE plus development tools such as compiler (javac), debugger, etc.

Windows Installation Steps
Download JDK 17 or higher from Oracle or OpenJDK website.

Run the installer and follow the prompts.

Set environment variables:

Add JAVA_HOME pointing to JDK folder.

Add %JAVA_HOME%\bin to PATH.

Verify installation in Command Prompt with java -version and javac -version.

(Insert your annotated screenshots showing each step here.)

Eclipse Setup Steps
Download Eclipse IDE for Java Developers from the Eclipse website.

Install and launch Eclipse.

Create a new Java project (File > New > Java Project).

Import CCRM source files into src folder.

Configure JDK 17 in project settings (Project Properties > Java Build Path > Libraries).

Build and run the main class.

(Insert your annotated screenshots showing each step here.)

Mapping table: Syllabus Topics → File/Class/Method Demonstrations:
<img width="614" height="369" alt="image" src="https://github.com/user-attachments/assets/bb091e69-284c-40ed-a4fa-b1f90c63e81d" />

Enabling Assertions and Sample Commands
Enable assertions while running the Java application to perform runtime checks:

text
java -ea -cp bin edu.ccrm.cli.Main
Explanation:

-ea or -enableassertions enables assertion checking.

Assertions help catch programming errors by verifying assumptions in code during development/testing.

Author and Contact
Author: Anurag Thakur

Contact Email: atanuragthakurpro@gmail.com

