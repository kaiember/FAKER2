# hi
## basic syntax
```python
from faker import Faker
import os
fake = Faker()
os.system('clear')
for y in range(5):
    print(f" Name: {fake.name()}")
    print(f" Email: {fake.email()}")
    print(f" phone number: {fake.phone_number()}")
    print(f" address: {fake.address()}")
    print(f" text: {fake.text()}")
    print(f" ="*30)

```