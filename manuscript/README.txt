Writing conventions in the manuscript folder

# Structure

Part 1 Reconsidering Documentation
Part 2 Living Documentation exemplified by Behavior-Driven Development
Part 3 Knowledge Exploitation & Augmentation
Part 4 Automated Documentation
Part 5 Runtime Documentation
Part 6 Refactoring-Friendly Documentation
Part 7 Stable Documentation
Part 8 No Documentation
Part 9 Beyond Documentation
Part 10 Living Design & Architecture Documentation
Part 11 Efficient Documentation
Part 12 Introducing Living Documentation


# Current state of the book

- content is all there
- content has yet to be reviewed and edited for better sentences
- few pictures need cleaning or plain re-doing

# Published content

The magic file *book.txt* decides what goes into the published book. Only what's inside is actually published. The magic file *sample.txt* works the same way for the sample version of the book.

# Work in progress

Files in progress, not to be published as-is, have their name starting with '_', which is handy to have them sorted first in each folder, except the ones in the _attic, or in the _imported which will not be used anymore.

# Images management

- Because Leanpub expects every image to be in the single images/ folder, whereas Markdowm editors use regular relative links, I stored all images in a local images/ folder within each folder in the manuscript. Then I used a one line command line (update_images.command) to copy them all flat into the one official folder for Leanpub. It's far from perfect, but it works.

- Images that are not in images/ folders are images to use later

# TODO

Files with TODO in the same mean these files are todo list in some aspect:

- courtesy_TODO is all about asking permission to other authors to publish stuff they own
- releasenotes_TODO is all about informing readers of the new content
- humor_TODO is about including the WTF questions where appropriate to entertain a bit the reader; they should come with a funny drawing of a stupid boss, business analyst, developer or tester (à la troll face but novel)

Files with lines starting with %% TODO also need some action

## Writing this book

All the preparatory material and many sections of book have been written on the notepad of my iPhone 5, standing up in the Paris metro while commuting to and from customers. The majority of the actual writing was done on the Atom editor, on top of the excellent Leanpub + Github toolchain.


Many pictures in this book were drawn by Yunshan Xia on 53 Paper with the 53 Pencil on Ipad Mini.
