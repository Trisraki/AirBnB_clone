# 0x00. AirBnB clone - The console
# Welcome to the AirBnB clone project! **The goal of the project is to deploy on your server a simple copy of the AirBnB website.**

You won’t implement all the features, only some of them to cover all fundamental concepts of the higher level programming track.

First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:
- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine

What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc…
* Do operations on objects (count, compute stats, etc…)
* Update attributes of an object
* Destroy an object

## *Learning Objectives*

* How to create a Python package
* How to create a command interpreter in Python using the cmd module
* What is Unit testing and how to implement it in a large project
* How to serialize and deserialize a Class
* How to write and read a JSON file
* How to manage datetime
* What is an UUID
* What is *args and how to use it
* What is **kwargs and how to use it
* How to handle named arguments in a function

### Tasks
0. README, AUTHORS
1. Be pycodestyle compliant!
2. Unittests
3. BaseModel
4. Create BaseModel from dictionary
5. Store first object
6. Console 0.0.1
7. Console 0.1
8. First Usery7
9. More classes!
10. Console 1.0
11. All instances by class name
12. Count instances
13. Show
14. Destroy
15. Update
16. Update from dictionary
17. Unittests for the Console!

