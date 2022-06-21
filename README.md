# Lab04PetStore
Inheritance/overwriting Application Lab

Model for Inheritance (Where the curved boxes represent are the functions and the square boxes are the classes)
```mermaid
graph TD;
    A[Pets]--> E(get/setName, get/setBreed, makeNoise);
    E --> B[Cat] --> F(chaseMice);
    E --> C[Dog] -->G(playFetch);
    E --> D[Hamster] --> H(wheelRun);
```
Base class: pets
Inheritting classes: cat, dog, hamster
//getters/setters for name and breed--these are simply inheritted by other classes
//makeNoise -- to be overwritten
//each animal gets at least one special task that it can do--dogs fetch, cats chase mice, hamsters run on wheels
//Maybe they have to make a function for main that generates an array list of pets or something
//Either that or maybe cat uses array lists/regular arrays to store mice it has caught
