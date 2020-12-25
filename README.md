# Timetable-Generator-Genetic-Algorithm
Timetable Generation using Genetic Algorithm

### Problem
    The assignment is to find generic solution that will facilitate generating schedule for university using
    “Genetic Algorithm”.
    • You have to write code from scratch.
    • You cannot use any built-in library for the implementation of Genetic Algorithm except Pandas
    and NumPy.
    • You can use any kind of crossover
    • You can choose any rate of mutation (which can be justifiable)
    • You have to roulette wheel selection for selecting potentially useful solutions for recombination
    (Chromosomes).
    The success of solution is estimated on fulfillment of given constraints and criteria. Results of testing the
    algorithm show that all hard constraints are satisfied, while additional criteria are optimized to a certain
    extent.

### Constraints
    There are set of constraints that need to be fulfilled.
    ## Hard Constraints
      • No teacher can hold two classes at the same time
      • No section can listen for two classes at the same time
      • No classroom can receive two classes at the same time
      • No teacher can hold three consecutive classes
      • There will be no class before 8:30 am and after 5:00 pm.
      • University will remain close as there will be no class on weekends (Sat, Sun)
      The above-mentioned constraints must be satisfied.
    ## Soft Constraints
      • There will be no class from 1-2 on Friday.
      • No section can hold three consecutive classes.
      • A subject having multiple forms, such as lectures and labs, the preferred order is: lecture and
      lab.
      • One hour for faculty meeting in a week when there is no class except Friday’s prayer break.
