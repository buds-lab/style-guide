# Budslab Coding Style Guide

For python please follow PEP 8: https://www.python.org/dev/peps/pep-0008/

For javascript use the AirBNB style guide https://github.com/airbnb/javascript

## General Rules

### Defining Human friendly variables and functions

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
- Acronyms: `text_message_request` is much better than `sms_request`
- `UPPERCASE`: It's annoying, difficult to read, and should be reserved for situations like calling an database where it's already labeled like that

## Python Variable Names

- Classes: `UpperCamelCase`
- functions: `lower_snake_case`
- variables: `lower_snake_case`


## Javascript Variable Names

- Classes: `UpperCamelCase`
- functions: `lowerCamelCase`
- variables: `lowerCamelCase`

## InfluxDB Variable Names

Because we use python most prominently with influx DB, we will follow the pythonic naming convention `lower_snake_case`. However if javascript names come up then it's not a problem



