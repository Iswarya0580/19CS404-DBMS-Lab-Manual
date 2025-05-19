# Experiment 9: PL/SQL – Procedures and Functions

## AIM
To understand and implement procedures and functions in PL/SQL for performing various operations such as calculations, decision-making, and looping.

---

## THEORY

PL/SQL (Procedural Language/SQL) extends SQL by adding procedural constructs like variables, conditions, loops, procedures, and functions. Procedures and functions are subprograms that help modularize the code and improve reusability.

### **Procedure**
A PL/SQL **procedure** is a subprogram that performs a specific action. It does not return a value directly but can return values using `OUT` parameters.

**Syntax:**
```sql
CREATE OR REPLACE PROCEDURE procedure_name (parameters)
IS
BEGIN
   -- statements
END;
```

To call the procedure

```sql
EXEC procedure_name(arguments);
```

### **Function**
A PL/SQL **function** is a subprogram that returns a single value using the RETURN keyword.

```sql
CREATE OR REPLACE FUNCTION function_name (parameters)
RETURN datatype
IS
BEGIN
   -- statements
   RETURN value;
END;
```

To call the function:

```sql
SELECT function_name(arguments) FROM DUAL;
```

Key Differences:

-A procedure does not return a value, whereas a function must return a value.
-Functions can be called from SQL queries, procedures cannot (in most cases).

## 1. Write a PL/SQL Procedure to Find the Square of a Number
## PROGRAM:
## OUTPUT:

## 2. Write a PL/SQL Function to Return the Factorial of a Number
## PROGRAM:
## OUTPUT:

## 3. Write a PL/SQL Procedure to Check Whether a Number is Even or Odd

## PROGRAM:
## OUTPUT:

## 4. Write a PL/SQL Function to Return the Reverse of a Number

## PROGRAM:
## OUTPUT:
---

## 5. Write a PL/SQL Procedure to Display the Multiplication Table of a Number

## PROGRAM:
## OUTPUT:

## RESULT
Thus, the PL/SQL programs using procedures and functions were written, compiled, and executed successfully.
