# clojure-game-geek

This repo was created while working through the [Lacinia](https://github.com/walmartlabs/lacinia) GraphQL framework tutorial.

The tutorial is available at http://lacinia.readthedocs.io/en/latest/tutorial/

Each student effectively cuts-and-pastes code sections into files in their IDE, building and exercizing the application as the tutorial progresses. It helps you wrap your mind around the concepts without getting overwhelmed as the system gets refactored and bigger.


### Why this product version may be useful to others studying this tutorial:

- The project template and dependencies are updated to their current versions (as of December 2021).
- Commits are made at the completion of each section and labeled so it's easy to see the progression of each file as intended by the author.
- Problems or confusion I encountered along the way in my development environment are resolved in the section they were introduced.


The development environment used was VS Code/Calva on Windows, remoting via WSL to a Ubuntu 20.04 VM. The server is effectively containerized and required { :host "0.0.0.0" } configuration in order to access http://localhost:8888 from a browser in Windows.

The current versions of dependencies did not introduce any problems with the tutorial's functioning.


[Here](https://github.com/walmartlabs/clojure-game-geek) is the example code prepared by the tutorial author with the commits as he developed it.
