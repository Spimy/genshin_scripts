# Genshin Windsong Lyre Midi Player
![](http://i3.ytimg.com/vi/9XUrdGh86rU/hqdefault.jpg)

As the name suggests, this tools allows you to play any MIDI file in Genshin using the Wingsong Lyre obtained in the 1.4 Windblume Festival event.

## How To Use It
1. Install [Python](https://python.org)
2. Download this repo (or clone it)
3. Extract the files (if downloaded, unneccessary if you cloned it via Command Line)
4. [Download](https://bitmidi.com/) any MIDI file and put it inside the project folder
5. Rename `midi_config.template.json` to `midi_config.json`
6. Open the `midi_config.json` file and find the `file` key and set its value to `<mini_file_name>.mid`
7. Run `pip install` to install all requirements listed in `requirements.txt`
8. Run the `midi.py` file (recommended to run using your command line by typing `python midi.py`)
9. Open Genshin and use the Windsong Lyre equipment
10. Press `TAB + <number>` to start playing the music

Video tutorial by Takagg: https://www.youtube.com/watch?v=9XUrdGh86rU

## Note
There are occasions where the script will error and it's due to the MIDI file. If this happens, either find a new MIDI file of the same song of edit it yourself
using a [MIDI Editor](https://www.midieditor.org/)
