1. line 9 prints:
    ```
    values added:  20
    ```
2. line 13 prints:
    ```
    final result:  20
    ```
3. line 9 prints:
    ```
    values added:  20
    ```
 4. line 13 prints:
    ```
    ReferenceError: result is not defined
    ```
    This is because variables created by the keyword *let* have blocked scope. Therefore, the scope of result is limited inside the if block.
  5. line 9 prints:
    ```
    ReferenceError: result is not defined
    ```
    This is because constant variable cannot be modified
  6. line 13 prints (after fixed previous error):
    ```
    ReferenceError: result is not defined
    ```
    This is because variables created by the keyword *const* have blocked scope. Therefore, the scope of result is limited inside the if block.

        