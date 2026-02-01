Yet another color scheme plugin for IntelliJ IDEA.

# A bit  of context

I worked in Eclipse for many years, and when I switched to IntelliJ IDEA, I realized I liked almost everything except... the editor's color scheme. Oh yeah, that was terrible - I'm used to being able to determine a fair amount of context by font color, boldness, and italics, whereas IntelliJ IDEA by default suggests, "Go ahead, hover your mouse over it or go to the declaration file! You'll find out more info there."

So, the decision to get eclipse-like color scheme came immediately after IntelliJ IDEA installation.

I found several plugins in the store, but they were inaccurate, outdated, and often didn't support Kotlin, that wonderful programming language, so similar to Java, that should be colored the same in the editor, but it isn't.

# So

This repository contains the source code of my color scheme. I aimed to replicate what was in Eclipse as simply and as closely as possible, and also extend it to Kotlin, based on the color scheme logic (bold is immutable, italic is static/cannot be instantiated, and so on). I don't claim perfection; the work will likely continue to be refined. I don't know if it's possible to achieve perfection, given that IntelliJ IDEA can't provide full context for some scenarios, such as constants in Kotlin, and I can't make them bold. But those are minor details. Overall, almost everything is ready, usable, and I'm sure you'll like it.

Have fun!
