# kata-stringcalculator-dotnet-core

## Credits

Author: Roy Osherove - TDD Kata 1 - String Calculator
Source: http://osherove.com/kata

## Before you start:

- Try not to read ahead.
- Do one task at a time. The trick is to learn to work incrementally.
- Make sure you only test for correct inputs. there is no need to test for invalid inputs for this kata

## String Calculator

1. Create a simple String calculator with a method signature:

    ———————————————
    ```csharp
    int Add(string numbers)
    ```
    ———————————————

2. The method can take up to two numbers, separated by commas, and will return their sum.
   for example "" or "1" or "1,2" as inputs.
   (for an empty string it will return 0)

   Hints:
   ——————

   - Start with the simplest test case of an empty string and move to one and two numbers
   - Remember to solve things as simply as possible so that you force yourself to write tests you did not think about
   - Remember to refactor after each passing test
     ———————————————————————————————
