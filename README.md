# PHP Foreach and Unset: Unexpected Behavior
This repository demonstrates an uncommon bug in PHP related to using `unset()` within a `foreach` loop on an array. Modifying the array during iteration can lead to unexpected results and skipped elements.

The `bug.php` file contains the problematic code, while `bugSolution.php` offers a corrected version.

This bug is subtle and can be difficult to spot, especially in larger codebases.  Understanding this behavior is crucial for writing robust and predictable PHP code.