
# ChatGPTJailbreakSearch

A workflow called JailBreak that searches for the best current ChatGPT Jailbreaks. The workflow performs the following steps: 1. Accesses https://www.jailbreakchat.com/, filters the list by JB score, and parses the top 10 prompts to Google Sheets. 2. Rates the jailbreakability of these prompts by loading a fresh thread of ChatGPT with each prompt and asking it to identify itself or if it would do anything unethical. 3. Rates each jailbreak and orders them on the Google Sheet based on the rating.
## Initial generation prompt
a workflow named JailBreak that functionally searches for the best current ChatGPT Jailbreaks performs the following steps:   1. First, a component that accesses  https://www.jailbreakchat.com/ and filters the the list by JB score and then parses the top 10 prompts to Google Sheets. 2. A component that then rates the jailbreakability of these prompts, by loading a fresh thread of ChatGPT with each prompt and then asking it to identify itself or if it would do anything unethical.  3. Finally, a component that rates each jailbreak and orders them on the google sheet in the end!

## Authors: 
- yWorkflows
- DragonDreamweaver#8808
        