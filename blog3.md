# Why a PDF Costs More Than It Looks Like

An LLM doesn't read a PDF. It reads a PDF's description of itself — fonts, positions, spacing, decoration, a whole costume of formatting — and has to dig the actual words out from underneath.

All that digging costs tokens. Tokens cost money. They also cost context — the room a model has left to actually think, once it's done unpacking your file.

PPTs are worse. A slide isn't text with a shape around it. It's shapes, and text is one of the things that happens to live inside them. The model has to guess what belonged next to what, in what order, before it can even start reading.

Markdown skips the costume. It's just the words, in the order they matter, with nothing to strip away first.

Nobody's measured an exact saving for you here — it depends on the document, how it was built, how much junk is hiding in it. But the direction holds: less to strip out, less wasted, more room left for the part you actually wanted the model to think about.

If you've ever pasted a PDF into a chat window and watched it lose the thread halfway through — that's usually why.
