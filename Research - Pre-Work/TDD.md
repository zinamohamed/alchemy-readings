## Test Driven Development By Example - Kent Beck

## Preface
    - Every developer should be writing code with the intention to keep it clean and not having to worry about leaving a long bug trail.
    - The best way to do that Beck argues is "Test-Driven Development" aka TDD:
        - Write new code only if you first have a failing automated test
        - Eliminate duplication
    - Ths seems pretty straightforward but proves to be difficult for most developers.
        - You must write your own tests, and writing tests isn't easy.
    - Task Programming
        - Write a test that doesn't work
        - Make the test work quickly
        - Elimante all duplication
    * Red/green/refactor
  

## Story- Time
      - This section tells the story of ward at WyCash when he and his team were tasked to handle bonds in different currencies.
      - His team were able to succesfully complete the task given to them by the manager and increasing the overall value of WyCash.
      - The did this by having a clear method, motive and oppurtunity.

## Section I: Money Example
    - In this section Beck runs through the cycle of TDD
        1) Add a little test
        2) Run all tests and fail
        3) Make a little change
        4) Run the tests and succeed
        5) Refactor to remove duplication
    - Beck mentions how important it is to keep a to-do list of sorts to keep track of tasks and tackling them in short bursts
    - The goal of TDD is writing clean code, that works!