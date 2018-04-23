# Back-end questions - .NET

### Simple principles

* What are simple and reference types? What are the differences? Where are they stored?
* There are two types of transformations in c# tell me about it
* What is boxing and unboxing?
* Differences between ref and out
* Tell me about "sealed" and "partial"
* "Checked", "Unchecked" for what is used, which is set by default?
* What are immutable objects?
* Polymorphism, Hermertherization, Inheritance - tell me about it
* Explicit interface implementation. Difference between explicit interface implementation and implicit interface implementation
* Covariance vs Contravariance in C#
* Class vs Struct
* IQueryable<T> vs IEnumerable<T>

### Design patterns

* SOLID - tell me about pattern, go through all letters
* Tell me about two design patterns you use, skip singleton or tell me about it + two other
* Describe design pattern XYZ (https://sourcemaking.com/design_patterns)
* IoC vs DI

### Multi-threading

* What are the thread synchronization mechanisms?
* How can you queue async calls?
* What is the difference between Thread and Task?
* Difference between Thread and Process
* What is the critical section?
* What are the ways to set up a critical section?
* BlockingCollection - tell me for what it's used
* Which collections are Thread safe in C#?
* What is the difference between the lock and the monitor?
* Could you tell me anything about Interlocked class?
* Const vs readonly - which is better to use, which can be changed in runtime?

### Garbage collection

* What is garbage collection?
* When object is deleted from GC?
* Garbage Collector - Compacting
* Large object heap - from what size objects are transfered directly to large object heap
* Difference between NGen and JIT
* Describe generations in GC

### Object programming

* Interface vs abstract class, differences

### Database / ORM / Entity Framework

* Do you know what ACID is? Tell me about every letter
* SQL vs NOSQL - when it's good to use non relational databases
* Tell me about isolation levels, differences etc.
* What types of database normalization you know?
* What's the difference between clustered and non-clustered index?
* Tell me about “SELECT N+1” problem in Object-Relational mapping (ORM)
* For what “HAVING” statement is used in T-SQL?
* Explain differences between inner join, left join, right join etc
* Explain differences between union vs union all / except / intersect
* What is the difference between Single() vs First()
* Explain difference between optimistic and pessimistic concurrency? Explain shortly how both works.
* Explain difference between Add() vs Attach() in Entity Framework
* What is a default transaction isolation level in EF 6 for SQL Server?
* SQL Server connection pooling 

### Common not directly programming

* Describe the CI / CD pipeline
* Computational complexity - np hard problem etc.
* Xslt → what is it? For what is used?
* Xsd → how strong you can validate values by it?

### Testing

* Unit testing vs integration testing

### Other

* What a,b,c means in WCF?
* What binding types are used in WCF?
* How you can connect with server via WCF?
* How you would implement your own basic DI container, what methods it will have inside
* What data structure would you create to make sure that a class that has 15 variables and 3 variables is uniquely identified will never be duplicated when added to a collection?
* If you had two objects of the same class that are identified by 3 variables (they have more of them) then how would you compare that both are the same object without using multiple if statements?
* Tell me about Docker, for what it's used, cons vs pros
* Closures in C#. Do they exist? If so, show an example
* Describe briefly OWIN standard
* PUT vs POST method in HTTP. When which one should be used?
