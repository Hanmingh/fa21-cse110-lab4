1. line 9 prints 'values added: 20'.
2. line 13 prints 'final result: 20'.
3. line 9 prints 'values added: 20'.
4. The code returns an error, because unlike 'var', 'let' operation has block scope. Therefore, 'result' is undefined when it is called in line 13.
5. The code returns an error, because result is a constant and code in line 7 tries to reassign the constant.
6. Same as line 9. Nothing is printed since an error is returned.