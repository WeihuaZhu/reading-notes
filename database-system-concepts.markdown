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
- Atomicity problems.
