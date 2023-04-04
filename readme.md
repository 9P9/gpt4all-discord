## Simple Discord AI using GPT4ALL

This is a chat bot that uses AI-generated responses using the GPT4ALL data-set.

### How to get the GPT4ALL model! 

Download the `gpt4all-lora-quantized.bin` file from [Direct Link](https://the-eye.eu/public/AI/models/nomic-ai/gpt4all/gpt4all-lora-quantized.bin) or [[Torrent-Magnet]](https://tinyurl.com/gpt4all-lora-quantized).

### Where to Put the Model:

Ensure the model is in the main directory! Along with binary

If you're using a different platform ensure you use the correct binary for your OS from: 
- [GPT4ALL](https://github.com/nomic-ai/gpt4all)
Then Adjust the code in index.js to fit: 

```	
	let GPT = new GPT4('./ai/gpt4all-lora-quantized-win64'); //Windows
	let GPT = new GPT4('./ai/gpt4all-lora-quantized-OSX-m1'); //M1 Mac/OSX
	let GPT = new GPT4('./ai/gpt4all-lora-quantized-OSX-intel'); //Intel Mac/OSX
	let GPT = new GPT4('./ai/gpt4all-lora-quantized-linux-x86'); //Linux
```

### How to Run!
	- npm i 
	- node index.js


Related Repos:
	- [GPT4ALL](https://github.com/nomic-ai/gpt4all)
	- [Unmodified gpt4all Wrapper](https://github.com/realrasengan/gpt4all-wrapper-js)
