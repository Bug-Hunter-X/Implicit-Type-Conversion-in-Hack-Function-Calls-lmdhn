# Implicit Type Conversion in Hack Function Calls

This repository demonstrates a subtle bug in Hack related to implicit type conversion in function calls. The `foo` function has an implicitly declared return type of `int`, however, if this return type were to be changed, it could lead to unexpected errors.