# zen-alarm
An alarm clock that gradually increases in volume to wake you up gently.



# Installation

Run `pip install -r requirements.txt`

In addition to the `python-vlc` library, you need to have [VLC](https://www.videolan.org/vlc/#download) installed separately.

# Usage

Time can be in either 12:00 or 24:00 format. 

##### Examples

`python alarm.py 8:00 "/mnt/HDD/Music/The Beatles"`

`python alarm.py 8:00am "/mnt/HDD/Music/The Beatles" "/mnt/HDD/Music/ACDC" "/mnt/HDD/Music/Avicii"`

`python alarm.py 15:00 "/mnt/HDD/Music/The Beatles" --start-volume 0 --end-volume 100`

`python alarm.py 3:00pm "/mnt/HDD/Music/The Beatles" --start-volume 50 --end-volume 100 --duration 120 --shuffle`

