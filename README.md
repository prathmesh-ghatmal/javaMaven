
# Java Maven WebApp - Hello World Project

This is a **simple Java Maven Web Application** using Servlets and JSP.  
It can run locally on **Windows** or **Linux** using Maven and Jetty.

---

## **Prerequisites**

The following software must be installed:

1. **Java (JDK 17 or higher)**
2. **Apache Maven**

### **Check if Installed**

#### **Java**
```bash
java -version
````

* If Java is installed, it will show the version.
* If not installed, follow the steps below.

#### **Maven**

```bash
mvn -version
```

* If Maven is installed, it will show the version.
* If not installed, follow the steps below.

---

## **Installation**

### **Windows**

1. **Install Java JDK 17+**

   * Download from [Adoptium](https://adoptium.net/) or [Oracle](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
   * Install and set environment variable:

     ```
     JAVA_HOME = C:\Path\to\jdk
     ```
   * Add `%JAVA_HOME%\bin` to system `PATH`

2. **Install Maven**

   * Download from [Apache Maven](https://maven.apache.org/download.cgi)
   * Extract and set environment variable:

     ```
     MAVEN_HOME = C:\Path\to\apache-maven
     ```
   * Add `%MAVEN_HOME%\bin` to system `PATH`

---

### **Linux (Ubuntu/Debian)**

1. **Update system**

```bash
sudo apt update && sudo apt upgrade -y
```

2. **Install Java JDK 17+**

```bash
sudo apt install openjdk-17-jdk -y
```

3. **Install Maven**

```bash
sudo apt install maven -y
```

4. **Verify installation**

```bash
java -version
mvn -version
```

---

## **Clone the Project**

```bash
git clone https://github.com/prathmesh-ghatmal/javaMaven.git
cd javaMaven
```

---

## **Run on Windows**

1. Open terminal in project folder:

```bash
mvn jetty:run
```

2. Open browser and go to:

```
http://localhost:8080/hello
```

---

## **Migrate to Linux using FileZilla**

1. Connect to Linux server using **FileZilla (SFTP)**
2. Upload the entire project folder `javaMaven` to:

```
/home/imcc/javaMaven
```

---

## **Run on Linux**

1. Open terminal and navigate to project folder:

```bash
cd /home/imcc/javaMaven
```

2. Run the application:

```bash
mvn jetty:run
```

3. Open browser on the Linux machine and go to:

```
http://localhost:8080/hello
```

---

Now your **Hello World Maven WebApp** should run successfully on both Windows and Linux locally!

```


