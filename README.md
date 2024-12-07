# Type '{ x: number; y: number }' is missing in the function parameter
This TypeScript code demonstrates a common error:  incorrectly defining function parameters.  The function `printCoord` expects an object with `x` and `y` properties, but the provided object is missing these properties.

## Bug
The original code lacks the type definition for the parameter. This results in the compiler error: Type 'number' is not assignable to type '{ x: number; y: number; }'.