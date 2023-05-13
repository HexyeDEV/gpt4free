# Example: `chatbase`

```py
from gpt4free import chatbase

chatbase = Model()

while True:
    prompt = input("Your prompt: ")
    print(chatbase.Completion().create(prompt=prompt, model="gpt-4"))
```

Note: Available models are gpt-4 and gpt-3.5-turbo. Conversations are kept by default. You will get 2 answers: one from GPT and one from DAN, this is because for this service to work we need to use the DAN prompt which is already added as a system message.