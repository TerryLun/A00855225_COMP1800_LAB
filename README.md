Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR
    (pull request). Is there other keywords that can accomplish the same thing?

A1: The following keywords can all auto close an issue:
    "close, closes, closed, fix, fixes, fixed, resolve, resolve, resolved"

Q2: Do you have to create a new PR EVERYTIME you want to close an issue,
    or is it possible to close multiple issues within a single PR? If so,
    how?

A2: one PR can close multiple issues. Use multiple "keywords + issue number" to auto-close
    all issues you want to close

Q3: Provide an example of using map that is different from the one I have done.
    Your example must use map both as a named function declaration and with an
    anonymous function.

    Within comments, explain exactly what map is doing. Finally, why is the
    "transformation function" we discussed in class sometimes referred to
    as a callback function.

A3: // example 1
    let numbers = [1, 2, 3];
    // map() calculates the exponent of each number in numbers array and save all the result in a new array called sqrt
    let sqrt = numbers.map(function(num) {
        return num * num;
    })

    // example 2
    let numbers = [1, 4, 9];
    function returnRoot(num) {
      return math.sqrt(num)
    }
    // map() calculates the square root of each number in numbers array and save all the result in a new array called root
    let root = numbers.map(returnRoot)
