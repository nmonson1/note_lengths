# note_lengths
What do LLMs implicitly learn about song rhythms?

I gave GPT4 the lyrics and notes (but not durations) to Rick Astley's "never gonna give you up," and asked it to give me the note durations.

The resulting MIDI file sounds better-than-random, while still not being correct. This is very surprising to me. If it was correct, I would assume the note durations are in the training data somewhere. If it was random, I would assume GPT just didn't know the answer. But this seems like GPT has learned something about music that I wouldn't expect it to infer from the training data.
