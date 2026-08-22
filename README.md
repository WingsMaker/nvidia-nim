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
<pre>	
回應內容：
To calculate the number of days between 1st January 1964 and 1st January 2026:
**Step 1: Count the years**
2026 − 1964 = 62 years
**Step 2: Calculate days for 62 years**
- 62 × 365 = 22,630 days
**Step 3: Add leap days**
Leap years between 1964 and 2026 (inclusive of 1964, exclusive of 2026 since 2026 is not a leap year):
1964, 1968, 1972, 1976, 1980, 1984, 1988, 1992, 1996, 2000, 2004, 2008, 2012, 2016, 2020, 2024
= **16 leap years**
**Step 4: Total**
22,630 + 16 = **22,646 days**
So there are **22,646 days** between 1st January 1964 and 1st January 2026.
</pre>
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

