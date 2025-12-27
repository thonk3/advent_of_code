
https://adventofcode.com/
https://github.com/thonk3/advent_cal

this is also backed up on github

last updated - `28 dec 2025`

## overview
> what do i want to do with this project
> solutions should be using plain vanilla code, no additional packages 
> should use the demo input as a unit test
> i want to play with aoc in multiple languages
> i dont want to seperate each day into each folder
> scripting tool might be just only in plain js

## repo folder structure

> wip changing project folder structure
updating project folder structure due to
- previous structure encourages duplication of inputs files with different programming language solutions
- heavy nesting of folders

```
src/
-- utils/
-- utils/templates/js_template.js
-- utils/templates/go_template.go
-- 2024/
-- 2025/
-- |- inputs/
-- |- |- input01
-- |- |- demo01
-- |- js_sol_01.js
-- |- go_sol_01.js
```

- how should i handle multi language utilities files
- utils should be common so its not repeated year over year
