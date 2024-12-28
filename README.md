# Quiz Builder
A quiz builder program that takes a text file containing information as input, and turns it into a json file. This is done using the ```OpenAI API``` to process text information and turn it into relevant questions in a predictable format using the new ```json mode```.



### Requirements
__Python :__
- Python 3.11.5 or newer

__Standard packages :__
- pathlib
- json
- os
- random

__OpenAI toolkit :__

`pip install openai`



## Basic How To
To use this program, start by removing the sample files from ```read_folder``` and ```write_folder``` (```information.txt``` & ```Questionaire_0.txt```),
then update the ```configuration.txt``` file to include your openAI key, add your own input file to ```read_folder```. Finally, run ```Launcher.py```.
You can then run ```Quiz.py``` to go through the quiz.


## Features backlog
- Add a way to count tokens prior to sending - context length issue
- Improve the docs system (measure current_len + next_file_len. If too long, cut the prompts)
- Add all OpenAI configs to config file for full customization
- Change temp.txt to logs.txt, save objects as json for each query, instead of a counter


## Usage
Available for use under MIT license.
