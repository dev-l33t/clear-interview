
## Personal Interview Questions

### Q1: Tell me about yourself.
- Good morning! My name is Pratik Diliprao Joshi. I have completed my Bachelor of Technology in Computer Science and Engineering from Dr. Babasaheb Ambedkar Technological University Lonere, in 2022 with a CGPA of 7.86

- After that, I completed a software testing course where I gained strong knowledge in both manual and automation testing, along with hands-on practice using Selenium and Core Java. I also have a solid foundation in HTML and CSS. 

- I’m now looking for an opportunity where I can contribute my skills to the organization and its teams, while continuing to grow in the field of software testing.

- That's it about me. Thank you!

---

### Q2: Can you explain the gap in your academic and career journey?

A: Yes, I had a 2-year academic gap and a career gap after graduation. Here's a brief explanation of both:

| **Academic Year** | **Explanation** |
|-------------------|------------|
| 1st Year (Aug 2016 – Jun 2017) | I relocated for my studies, and adjusting to the new environment took time. I couldn’t focus properly and ended up with a backlog . |
| 2nd Year (Aug 2017 – Jun 2018) | I was under pressure managing both the backlog and new subjects. This led to a year down in 2018. |
| Gap (Aug 2018 – Jun 2020) |  I completed the Certified IT Architect (CITA) course from CMS IT Services (Jun – Dec 2019), building foundational IT skills. |
| COVID Phase (2020 – 2021) |  I used this time to clear my backlogs through online exams. Our college also migrated to a new university (XYZ University), and I completed my remaining years, graduating in 2022. |

💼 Career Gap (Post-Graduation):
After graduation, I enrolled in a Software Testing Course (July – Dec 2022) where I learned Manual & Automation Testing using Selenium, Core Java, and enhanced my HTML/CSS skills.

---

