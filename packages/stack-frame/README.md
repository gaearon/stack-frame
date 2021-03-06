# `stack-frame`

A stack frame.

# API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## ScriptLine

A container holding a script line.

### lineNumber

The line number of this line of source.

Type: [number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)

### content

The content (or value) of this line of source.

Type: [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

### highlight

Whether or not this line should be highlighted. Particularly useful for error reporting with context.

Type: [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)

## StackFrame

A representation of a stack frame.

### getFunctionName

Returns the name of this function.

Returns **([string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | null)** 

### getSource

Returns the source of the frame.
This contains the file name, line number, and column number when available.

Returns **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** 

### toString

Returns a pretty version of this stack frame.

Returns **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** 
