---
title: ActiveRecord Obstacle Course
length: 120
tags: activerecord, rails
---

## Goals

For Everyone:
* Practice using ActiveRecord for problems beginners commonly us Ruby to solve
* Practice finding and reading ActiveRecord documentation

For Advanced Students:
* Gain an understanding of `joins` and `includes`

## Instructions

1. Clone Storedom and checkout the `activerecord-obstacle-course` branch

  `git clone -b activerecord-obstacle-course git@github.com:turingschool-examples/storedom.git`

1. Start with the top test within `spec/models/activerecord_obstacle_course_spec.rb` and work in order

  Note: There's one skipped spec. Ignore it until the very end.
  
1. Most of the tests follow the same format...

  Leave the Ruby as is or comment it out -- Don't erase.
  ```ruby
  # -----------------------------
  # A section with some Ruby code
  # -----------------------------
  ```
  
  Write a refactored implementation using ActiveRecord. Assign to the same variables as above.
  ```ruby
  # -----------------------------
  # A section for you to write refactor the Ruby code
  # -----------------------------
  ```
  
  Leave the expectations alone. They will determine whether you have a working solution.
  ```ruby
  # -----------------------------
  # The expectation
  # -----------------------------
  ```

1. When you think you have successfully refactored one test, show it to your instructor before moving on. If the instructor is busy, get in the queue and start the next problem.
  
## If You Finish Early

* Break your solutions into scopes and/or class methods.
* Try to implement one example using ActiveRecord's `merge`.
