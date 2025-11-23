# Problem Statement: Campus Course & Records Manager (CCRM)

## Project Statement
Many small to medium-sized academic institutions currently rely on manual, decentralized, or outdated methods (like spreadsheets or simple desktop databases) for managing core academic operations. This leads to several critical issues:
- **Inconsistency and Error**: Data entry is prone to human error, resulting in incorrect grades, flawed transcripts, and inaccurate enrollment records.
- **Inefficiency**: Generating basic reports, calculating GPA, and managing file backups require significant manual effort and time.
- **Lack of Structure**: The data lacks a clear, programmatic structure, making it difficult to scale, analyze, or integrate with other systems.

**CCRM** addresses this by providing a robust, centralized, and structured console-based application built on Java SE principles to handle these records efficiently and accurately.

---

## Scope of Project CCRM

The scope of the Campus Course & Records Manager (CCRM) is strictly defined as a Java SE console-based application focused on core data management within a single environment.

**Core Functional Scope:**

- **Records Management:** Creating, reading, updating, and deleting records for Students and Courses.
- **Academic Operations:** Managing Enrollments (linking students to courses), recording Grades, and calculating GPA.
- **Reporting:** Generating standardized Transcripts for students.
- **File Utility:** Implementing Data Persistence through structured CSV import/export and demonstrating recursive file backup capabilities using Java NIO.2.

**Exclusions (Out of Scope):**
- **Web/GUI Interface:** The project is limited to a command-line interface (CLI).

- **Database Integration:** It does not use external databases (e.g., SQL, NoSQL); persistence relies solely on file I/O (CSV, serialized objects).

- ****Networking/Security:**** It is a single-user application and does not include user roles, authentication, or network capabilities.

## Target Users

CCRM is designed to be used by administrative personnel who manage academic data in a small-scale or educational environment.

- **Registrars/Admissions Staff**: Creating new student records and managing enrollment status (enroll/unenroll).
- **Academic Administrators**: Creating and updating course details, and assigning instructors.
- **Records/Grading Clerks**: Entering marks, computing GPAs, and generating official transcripts.
- **Java Developers/Students**: Demonstrating practical application of OOP, NIO.2, Streams, and Design Patterns.