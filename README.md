# [Advent of Code][1]

It's the most wonderful time of the year. While everyone sings the "12 Days of
Christmas" song, we programmers solve the 25 days of Christmas problems.

### Small Disclaimer

I realized, while going through the 2021 problems, that [there's a points system
and a stars system][2]. I am only going for the stars here. While sharpening
programming skills, and proving mettle, feels good and brings good social
status... I prioritize family during Christmas, so I'd be slow here. So, you may
not be able to use this repository to rank up during the event. Sorry; not
sorry. This repository exists to show how I translate the problems into code to
find their solutions.

## The Setup

This repository is a parent repository for all the events — from 2015 til date.
Each year is a sub-repository to separate concerns of the event itself. You can
use this setup to read through all the code in one place. It saves the time of
clicking through GitHub for all repositories.

## The Runner

Questions in Advent of Code (henceforth a.k.a AoC) are story problems. The
solution should take in a file (the input file) and return an answer. The answer
is used to verify if the solution is correct.

Each AoC repo has three types of files

- `<DAY>.rb` files which solve the problem
- `<DAY>-ex.in` which is the example in the story to explain the problem
- `<DAY>.in` which is the actual input for the problem

I do not commit the `<DAY>-ex.in` and `<DAY>.in` files since these can be gotten
from the AoC website.

To run these solutions...

1. Ensure you have the proper input file in the same level as the solution
file; named appropriately
2. Check with the `File.readlines(...)` line in the solution code that you're
getting the actual input file you want to work with
3. Run the file.

## Contributions

None. Please. Thank you.

## Licensing

Honestly, this has no license. You can plagiarise as much as you want. This is a
learning exercise for me, as it should be for you. I've tagged on the MIT
License to this. But honestly, I haven't even read the thing. So, enjoy!

  [1]: https://adventofcode.com/
  [2]: https://twitter.com/Yaasky/status/1474919955112071169
