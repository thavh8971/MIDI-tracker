*As an new Python learned, most of the code are AI-made, so if anyone have an proper courses of Python for me, please share it, lessons on internet are sometimes lame in Vietnam(not an country self disrespect, but I see that there is nearly no free lessons that properly teaches me.)*

Thanks Admin of ZeroEval to help me in this project by give me another $10 credit

Contains:

The GUI(gui.py)

The core(tracker_core.py)

The engine(engine.py)

The MIDI module(midi.py)

The MIDI import module(midi_import.py)

The MIDI import mode of tracker(run_with_midi_import.py)


Usage:

Blank start:In the same dir of the tracker files, run:

MacOS:python3 gui.py

Windows:py gui.py


Start with an MIDI file:

MacOS:python3 run_with_midi_import.py "your_midi_file.mid"

Windows:py run_with_midi_import.py "your_midi_file.mid"

*The MIDI also in same dir of tracker files


You need:

-PySide6

-mido

-sf2util(note:under construction, sf2util still cannot import properly.)

-fluidsynth(both python and main FluidSynth)


Note:

-Still cannot export tracker files

-Cannot use multithread of CPUs

-Freely modify this and release it again.
