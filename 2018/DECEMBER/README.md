# PuneRbUsersMeetup Dec 2018

## Rake - An Overview

##                 Rake 
                  /   \
               Ruby   Make

Rake is build language with **purpose** similar to Ant and Make. 

**Purpose**
______

* was developed to manage the build process of software projects.
* the convinience and flexibility which ruby provides, rake has now become a primary 
  methods for automation of various task in ruby projects.

**Why Rake?**
______

__Rake is declarative__
* The expected results are specified. It carries out the associated and their dependent tasks
  as the necessity is.
* Rake will do as little as much as necessary work to produce a known state.

> **Example**
> A build in task may involve creating a file.
> It automaically check for the specified item in directory.
> It wont run if upto date copies exists.

**Working with Rake**
All tasks to be run are described inside a file named ```Rakefile``` which is generally located in 
the application root.
```Rakefile``` is nothing but a ruby program written in a partivular format.

```ruby

desc "Sample Task"
task :sample do
  puts "hi"
end

```





