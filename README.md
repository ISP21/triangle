## Testing with Code Coverage

`triangle.py` contains a function `is_triangle(a, b, c)`
that returns True if (a, b, c) are valid lengths of the sides of a triangle, and returns False otherwise.

`triangle_test.py` contains unit tests of is\_triangle.

## Instructions

1. Run the unit tests. They should all pass.

2. Run the tests using code coverage, then generate an html coverage report:
   ```bash
   coverage run -u unittest triange_test.py
   coverage html
   ```

3. View the report in a web browser. The file to open is `htmlcov/index.html`.

4. Is there any part of the code under test (`trinagle.py`) that was not tested?

   Write the Line Numbers Here: [          ]

5. Modify the tests so that all lines of the code are tested.

6. What lines in the **test** code were not executed?     
   Line Numbers: [                  ]

7. Normally, **all** the lines of test code should be executed.  When some part of test code is not executed it may indicate a problem with the tests.  Explain the problem in the unit test code. (write you answer below).

   Answer:








When done, push your changes to all files to Github, including this README.

### Install Coverage Package

On most systems you can use: `pip3 install coverage`.

For more info, see the Coverage 
_
