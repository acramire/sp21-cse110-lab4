1. values added: 20

2. final result: 20

3. values added: 20

4. The following error is returned: "error: ReferenceError: Can't find variable: result".
This is because the 'let' keyword when declaring the result variable narrows the scope of the variable to the if statement its in.

5. The following error is returned: "error: TypeError: Attempted to assign to readonly property." 
This is because the 'const' keyword when declraring the variable 'result' made the variable a constant, so you cannot modify it after initialization.
So, in line 7 when we are trying to modify the variable, it throws that error. Therefore, the code does not make it to line 9 or 13

6. Same as #5

7.
