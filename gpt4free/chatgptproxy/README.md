# Example: `chatgptproxy`

To use this model is very simple, first you need to import it:

```python
from gpt4free import chatgptproxy

while True:
    prompt = input("Your prompt: ")
    print(chatgptproxy.Completion().create(prompt=prompt))
```