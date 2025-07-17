# Strings

Strings are ubiquitous in Jelly — you’ll use them when calling functions and when setting variables.

## Basic string literal

```jelly
"String Content"
```

## Multiline string literal

```jelly
"""
String Content
"""
```

## Variables inside a string

Insert a variable directly into a string using *string interpolation*:

```jelly
"Hello ${username}"
```

## Escaping quotes

If you need to include a double-quote (`"`) inside your string, escape it with a backslash (`\`). The backslashes are automatically removed when the Jellycut is built.