## Java Notes

- Java code is first compiled into Java bytecode which is in a machine independent format. JVM then executes the bytecode, interpreting it as binary instructions for the target platform.

- What is JVM?
  - JVM is a software program that provides a platform-independent environment for executing Java code. When you compile a Java program, the compiler generates Java bytecode, which is a compact binary representation of the program's source code. The JVM then reads the bytecode and converts it into machine code, which can be executed directly by the computer's processor.
  - The JVM acts as a "runtime interpreter" that dynamically executes the bytecode instructions, managing memory and other resources as necessary. Because the JVM is available on many different platforms (such as Windows, MacOS, and Linux), Java code can run on any of these platforms without modification, provided that a JVM is installed.
  - In this way, the JVM allows Java code to be portable and run on any device that has a JVM, regardless of the underlying hardware and operating system. This is one of the key benefits of the Java platform, as it allows Java developers to write code once and run it anywhere.

- Difference between JVM and JRE
  - *JRE* (Java Runtime Environment) is a package that contains all the necessary components to run a Java program. It includes the following components:
    - Java Virtual Machine (JVM): This is the component responsible for executing the compiled Java code. It interprets the bytecode into machine-readable form and performs tasks such as memory management and security checks.
    - Java Class Libraries: These are a set of pre-written classes that provide a wide range of functionality, such as input/output operations, data structures, and other utility functions.
    - Java Application Launcher: This component is responsible for launching Java applications. It takes care of finding the main class of the application, creating a new instance of the JVM, and executing the main method.
    - The JRE is what you need to run a Java program on your computer. You can think of it as a runtime environment that provides the necessary components to run a Java program.

  - *JVM* (Java Virtual Machine), on the other hand, is a virtual machine that runs the compiled Java code. It provides a runtime environment for the execution of Java code. The JVM acts as an interpreter between the compiled Java code and the underlying hardware and operating system. It is responsible for the following tasks:
    - Memory Management: The JVM allocates memory to objects and manages the memory space to ensure that the program runs smoothly and efficiently.
    - Type Checking: The JVM performs type checking to ensure that the program is type-safe and free of type errors.
    - Security: The JVM performs security checks to ensure that the code being executed is secure and does not pose a threat to the underlying system.
    - In summary, JRE is a package that contains the necessary components to run a Java program, including the JVM. JVM is the component responsible for executing the compiled Java code and providing a runtime environment for the program to run.

- What is JDK?
  - JRE (Java Runtime Environment) is not a complete development environment. It only provides the necessary components to run a Java program, including the  Java Virtual Machine (JVM), Java Class Libraries, and the Java Application Launcher.
  - While the JRE is necessary to run Java programs, it does not provide the tools and resources necessary for developing Java programs. For development purposes, you need the JDK (Java Development Kit), which includes the JRE along with additional components such as the Java Compiler, Java Debugger, Java Documentation, and Java Tools.
  - So, to summarize, JRE is a component of the Java ecosystem that provides the necessary components to run Java programs, while JDK is a complete development environment that provides everything you need to develop, compile, and run Java programs.