### Q3: You’ve spent over two years focusing on self-improvement after graduation. Can you explain how you used that time and what you achieved?
**A:**  
  Yes, I understand that it might seem like a long time. 
  After graduating in **2022**, I joined a **software testing course** from **July to December 2022**, where I learned **manual and automation testing** using **Selenium and   Core Java**. After that, I used this time effectively:

  - Focused on **interview preparation** and **communication skills**.
  - Built a solid **portfolio** with **real-time testing projects**.
  - Practiced [**test case writing**](https://pratiks-desk.site/test-cases/practiced-testcases/#sanity-testing), **bug reporting**, and **scenario-based testing** regularly.
  - Kept learning through **online tutorials, mock interviews**, and peer feedback.

  I didn’t want to rush into a job. I aimed to be **fully job-ready** — both technically and personally.  
  Now, I feel confident and excited to begin my career in software testing.

---


# 📝 Testing Documents & Related Terms

---

## 1. **Test Plan**

* A **formal document** describing the **scope, objectives, strategy, resources, schedule, and deliverables** of testing.
* It answers **what to test, how to test, who will test, and when testing will be done**.

---

## 2. **Test Scenario**

* A **high-level description of what to test** → usually derived from requirements.
* Example: “Verify login functionality with valid and invalid credentials.”

---

## 3. **Test Case**

* A set of **step-by-step instructions with input, execution steps, and expected result** to validate a feature.
* Example: Steps to enter username & password → Expected: User should log in successfully.

---

## 4. **Test Script**

* A set of **automated test instructions** written using tools (e.g., Selenium + Java).
* It performs **execution of test cases automatically**.

---

## 5. **Test Data**

* The **input values (valid, invalid, boundary, large data sets)** used to test application behavior.
* Example: Test login using valid email, invalid email, empty field, etc.

---

## 6. **Test Execution**

* The process of **running test cases or test scripts** and recording the results.
* Can be **manual (step execution)** or **automation (tool execution)**.

---

## 7. **Test Report**

* A **summary document of test execution results** showing total test cases, passed, failed, blocked, skipped.
* Helps stakeholders **understand project quality and risks**.

---

## 8. **Defect / Bug**

* A **mismatch between expected result and actual result** found during testing.
* Example: Clicking login with valid credentials → Actual: Error shown.

---

## 9. **Defect Life Cycle**

* The **journey of a defect from identification to closure**.
* States: New → Assigned → Open → Fixed → Retested → Verified → Closed (or Reopened if not fixed).

---

## 10. **RTM (Requirement Traceability Matrix)**

* A document that **maps requirements to test cases** to ensure full coverage.
* Helps confirm that **every requirement has been tested**.

---

## 11. **Smoke Testing**

* A quick test to check whether the **basic functionalities of the build are working**.
* Example: Check login, signup, and homepage load before deeper testing.

---

## 12. **Sanity Testing**

* Narrow and deep testing to check whether **a specific bug fix or module is working properly**.
* Example: After fixing login issue → only test login page in detail.

---

## 13. **Regression Testing**

* Testing to ensure that **new changes do not break existing features**.
* Example: After adding payment option → recheck login, cart, checkout.

---

## 14. **Re-testing**

* Running the **same test again** after fixing a defect.
* Example: Login was failing → after fix → retest login.

---

## 15. **Test Strategy**

* A **high-level document** prepared by the QA Manager that defines **approach, tools, and testing levels**.
* Test Plan = project-specific; Test Strategy = organization-level.

---

## 16. **Test Environment**

* The **hardware, software, database, network setup** required for testing.
* Example: Windows 10, Chrome browser, MySQL DB, Test server.

---

## 17. **Entry & Exit Criteria**

* **Entry Criteria** → Conditions that must be met before testing begins (e.g., test environment ready).
* **Exit Criteria** → Conditions that define when testing is completed (e.g., 95% test cases passed).

---

## 18. **Bug Severity & Priority**

* **Severity** → Impact of defect on system (Critical, Major, Minor).
* **Priority** → Order in which bug should be fixed (High, Medium, Low).
* Example: Spelling mistake (Low severity, Low priority) vs. Login crash (High severity, High priority).

---

## 19. **Levels of Testing**

* **Unit Testing** → Individual module testing.
* **Integration Testing** → Module interaction testing.
* **System Testing** → Entire application testing.
* **UAT (User Acceptance Testing)** → Testing by end users/business.

---

## 20. **Types of Testing (Common in Interviews)**

* **Functional Testing** → Check business functionalities.
* **Non-Functional Testing** → Performance, security, usability.
* **Black Box Testing** → Tester doesn’t see code, only inputs/outputs.
* **White Box Testing** → Tester checks code structure, logic, loops.
* **Grey Box Testing** → Partial code knowledge.

---

**simple, short & complete Java notes** that cover all important points for revision.

---

# 📘 Java Quick Notes (Beginner → Intermediate)

## 1. Basics

* **Java = OOP language** (Object-Oriented Programming).
* **Platform Independent** → Write once, run anywhere (JVM).
* **Case-sensitive**.
* `.java` → source code, `.class` → bytecode.

## 2. Data Types

* **Primitive (8 types)**

  * byte (1 byte), short (2), int (4), long (8), float (4), double (8), char (2), boolean (1).
* **Non-primitive** → String, Arrays, Classes, Objects.

## 3. Variables

* Types → local, instance, static.
* Final → constant, value can’t change.
* Static → belongs to class, not object.

## 4. Operators

* Arithmetic: `+ - * / %`
* Relational: `== != < > <= >=`
* Logical: `&& || !`
* Assignment: `= += -= *= /=`
* Unary: `++ --`
* Ternary: `(condition) ? true : false`

## 5. Control Statements

* **if-else, switch-case**
* **Loops**: for, while, do-while
* **break** → exit loop, **continue** → skip current iteration

## 6. OOPs Concepts

* **Class**: Blueprint of object.
* **Object**: Instance of class.
* **Encapsulation**: Bind data + methods. (use private + getters/setters).
* **Inheritance**: Reuse parent class properties (`extends`).
* **Polymorphism**:

  * Compile time (method overloading).
  * Runtime (method overriding).
* **Abstraction**: Hiding details, showing only essentials. (abstract class, interface).

## 7. Keywords

* `this` → current object.
* `super` → parent class.
* `final` → variable (constant), method (can’t override), class (can’t extend).
* `static` → class level.
* `abstract` → incomplete method/class.
* `synchronized` → thread-safe.
* `transient` → not serialized.
* `volatile` → variable updated by multiple threads.

## 8. Strings

* Immutable (can’t change).
* Created by `" "` or `new`.
* Important methods: `length()`, `charAt()`, `substring()`, `equals()`, `compareTo()`, `toLowerCase()`, `toUpperCase()`.

## 9. Arrays

* Collection of same type, fixed size.
* `int arr[] = new int[5];`
* `for-each` loop to iterate.

## 10. Exception Handling

* Try-catch-finally.
* `throw` → used to throw exception.
* `throws` → declare exception.
* Checked (compile-time) & Unchecked (runtime).
* Common: `NullPointerException`, `ArrayIndexOutOfBoundsException`.

## 11. Collections

* **List** → ordered, duplicates allowed (`ArrayList`, `LinkedList`).
* **Set** → no duplicates (`HashSet`, `TreeSet`).
* **Map** → key-value pairs (`HashMap`, `TreeMap`).
* **Queue** → FIFO (`PriorityQueue`, `LinkedList`).

## 12. Multithreading

* Thread → lightweight process.
* Create thread:

  * extend `Thread` class OR
  * implement `Runnable` interface.
* Start → `start()` (not `run()` directly).
* Synchronization → avoid conflicts in multi-threading.

## 13. File Handling (java.io)

* Classes → `File`, `FileReader`, `FileWriter`, `BufferedReader`, `BufferedWriter`.
* Use try-with-resources to auto close streams.

## 14. Java 8 Features

* **Lambda expressions**: `(a, b) -> a + b`
* **Functional Interfaces** (`@FunctionalInterface`).
* **Streams API** → operations on collections.
* **Default methods** in interfaces.

## 15. Memory

* **Heap** → objects.
* **Stack** → method calls + local vars.
* **Garbage Collector (GC)** → cleans unused objects.

---

Perfect 👍 Now you want a **detailed version with full explanations of all Java concepts**.
This will be like **complete notes** (clear, structured, and easy to study).
Here’s the expanded version 👇

---

# 📘 Complete Java Notes (Detailed + Beginner Friendly)

---

## 1. Introduction to Java

* Java is a **high-level, object-oriented, secure, and platform-independent language** developed by Sun Microsystems (1995).
* It compiles code into **bytecode** which runs on the **JVM (Java Virtual Machine)**.
* Known for *portability* → *“Write Once, Run Anywhere”*.

---

## 2. Java Architecture (JDK, JRE, JVM)

* **JVM (Java Virtual Machine)** → executes bytecode, makes Java platform-independent.
* **JRE (Java Runtime Environment)** → JVM + libraries to run programs.
* **JDK (Java Development Kit)** → JRE + tools like compiler, debugger (for development).

---

## 3. Data Types in Java

* **Primitive (8 types):**

  * byte (1 byte), short (2), int (4), long (8) → integers.
  * float (4), double (8) → decimals.
  * char (2) → single character.
  * boolean (1 bit) → true/false.
* **Non-Primitive:** Strings, Arrays, Classes, Interfaces, Objects.

---

## 4. Variables

* **Local Variables** → declared inside methods, exist during method execution.
* **Instance Variables** → object-specific, stored in heap memory.
* **Static Variables** → shared across all objects, memory-efficient.
* **Final Variables** → constants, cannot change after initialization.

---

## 5. Operators

* **Arithmetic** → `+ - * / %`
* **Relational** → `== != > < <= >=`
* **Logical** → `&& || !`
* **Assignment** → `= += -= *= /=`
* **Unary** → `++ --` (increment/decrement)
* **Ternary** → `(condition) ? trueValue : falseValue`

---

## 6. Control Statements

* **if-else** → decision making.
* **switch-case** → multiple options based on a value.
* **Loops:**

  * for → known iterations.
  * while → condition-based loop.
  * do-while → runs at least once.
* **break** → exits loop, **continue** → skips current iteration.

---

## 7. OOPs Concepts in Java

Java follows **4 main pillars of OOP**:

1. **Encapsulation**

   * Binding data and methods into a single unit (class).
   * Achieved using **private variables + public getters/setters**.

2. **Inheritance**

   * Acquiring properties of one class into another (`extends`).
   * Promotes **code reusability**.
   * Types: single, multilevel, hierarchical (Java doesn’t support multiple inheritance directly).

3. **Polymorphism**

   * **Compile-time (Overloading):** Same method name, different parameters.
   * **Runtime (Overriding):** Subclass provides specific implementation of parent class method.

4. **Abstraction**

   * Hiding internal details, showing only essential features.
   * Achieved using **abstract classes** (incomplete methods) and **interfaces**.

---

## 8. Important Keywords

* **this** → refers to current object.
* **super** → calls parent class constructor/method.
* **final** → makes constants, prevents inheritance or overriding.
* **static** → class-level keyword (variables, methods).
* **abstract** → defines incomplete methods/classes.
* **synchronized** → ensures thread safety.
* **volatile** → variable value updated by multiple threads.
* **transient** → skips variable during serialization.

---

## 9. Strings

* **Immutable:** Once created, values cannot change.
* Declared as `"Hello"` or `new String("Hello")`.
* **Important Methods:**

  * `length()`, `charAt(i)`, `substring()`, `equals()`, `compareTo()`, `concat()`, `toLowerCase()`, `toUpperCase()`.
* For **mutable strings**, Java provides **StringBuilder & StringBuffer**.

---

## 10. Arrays

* **Definition:** Fixed-size collection of same type elements stored in sequence.
* Example: `int arr[] = new int[5];`
* Types:

  * Single Dimensional (`int arr[]`).
  * Multi-Dimensional (`int arr[][]`).
* Traversed using normal `for` or `for-each` loop.

---

## 11. Exception Handling

* **Definition:** Mechanism to handle runtime errors gracefully.
* **Keywords:**

  * `try` → code to test.
  * `catch` → handle exception.
  * `finally` → always executes (cleanup).
  * `throw` → manually throw exception.
  * `throws` → declare exceptions in method signature.
* **Types:**

  * Checked (compile-time) → e.g., IOException.
  * Unchecked (runtime) → e.g., NullPointerException.

---

## 12. Collections Framework

* Provides **ready-made data structures** for storing/managing data.
* **List** (ordered, allows duplicates): `ArrayList`, `LinkedList`.
* **Set** (unique elements, no duplicates): `HashSet`, `TreeSet`.
* **Map** (key-value pairs): `HashMap`, `TreeMap`.
* **Queue** (FIFO): `PriorityQueue`, `Deque`.

---

## 13. Multithreading

* **Definition:** Executing multiple tasks simultaneously.
* **Creating Threads:**

  1. Extending `Thread` class and overriding `run()`.
  2. Implementing `Runnable` interface.
* **Important Methods:** `start()`, `run()`, `sleep()`, `join()`.
* **Synchronization:** prevents data inconsistency when multiple threads access shared resources.

---

## 14. File Handling (I/O in Java)

* Java provides **java.io** package for file operations.
* **Classes:**

  * `File` → represents file.
  * `FileReader`, `FileWriter` → read/write.
  * `BufferedReader`, `BufferedWriter` → efficient reading/writing.
* **try-with-resources** → auto-closes files after use.

---

## 15. Java 8 Features

* **Lambda Expressions:** `(a, b) -> a + b`, shorter anonymous methods.
* **Functional Interfaces:** Interfaces with a single abstract method (`@FunctionalInterface`).
* **Streams API:** Process collections (filter, map, reduce) in functional style.
* **Default Methods:** Allow methods with body in interfaces.
* **Date & Time API (java.time):** Improved date handling.

---

## 16. Memory Management

* **Stack Memory:** Stores method calls and local variables.
* **Heap Memory:** Stores objects and instance variables.
* **Garbage Collector (GC):** Automatically deletes unused objects.
* **Reference types:** Strong, weak, soft, phantom references.

---

## 17. Access Modifiers

* **public** → accessible everywhere.
* **protected** → accessible in same package + subclasses.
* **default (no keyword)** → accessible only in same package.
* **private** → accessible only within the class.

---

## 18. Differences (Common Interview Qs)

* **JDK vs JRE vs JVM:** JDK = development tools, JRE = runtime, JVM = executor.
* **Overloading vs Overriding:** Overloading → same method name, diff parameters (compile-time). Overriding → same method signature, redefined in child (runtime).
* **Abstract Class vs Interface:** Abstract class can have abstract + non-abstract methods; interface has only abstract methods (till Java 7, Java 8 added default methods).
* **String vs StringBuilder vs StringBuffer:** String → immutable, StringBuilder → mutable, not thread-safe, StringBuffer → mutable, thread-safe.

---

**detailed, structured notes** covering all important manual testing concepts — short enough to revise, detailed enough to Technical interview.

---

# 🧪 Manual Testing Notes (Complete)

---

## 1. What is Software Testing?

* Software Testing is the process of **evaluating software** to ensure it meets requirements and is free of defects.
* Goal → deliver **quality software** with minimal bugs.

---

## 2. Types of Testing

### 🔹 Based on Execution

* **Manual Testing** → tester executes test cases without automation tools.
* **Automation Testing** → tests are executed using tools/scripts.

### 🔹 Based on Knowledge

* **Black Box Testing** → focuses on input/output, tester doesn’t know internal code.
* **White Box Testing** → focuses on code structure, logic, and paths.
* **Grey Box Testing** → mix of both.

### 🔹 Based on Level

1. **Unit Testing** → testing individual components (done by developers).
2. **Integration Testing** → checking data flow between modules.
3. **System Testing** → testing complete system end-to-end.
4. **Acceptance Testing** → verifying product against business requirements (UAT).

### 🔹 Based on Approach

* **Functional Testing** → validates features (login, signup, cart, etc.).
* **Non-Functional Testing** → checks performance, security, usability, reliability.

---

## 3. Software Development Life Cycle (SDLC)

* **Requirement Analysis** → gathering requirements.
* **Design** → architecture & UI planning.
* **Implementation** → actual coding.
* **Testing** → verifying product.
* **Deployment** → release to production.
* **Maintenance** → support, bug fixing.

---

## 4. Software Testing Life Cycle (STLC)

1. **Requirement Analysis** → understand what to test.
2. **Test Planning** → prepare test strategy, tools, resources.
3. **Test Case Development** → design test cases & test data.
4. **Test Environment Setup** → prepare hardware/software for testing.
5. **Test Execution** → run tests, log defects.
6. **Test Closure** → prepare test reports, lessons learned.

---

## 5. Test Artifacts

* **Test Scenario** → high-level description of what to test.
* **Test Case** → detailed steps, input, expected result, actual result.
* **Test Data** → input values for test execution.
* **Defect Report (Bug Report)** → document describing issue found.
* **Traceability Matrix** → mapping requirements to test cases.

---

## 6. Defect Life Cycle

1. New → tester finds bug.
2. Assigned → bug assigned to developer.
3. Open → developer works on it.
4. Fixed → developer resolves it.
5. Retest → tester verifies fix.
6. Closed → bug is resolved successfully.
7. Reopened → bug persists.
8. Deferred/Rejected → not valid or postponed.

---

## 7. Testing Techniques

### 🔹 Black Box Techniques

* **Equivalence Partitioning** → divide input data into valid/invalid groups.
* **Boundary Value Analysis** → test values at boundaries (min, max, just inside/outside).
* **Decision Table Testing** → test combinations of inputs.
* **State Transition Testing** → test different states of application.

### 🔹 White Box Techniques

* **Statement Coverage** → every line of code executed at least once.
* **Branch Coverage** → every decision (if-else) executed.
* **Path Coverage** → every possible path executed.

---

## 8. Levels of Testing in Detail

* **Smoke Testing** → basic build verification (is app stable?).
* **Sanity Testing** → quick check of specific functionality.
* **Regression Testing** → check old features after changes.
* **Re-testing** → checking same defect again after fix.
* **Exploratory Testing** → testing without pre-defined test cases.
* **Ad-hoc Testing** → random testing using tester’s experience.

---

## 9. Non-Functional Testing

* **Performance Testing** → speed, stability.

  * Load Testing (expected users).
  * Stress Testing (beyond limit).
  * Endurance Testing (long duration).
* **Security Testing** → authentication, authorization, data safety.
* **Usability Testing** → user-friendly design.
* **Compatibility Testing** → runs on all devices/browsers.

---

## 10. Test Metrics

* **Defect Density** → defects per size of module.
* **Test Coverage** → % of requirements tested.
* **Defect Leakage** → bugs missed in one phase but found later.
* **Defect Removal Efficiency (DRE)** → % of defects removed before release.

---

## 11. Agile Testing

* Follows **Agile methodology** (Scrum/Kanban).
* Testing is **continuous and iterative**.
* **Daily stand-ups, sprint planning, retrospective** included.
* QA works closely with developers from start (Shift Left Testing).

---

## 12. Important Interview Q\&A (Manual Testing)

* **Difference between Smoke & Sanity Testing:**

  * Smoke → checks stability of build.
  * Sanity → checks specific functionality after changes.

* **Difference between Verification & Validation:**

  * Verification → “Are we building the product right?” (reviews, inspections).
  * Validation → “Are we building the right product?” (actual testing).

* **Severity vs Priority:**

  * Severity → impact of defect on application.
  * Priority → urgency of fixing defect.

* **Bug vs Defect vs Error vs Failure:**

  * Error → mistake in code.
  * Defect/Bug → deviation found during testing.
  * Failure → defect appears in production.

---

**detailed but clear points** so you can revise quickly and also speak confidently in interviews.

---

# 🤖 Automation Testing + Selenium WebDriver Notes

---

## 1. What is Automation Testing?

* Automation Testing is the process of **executing test cases using tools or scripts** instead of manual execution.
* Purpose → **save time, increase coverage, reduce human error, and improve accuracy**.

---

## 2. When to Use Automation Testing?

* Repetitive test cases (like regression testing).
* Large test data execution.
* Cross-browser/cross-platform testing.
* Load/performance testing.
* Not suitable for: one-time or exploratory testing.

---

## 3. Popular Automation Testing Tools

* **Selenium (Java/Python, open-source)**
* **TestNG / JUnit** → test frameworks
* **Cucumber (BDD)**
* **Cypress (JS-based)**
* **Playwright, Puppeteer**
* **Performance tools** → JMeter, LoadRunner

---

## 4. Selenium Overview

* Selenium is an **open-source automation tool for web applications**.
* Supports multiple languages (Java, Python, C#, JavaScript).
* Supports all major browsers (Chrome, Firefox, Edge, Safari).
* **Components:**

  1. **Selenium IDE** → record & playback (basic).
  2. **Selenium RC (deprecated)**.
  3. **Selenium WebDriver** → advanced, real browser interaction.
  4. **Selenium Grid** → run tests on multiple machines/browsers in parallel.

---

## 5. Selenium WebDriver

* **Definition:** WebDriver is a library that directly communicates with browsers using browser-specific drivers.
* Provides **API methods** to locate elements, interact with them, navigate pages, handle alerts, etc.
* Supported Browsers → Chrome, Firefox (GeckoDriver), Edge, Safari.

---

## 6. Locators in Selenium (Most Important)

Locators help Selenium find web elements.

* **By ID** → `driver.findElement(By.id("username"))`
* **By Name** → `driver.findElement(By.name("password"))`
* **By ClassName** → `driver.findElement(By.className("btn"))`
* **By TagName** → `driver.findElement(By.tagName("input"))`
* **By LinkText** → `driver.findElement(By.linkText("Login"))`
* **By PartialLinkText** → `driver.findElement(By.partialLinkText("Log"))`
* **By CSS Selector** → `driver.findElement(By.cssSelector("input#email"))`
* **By XPath** → `driver.findElement(By.xpath("//input[@id='email']"))`

👉 **XPath types:**

* Absolute XPath → `/html/body/div[1]/input`
* Relative XPath → `//input[@id='email']`
* XPath Functions → `contains()`, `starts-with()`, `text()`

---

## 7. Important WebDriver Methods

* **Browser Commands**

  * `get("url")`, `getTitle()`, `getCurrentUrl()`, `close()`, `quit()`
* **Navigation**

  * `navigate().to()`, `back()`, `forward()`, `refresh()`
* **Element Interaction**

  * `sendKeys()`, `click()`, `getText()`, `isDisplayed()`, `isEnabled()`, `isSelected()`
* **Waits**

  * Implicit Wait: `driver.manage().timeouts().implicitlyWait(10, TimeUnit.SECONDS)`
  * Explicit Wait: `WebDriverWait` with `ExpectedConditions`
  * Fluent Wait: polling at intervals
* **Handling Dropdowns**

  * `Select dropdown = new Select(element)`
  * `selectByIndex()`, `selectByValue()`, `selectByVisibleText()`
* **Handling Alerts**

  * `alert.accept()`, `alert.dismiss()`, `alert.getText()`
* **Frames & Windows**

  * `driver.switchTo().frame(index/id/name)`
  * `driver.switchTo().window(handle)`

---

## 8. Test Frameworks with Selenium

* **JUnit** → unit testing framework, simple annotations (`@Test`, `@Before`, `@After`).
* **TestNG (more popular)**

  * Supports parallel testing, annotations, grouping, priorities.
  * Generates HTML reports.
  * Example:

```java
@Test(priority=1)
public void loginTest() { ... }
```

---

## 9. Page Object Model (POM)

* **Design pattern** for test automation → separates test scripts from page elements.
* Improves **code reusability, readability, maintainability**.
* Each web page = one class with elements + methods.

---

## 10. Selenium Grid

* Used for **distributed testing** across multiple machines & browsers.
* Helps in **parallel execution** to save time.
* Example: Run tests on Chrome + Firefox simultaneously.

---

## 11. Advantages of Selenium

* Open-source (free).
* Supports multiple languages & browsers.
* Works on all OS (Windows, Mac, Linux).
* Large community support.

---

## 12. Limitations of Selenium

* Supports **only web applications** (not desktop/mobile apps directly).
* No built-in reporting (needs TestNG/ExtentReports).
* Requires programming knowledge.
* Handling CAPTCHA, OTP, and advanced graphics is difficult.

---

## 13. Common Interview Q\&A

* **Difference: Selenium WebDriver vs Selenium RC**

  * WebDriver communicates directly with the browser.
  * RC required a server in between (slower, deprecated).

* **Difference: findElement() vs findElements()**

  * `findElement()` → returns first matching element.
  * `findElements()` → returns list of all matching elements.

* **Implicit vs Explicit Wait**

  * Implicit → applies globally, waits for element before throwing exception.
  * Explicit → applies to specific element with condition.

* **Why TestNG over JUnit?**

  * TestNG supports parallel execution, flexible annotations, better reporting, priorities, and grouping.

* **What is Page Object Model (POM)?**

  * A design pattern that separates locators and test logic → improves maintainability.

---

Let’s now cover **TestNG** and **GitHub** in detail.

---

# 🧪 TestNG Notes

---

## 1. What is TestNG?

* **TestNG (Test Next Generation)** is a **testing framework inspired by JUnit and NUnit**.
* Provides advanced features like **annotations, parallel execution, grouping, prioritization, and reporting**.

---

## 2. Why TestNG in Selenium?

* Generates **HTML test reports automatically**.
* Supports **parallel execution** to save time.
* Allows **test case grouping and prioritization**.
* Handles **dependency testing** (run tests in sequence).
* Better suited than JUnit for **large automation projects**.

---

## 3. TestNG Annotations (Important)

* `@Test` → Marks a method as a test case.
* `@BeforeMethod` → Runs before each test case.
* `@AfterMethod` → Runs after each test case.
* `@BeforeClass` → Runs once before all tests in a class.
* `@AfterClass` → Runs once after all tests in a class.
* `@BeforeTest` → Runs before `<test>` tag in XML.
* `@AfterTest` → Runs after `<test>` tag in XML.
* `@BeforeSuite` / `@AfterSuite` → Runs before/after whole test suite.

---

## 4. TestNG Features

* **Prioritization** →

  ```java
  @Test(priority=1)
  public void loginTest() {}
  @Test(priority=2)
  public void dashboardTest() {}
  ```
* **Grouping** →

  ```java
  @Test(groups={"Smoke"})
  public void test1() {}
  @Test(groups={"Regression"})
  public void test2() {}
  ```
* **Dependency** →

  ```java
  @Test
  public void startApp() {}

  @Test(dependsOnMethods={"startApp"})
  public void loginTest() {}
  ```
* **Parallel Execution** → defined in `testng.xml`.

---

## 5. testng.xml File

* XML configuration file to control test execution.
* Example:

```xml
<suite name="AutomationSuite">
  <test name="RegressionTests" parallel="methods" thread-count="2">
    <classes>
      <class name="tests.LoginTest"/>
      <class name="tests.DashboardTest"/>
    </classes>
  </test>
</suite>
```

---

## 6. Reporting in TestNG

* Automatically generates **HTML and XML reports** after execution.
* Can be enhanced using **Extent Reports or Allure Reports**.

---

## 7. Advantages of TestNG

* Flexible annotations.
* Supports parallel execution.
* Built-in HTML reports.
* Easy integration with **Maven/Gradle + Jenkins (CI/CD)**.

---

---

# 🐙 GitHub Notes

---

## 1. What is GitHub?

* **GitHub** is a cloud-based platform for **version control and collaboration** using Git.
* It helps developers **store code, track changes, collaborate, and manage projects**.

---

## 2. Why GitHub for Testers & Developers?

* Store and share test scripts (manual/automation).
* Version control for Selenium projects.
* Collaboration with team members.
* Integrates with CI/CD tools like **Jenkins, GitHub Actions**.

---

## 3. Basic Git Commands (Important for Interviews)

* **Setup**

  ```bash
  git config --global user.name "YourName"
  git config --global user.email "youremail@example.com"
  ```
* **Initialize Repository**

  ```bash
  git init
  ```
* **Clone Repository**

  ```bash
  git clone <repo_url>
  ```
* **Check Status**

  ```bash
  git status
  ```
* **Stage & Commit**

  ```bash
  git add .          # Stage all files
  git commit -m "Added new test cases"
  ```
* **Push Changes**

  ```bash
  git push origin main
  ```
* **Pull Updates**

  ```bash
  git pull origin main
  ```
* **Branching**

  ```bash
  git branch new-feature
  git checkout new-feature
  git merge new-feature
  ```

---

## 4. GitHub Workflow (Simple Example)

1. Clone repo from GitHub.
2. Create a new branch for your changes.
3. Commit your changes locally.
4. Push branch to GitHub.
5. Create a **Pull Request (PR)** → reviewed by team.
6. Merge into main branch.

---

## 5. GitHub for Selenium Projects

* Store **TestNG test scripts + Page Object Model structure**.
* Share code with team.
* Use GitHub Actions for **automated test execution** after every code push.

---
Perfect 👍 Let’s now make **Manual + Automation Testing Documentation Notes** (Test Plan, Test Cases, Test Scenario, and related terms).
I’ll keep them **detailed, clear, and 2–3 lines each** so you can use them for **interviews + revision**.

---
