# PHP Type Juggling Pitfalls: Loose vs. Strict Comparison

This repository demonstrates a common PHP bug related to loose comparison (`==`) versus strict comparison (`===`).  Loose comparison can lead to unexpected behavior due to PHP's type juggling system.  This example highlights the importance of using strict comparison (`===`) when you need to ensure both value and type are identical.

## Bug Description:

The `bug.php` file shows how loose comparison can produce incorrect results when comparing values of different types.  The solution in `bugSolution.php` demonstrates the correct usage of strict comparison to avoid this issue.

## How to Run:

1. Clone this repository.
2. Run the `bug.php` script using your PHP interpreter.
3. Observe the output and compare it to the expected result.
4. Run the `bugSolution.php` script to see the corrected code.