---
layout: post
title:  "Computer Science Terms"
date:   2016-05-15 10:00:00
categories: computer science
author: Carlos R. Mendoza
<!-- permalink: -->
---

*Last Update on May 15, 2016.*

<a name="compiler"></a>**Algorithm** - a set of step-by-step instructions to solve a problem.  

**Compiler** - a computer program or sets of programs that transforms [source code](#source-code) into [machine language](#machine-language) that a computer understands.  

**Constant** - an [identifier](#identifiers) with a value that cannot be altered while a program executes. This is opposite to the value of a variable, which can be altered during program execution.  

**Data Validation** - the process of checking for correctness, meaningfulness, and security of data to be inputted to the system to ensure a program operates with clean, correct, and useful data. Validation can be implemented by adding logic to an application or through a data dictionary.  
  
**Delegation** - an object relying on another object to provide a specific set of functionalities. This feature is often found in prototype-based languages such as JavaScript (prototypes).  

**Encapsulation** - A mechanism to prevent direct access to or manipulation of specific components belonging to an object/class, such as variables and methods, outside of that object/class. Typically, in programming languages, only methods belonging to the object/class can directly access the encapsulated components of that object/class.

**Enumeration Type** (also called enumeration or enum) - a data type consisting of a set of [identifier](#identifiers) that behave as constants in a language.  

<a name="identifiers"></a>**ETL (Extract, Transform, Loading)** - a process of database usage that does the following:

* **Extracts** - the process of reading data from a database.
* **Transforms** - the process of converting data to a format that is storable in the database or good for querying.
* **Loads** - the process of writing the data into the database.
	  
<a name="immutable"></a>**Identifiers** - a name given to a value that serves as a label. For instance, in JavaScript, variable and function names serve as identifiers.  
  
**Immutable** - a data type whose state cannot be modified after it is created. This is in contrast to [mutable](#mutable) data types, whose states can be altered after creation.

**Intermediate Language** - often refers to a language used by [high-level programming languages](#high-level-programming-language) which that do not output to [machine code](#machine-language) directly. The [source code](#source-code) is outputted to the intermediate language that is then compiled to machine code. Although not designed to be used as an intermediate language, other programming languages have frequently used C as an intermediate language because it has [compilers](#compiler) for many processors and operating systems.  

<a name="high-level-programming-language"></a>**Interpreter** - a computer program that reads [source code](#source-code) one line at a time and converts it to a format which can be executed by the processor.  

**High-level Programming Language** - a programming language that abstracts from the details of a computer, making it easier to use for humans.  

<a name="machine-language"></a>**Low-level Programming Languages** - a programming language that provides no or little abstractions to a [machine's language](#machine-language).  

**Machine Language (Machine Code)** - a set of instructions that a computer understands. These instructions are executed directly by the Central Processing Unit (CPU) of a computer.  

**Meta-Data** - data about data.  
  
<a name="mutable"></a>**Mixin** - a class in object-oriented programming that contains a combination of methods from other classes.

**Mutable** - a data type whose state can be modified after it is created. This is in contrast to [immutable](#immutable) data types, whose states cannot be altered after creation.
  
**Patch** - a piece of software to fix or improve a program or its supporting data.  
  
<a name="projection-queries"></a>**Polyfill** - code (or plugin) that can be added to a web application that allows functionality expected to work natively on a browser but that might not have yet been added to the browser. Polyfills allow for more consistency across browser APIs.  

<a name="source-code"></a>**Projection Queries** - the queries to a Datastore that specify properties of an entity to be returned. This lowers the amount of data being retrieved and returned in the response.  

**Polymorphism** - in object oriented programming (OOP), the practice of objects being able to share behavior is key. Polymorphism allows a child object to be able to override a behavior of a parent object while still maintaining the same interface. 

**Source Code** - set of computed instructions written in a human readable ([high-level](#high-level-programming-language)) computer language.
