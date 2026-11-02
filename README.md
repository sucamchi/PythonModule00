*This project has been created as part of the 42 curriculum by scamlett.*

# Python Module 00: Hello, Garden

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![42](https://img.shields.io/badge/42-Málaga-000000)

## Description

The very first step of the 42 Python track. Every exercise is a small
garden-themed function: greet the community, compute the area of a plot,
add up a harvest, decide whether a plant needs water. The goal is to get
comfortable with the basic building blocks of the language before anything
else is built on top of them.

| Exercise | File | What it does |
|----------|------|--------------|
| ex0 | `ft_hello_garden.py` | Prints a greeting |
| ex1 | `ft_garden_name.py` | Reads a garden name with `input()` and echoes it |
| ex2 | `ft_plot_area.py` | Multiplies length by width |
| ex3 | `ft_harvest_total.py` | Sums three days of harvest |
| ex4 | `ft_plant_age.py` | Says if a plant is ready to harvest (`if` / `else`) |
| ex5 | `ft_water_reminder.py` | Reminds you to water after 2 days |
| ex6 | `ft_count_harvest_iterative.py`, `ft_count_harvest_recursive.py` | Counts down to harvest day, once with a loop and once with recursion |
| ex7 | `ft_seed_inventory.py` | Formats a seed report based on its unit, with type hints |

## Instructions

Each file defines one function and does not run anything on its own. Import
it and call it:

```bash
cd ex6
python3 -c "from ft_count_harvest_recursive import ft_count_harvest_recursive as f; f()"
```

## What I learned

- Reading user input with `input()` and converting it with `int()`
- f-strings for formatting output
- Branching with `if` / `elif` / `else`
- `for` loops with `range()`, and how the same countdown can be written
  recursively (with a base case so it stops)
- Default arguments, and why `None` is a safer default than a mutable value
- Adding type hints to a function signature
