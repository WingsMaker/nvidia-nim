# nvidia-nim
demo use of Nvidia NIM api using google app script<br>
<br>
need to register free account from and to generate api key from https://build.nvidia.com/<br>
<br>
<hr>
##Example google app script<br>
<br>
see <a href='https://raw.githubusercontent.com/WingsMaker/nvidia-nim/refs/heads/main/nvidia-nim.txt'>nvidia-nim.txt</a> for the script<br>
<br>
Test results (execution log inside google app script)<br>
<br>
<img width="907" height="501" alt="image" src="https://github.com/user-attachments/assets/019e11b8-dd56-4db4-96fa-289098c7f153" />
<br>
Where to store the api key<br>
<br>
<img width="539" height="368" alt="image" src="https://github.com/user-attachments/assets/8b263320-3fab-432e-8b0d-0fd929e8061f" />
<br>
<hr>
##Example python script<br>
<br>
see <a href='https://raw.githubusercontent.com/WingsMaker/nvidia-nim/refs/heads/main/nv-nim-demo.py'>nv-nim-demo.py</a><br>
<br>
Test result:<br>
<pre>
{'id': 'chatcmpl-a155c641-3b17-444c-baf3-de5d9154fcc2', 'choices': [{'index': 0, 'message': {'content': '9.8 is larger than 9.11.\n\nTo compare decimals, you can look at the digits after the decimal point:\n- 9.**11**\n- 9.**8**\n\nSince 8 (in the tenths place) is greater than 1 (in the tenths place of 9.11), **9.8 is larger**.\n\nThis is because 9.8 = 9.80, and 9.80 > 9.11.', 'role': 'assistant', 'reasoning_content': None}, 'finish_reason': 'stop', 'logprobs': None}], 'created': 1787376024, 'model': 'minimaxai/minimax-m3', 'service_tier': None, 'system_fingerprint': None, 'object': 'chat.completion', 'usage': {'prompt_tokens': 178, 'completion_tokens': 97, 'total_tokens': 275, 'prompt_tokens_details': {'audio_tokens': None, 'cached_tokens': 128}}}  
</pre>

