# Database System Concepts 7th edition

by Abraham Silberschatz, Henry F. Korth, S. Sudarshan

# Chapter 1 Introduction

Databases are used in 2 modes:

- OLTP - Online trasaction processing: a large number of users, each user retrive small amounts of data, small updates.
- OLAP - Online analytics processing (data analytics): process a large amount of data, draw some conclusion/stats/insights out of the data, infer rules/decisions.

file-processing system's disadvantages:

- Data redundancy and inconsistency. data inconsistency: various copies of the same data may no longer agree.
- Difficult to access data. file-processing do not allow needed data retrieval to be convenient and efficient.
- Data isolation.
- Integrity problems.
- Atomicity problems. atomicity: bank system to transfer $500 from A to B, and failed during the transaction. Either rollback to the state before transferring, or the state after transfer: it must happen in its entirely or not at all.
- concurrent access anomalies. supervision is difficult to provide because data may be accessed by many different application programs that have not been coordinated previously.
- security problems.

Data Models

- Relational model. Use a collection of tables to represent data and the relationships among data. Tables aka relations. Structured in fixed-format records. Each table contains records of a paticular type. Each record type defines a fixed number of fields.
- Entity-Relationship(E-R) model. Use a collection of basic objects/entities, and relationships among objects. Widely used in db design.
- Semi-structured data model. Individual data items of the same type may have different set of attributes. JSON/XML are widely used representations.
- Object-based data model. db system allow procedures to be stored and executed. Can be seen as extending the relational model with encapsulation, methods and object identity.

Data Abstraction

- physical level
- logical level
- view level
