# Learn German cases

This is a small program which I made for myself in order to finally grasp German cases.

Remember this table from school?

-/- | MASCULINE | FEMININE  | NEUTER  | PLURAL
--- | --- | --- | --- | ---
NOM | der Mann  | die Frau  | das Kind  | die Kinder
ACC | den Mann  |	die Frau  |	das Kind  | die Kinder
DAT | dem Mann  |	der Frau  | dem Kind	| den Kindern
GEN | des Mannes|	der Frau  | des Kindes  |	der Kinder

Instead of learning it by heart, you can:

1. Insert your wordlist.txt with German words you like. The more, the better (example list already included!)
2. Run script with wordlist as an argument
3. Dump all output audio files to your audio playing device of choice, don't forget to turn on shuffling
4. Every file is a text-to-speech Nominativ to Akkusativ/Dativ/Genitiv riddle, with a few second pause for you to think about the answer
5. Use this playlist while doing your chores/commuting to work!

For text-to-speech I used [Michal Fapso's script which fetches audio from Google's engine](http://michalfapso.blogspot.com/2012/01/using-google-text-to-speech.html).

You can modify pause and rest parameters in learn_german_cases if the riddle pacing doesn't suit you.

## Caveats

This is just a proof-of-concept script written in bash, which isn't very well suited for more complex language processing. I will be porting this project to python, but for now:
* No Genitiv support
* No plural words support
