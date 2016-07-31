
# Composing Programs Notes

# Abstract

Welcome to Composing Programs, a free online introduction to programming and computer science.

In the tradition of [SICP](http://mitpress.mit.edu/sicp/), this text focuses on methods for abstraction, programming paradigms, and techniques for managing the complexity of large programs. These concepts are illustrated primarily using the [Python 3](http://www.python.org/) programming language.

In addition to reading the chapters below, you can apply your knowledge to the [programming projects](http://www.composingprograms.com/projects.html) that accompany the text and visualize program execution using the [Online Python Tutor](http://www.composingprograms.com/tutor.html).

Instructors: If you are interested in adapting any of these materials for your courses, please [fill out this short survey](https://docs.google.com/forms/d/1lcDf-_y9t1oSDH_-HFz3UhUFouAX1518XeCMnlRISss/viewform) so that we can support your efforts.

From:[http://www.composingprograms.com/](http://www.composingprograms.com/)
Composing Programs by John DeNero, based on the textbook Structure and Interpretation of Computer Programs by Harold Abelson and Gerald Jay Sussman, is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.

# Structure

## Chapter 1: Building Abstractions with Functions

* [1.1 Getting Started](http://www.composingprograms.com/pages/11-getting-started.html)
* [1.2 Elements of Programming](http://www.composingprograms.com/pages/12-elements-of-programming.html)
* [1.3 Defining New Functions](http://www.composingprograms.com/pages/13-defining-new-functions.html)
* [1.4 Designing Functions](http://www.composingprograms.com/pages/14-designing-functions.html)
* [1.5 Control](http://www.composingprograms.com/pages/15-control.html)
* [1.6 Higher-Order Functions](http://www.composingprograms.com/pages/16-higher-order-functions.html)
* [1.7 Recursive Functions](http://www.composingprograms.com/pages/17-recursive-functions.html)

## Chapter 2: Building Abstractions with Data

* [2.1 Introduction](http://www.composingprograms.com/pages/21-introduction.html)
* [2.2 Data Abstraction](http://www.composingprograms.com/pages/22-data-abstraction.html)
* [2.3 Sequences](http://www.composingprograms.com/pages/23-sequences.html)
* [2.4 Mutable Data](http://www.composingprograms.com/pages/24-mutable-data.html)
* [2.5 Object-Oriented Programming](http://www.composingprograms.com/pages/25-object-oriented-programming.html)
* [2.6 Implementing Classes and Objects](http://www.composingprograms.com/pages/26-implementing-classes-and-objects.html)
* [2.7 Object Abstraction](http://www.composingprograms.com/pages/27-object-abstraction.html)
* [2.8 Efficiency](http://www.composingprograms.com/pages/28-efficiency.html)
* [2.9 Recursive Objects](http://www.composingprograms.com/pages/29-recursive-objects.html)

## Chapter 3: Interpreting Computer Programs

* [3.1 Introduction](http://www.composingprograms.com/pages/31-introduction.html)
* [3.2 Functional Programming](http://www.composingprograms.com/pages/32-functional-programming.html)
* [3.3 Exceptions](http://www.composingprograms.com/pages/33-exceptions.html)
* [3.4 Interpreters for Languages with Combination](http://www.composingprograms.com/pages/34-interpreters-for-languages-with-combination.html)
* [3.5 Interpreters for Languages with Abstraction](http://www.composingprograms.com/pages/35-interpreters-for-languages-with-abstraction.html)

## Chapter 4: Data Processing

* [4.1 Introduction](http://www.composingprograms.com/pages/41-introduction.html)
* [4.2 Implicit Sequences](http://www.composingprograms.com/pages/42-implicit-sequences.html)
* [4.3 Declarative Programming](http://www.composingprograms.com/pages/43-declarative-programming.html)
* [4.4 Logic Programming](http://www.composingprograms.com/pages/44-logic-programming.html)
* [4.5 Unification](http://www.composingprograms.com/pages/45-unification.html)
* [4.6 Distributed Computing](http://www.composingprograms.com/pages/46-distributed-computing.html)
* [4.7 Distributed Data Processing](http://www.composingprograms.com/pages/47-distributed-data-processing.html)
* [4.8 Parallel Computing](http://www.composingprograms.com/pages/48-parallel-computing.html)

# Tree
```
.
├── exercises
│   ├── cap-1
│   │   ├── advanced.py
│   │   ├── basic.py
│   │   └── intermediate.py
│   ├── cap-2
│   │   ├── advanced.py
│   │   ├── basic.py
│   │   └── intermediate.py
│   ├── cap-3
│   │   ├── advanced.py
│   │   ├── basic.py
│   │   └── intermediate.py
│   └── cap-4
│       ├── advanced.py
│       ├── basic.py
│       └── intermediate.py
├── lectures
│   ├── cap-1
│   │   ├── control.py
│   │   ├── defining_functions.py
│   │   ├── defining_new_functions.py
│   │   ├── elements_of_programming.py
│   │   ├── getting_started.py
│   │   ├── higher_order_functions.py
│   │   └── recursive_functions.py
│   ├── cap-2
│   │   ├── data_abstraction.py
│   │   ├── efficiency.py
│   │   ├── implementing_classes_and_objects.py
│   │   ├── introduction.py
│   │   ├── mutable_data.py
│   │   ├── object_abstraction.py
│   │   ├── object_oriented_programming.py
│   │   ├── recursive_objects.py
│   │   └── sequences.py
│   ├── cap-3
│   │   ├── exception.py
│   │   ├── functional_programming.py
│   │   ├── interpreters_for_languages_with_combination.py
│   │   ├── interpreters_for_language_with_abstraction.py
│   │   └── introduction.py
│   └── cap-4
│       ├── declarative_programming.py
│       ├── distributed_computing.py
│       ├── distributed_data_processing.py
│       ├── implicit_sequences.py
│       ├── introduction.py
│       ├── logic_programming.py
│       ├── parallel_computing.py
│       └── unification.py
├── LICENSE
└── README.md
```

10 directories, 43 files


# Collaboration

You can try create a new PR adding exercises based on the structure above.


I advise you to use `hub` for handling PR's with command line, but you can use the github GUI also.

    hub fork
    git checkout -b exercise-cap1-basic
    git add .
    git commit
    git push
    hub pull-request

# License
MIT