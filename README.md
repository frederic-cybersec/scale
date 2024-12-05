                                      dP
                                      88
           .d8888b. .d8888b. .d8888b. 88 .d8888b.
           Y8ooooo. 88'  ''' 88'  '88 88 88ooood8
                 88 88.  ... 88.  .88 88 88.  ...
           '88888P' '88888P' '88888P8 dP '88888P'


Shell script to display musical scale information and its guitar patterns, with option to show diatonic chords and export the output to pdf.


![scrn1](https://github.com/user-attachments/assets/6162a358-7136-49b2-9e18-433945029360)
## Usage:

        scale [SCALE]       display musical scale information and its guitar patterns
        
        scale help          display this help and exit
        scale list          list all available scales

        scale [SCALE] [OPTION]...
            scale major
            scale major chords
            scale major chords pdf

        scale [ROOTNOTE] [SCALE] [OPTION]...
            scale A major
            scale D minor chords
            scale F# melodic mode 1 pdf
            scale Bb harmonic mode 4 onlychords pdf

    ROOTNOTES:
        A, Ab, A#, B, Bb, C, Cb, C# ...

    SCALES:
        major, minor, mixloydianb9b13, lydian#5 ...
        melodic mode1, natural mode4, harmonic mode6 ...
        ...
        (use 'scale list' to show the complete list)

    OPTIONS:
        chords          show the scale and its diatonic chords
        onlychords      display only the diatonic chords
        pdf             save the output as a PDF

          
## Available scales:

### Basics:
    major                     ==  natural mode1
    minor, natural minor      ==  natural mode6
    melodic, melodic minor    ==  melodic mode1
    harmonic, harmonic minor  ==  harmonic mode1
    major pentatonic
    minor pentatonic


### Natural modes:
    natural mode1   ==  major, ionian
    natural mode2   ==  dorian
    natural mode3   ==  phrygian
    natural mode4   ==  lydian
    natural mode5   ==  mixolydian
    natural mode6   ==  minor, aeolian, natural minor
    natural mode7   ==  locrian


### Harmonic modes:
    harmonic mode1  ==  harmonic minor
    harmonic mode2  ==  locrian#13
    harmonic mode3  ==  ionian#5, augmented major
    harmonic mode4  ==  dorian#11, altered dorian
                        ukranian dorian, romanian minor
    harmonic mode5  ==  phrygian dominant, mixolydian b9b13
    harmonic mode6  ==  lydian#9
    harmonic mode7  ==  altered diminished, locrian b11b7



### Melodic modes:
    melodic mode1   ==  melodic minor, jazz minor
    melodic mode2   ==  dorian b9, phrygian#13
    melodic mode3   ==  lydian augmented, lydian#5
    melodic mode4   ==  lydian dominant, lydian b7, overtone
    melodic mode5   ==  mixolydian b13, hindu
    melodic mode6   ==  aeolian b5, locrian#9, half diminished
    melodic mode7   ==  altered, super locrian
                        locrian b11, diminished wholetone

## Screenshots:


![scrn2](https://github.com/user-attachments/assets/fe6c851c-1ac8-4da7-9048-11c53f632d19)

![scrn3](https://github.com/user-attachments/assets/77246014-e7ba-4753-a32c-dfec94ba578f)


