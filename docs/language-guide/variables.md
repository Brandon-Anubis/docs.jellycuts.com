# Traditional Variables

Variables in Jelly are **mutable** — their value can be changed after they’re created. A variable can hold values coming from:

* A string
* A number
* A *Magic Variable*
* A *Global Variable*

## Variable with a string value

```jelly
var HelloWorld = "Hello World"
```

### Multiline string value

```jelly
var HelloWorldLong = """
Hello World!
I have multiple lines
"""
```

## Variable with a number value

```jelly
var MeaningOfLife = 42
```

## Variable with a Magic Variable value

Convert an existing magic variable into a traditional variable:

```jelly
var MyVariable = FunctionOutput
```

## Variable with a Global Variable value

Global variables are *read-only*. To mutate their value assign them to a regular variable first:

```jelly
var MutableGlobalVar = Shortcut Input
```

## Variables inside a string

See the [Strings](strings.md) guide for inserting variables into a string.

---

# Assigning data to a variable

## Assignment after initialisation

```jelly
// Initial value
var x = Shortcut Input

// New value
x = "Hello World!"
// or
var x = "Hello World!"
```

## Addition after initialisation

```jelly
// Initial value
var x = Shortcut Input

// New value
x += "Hello World!"
// or
var x += "Hello World!"
```

Using `+=` will turn the variable into an *array*, mirroring Shortcuts’ **Add to Variable** action.