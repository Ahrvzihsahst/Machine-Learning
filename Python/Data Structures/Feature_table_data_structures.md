Sure, here's a feature table summarizing some of the common data structures in Python:

| Data Structure | Description                                  | Mutable | Iterable | Ordered | Duplicate Elements | Example Declaration                 | Example Usage                                      |
|----------------|----------------------------------------------|---------|----------|---------|--------------------|-------------------------------------|---------------------------------------------------|
| List           | Ordered collection of items                 | Yes     | Yes      | Yes     | Yes                | `my_list = [1, 2, 3]`               | `my_list.append(4)`<br>`print(my_list)`            |
| Tuple          | Ordered collection of items (immutable)     | No      | Yes      | Yes     | Yes                | `my_tuple = (1, 2, 3)`              | `print(my_tuple[0])`<br>`for item in my_tuple:`     |
| Set            | Unordered collection of unique items        | Yes     | Yes      | No      | No                 | `my_set = {1, 2, 3}`                | `my_set.add(4)`<br>`print(my_set)`                  |
| Dictionary     | Collection of key-value pairs               | Yes     | Yes      | No      | Keys must be unique | `my_dict = {'a': 1, 'b': 2, 'c': 3}` | `print(my_dict['a'])`<br>`my_dict['d'] = 4`         |
| String         | Sequence of characters                      | No      | Yes      | Yes     | Yes                | `my_string = 'Hello'`               | `print(my_string[0])`<br>`for char in my_string:`   |
| Bytes          | Immutable sequence of bytes                | No      | Yes      | Yes     | Yes                | `my_bytes = b'hello'`               | `print(my_bytes[0])`<br>`for byte in my_bytes:`     |
| Bytearray      | Mutable sequence of bytes                  | Yes     | Yes      | Yes     | Yes                | `my_bytearray = bytearray(b'hello')`| `my_bytearray[0] = 72`<br>`print(my_bytearray)`    |
| Range          | Immutable sequence of numbers              | No      | Yes      | Yes     | No                 | `my_range = range(5)`               | `print(list(my_range))`<br>`for num in my_range:`   |
| List of Lists  | Nested list where each item is a list      | Yes     | Yes      | Yes     | Yes                | `matrix = [[1, 2], [3, 4]]`         | `print(matrix[0][1])`<br>`for row in matrix:`       |
| Tuple of Tuples| Nested tuple where each item is a tuple    | No      | Yes      | Yes     | Yes                | `coordinates = ((1, 2), (3, 4))`     | `print(coordinates[1][0])`<br>`for point in coordinates:` |
| Dictionary of Dictionaries | Nested dictionaries | Yes     | Yes      | No      | Keys must be unique | `student_info = {'John': {'age': 25, 'major': 'CS'}, 'Alice': {'age': 22, 'major': 'Math'}}` | `print(student_info['John']['age'])`<br>`student_info['Alice']['major'] = 'Physics'` |

This table provides a brief overview of each data structure, including whether it's mutable, iterable, ordered, allows duplicate elements, and examples of declaration and usage. Keep in mind that there are more specialized data structures available in Python, but these are some of the most commonly used ones.