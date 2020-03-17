## CHAPTER 01

# Introduction

IndyMicro.NET is an application template for creating modular monolithic applications that can evolve into microservices. 

### A cookbook of sorts

Use this project like a cookbook that provides ingredients and a recipe for creating modular applications.  There are many choices and factors that go into designing an application like this and this implementation makes many choices for you.  As in cooking, you are free to modify this recipe to your taste and IndyMicro.NET gives you a base to start from.  

Specifically, the following choices were made in picking this architecture with these goals in mind:

- Provide an evolvable application that can start as a **monolith** and move to **microservices** over time as a planned quality attribute
- Provide a **Domain Driven Design** approach to an application with good bounded contexts
- Make use of **ASP.NET class libraries** as loadable domain modules
- Make use of a **.NET Core HostBuilder** to dynamically load modules into a host process
- Provide an **infrastructure project template** for cross-cutting concerns such as security, configuration, logging and other core services provided by ASP.NET
- Provide a **module** **project template** that can be cloned and customized into more modules
- Provide a build that is deployable as a **monolith**
- Provide a build that is deployable as groups of modules or **microservices** hosted in resource groups in the cloud
- Provide a **sample** reference application

### Further Reading

- [Monolith First](https://martinfowler.com/bliki/MonolithFirst.html) by Martin Fowler
- [Modular Monolith with DDD](https://github.com/kgrzybek/modular-monolith-with-ddd) by Kamil Grzybek, much of the inspiration for this project came from here.



[< Back](index.md)





