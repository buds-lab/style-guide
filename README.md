# Budslab Coding Style Guide

## Python

For python please follow PEP 8: https://www.python.org/dev/peps/pep-0008/

Below are some simple conventions

### Variable Names

- Classes: `CapWords`
- functions: `lower_snake_case`
- variables: `lower_snake_case`

### Defining Human friendly variables

Good
```python
def calculate_discomfort (temperature, humidity, light):
  return (temperature + humidity + light)
```

Bad
```python
def c_disc(t,h,l)
  return (t + h + l)
```

### Please Avoid

- Using `__trailing` of `__dunderscores__` in definitions. These should just be reserved for python
- Lines longer than 79 characters. User backslashes `\` to break the lines
- Unecessary comments `x = x + 1                 # Increment x`
