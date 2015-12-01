Writing conventions in the manuscript folder

# Current state of the book

- content is mostly there (unless a file is almost empty), but a lot is still not publish nor publish-able yet
- content has to be totally reviewed and edited for better sentences
- every todo and work in progress has to be done
- most pictures need cleaning or plain re-doing

# Published content

The magic file *book.txt* decides what goes into the published book. Only what's inside is actually published. The magic file *sample.txt* works the same way for the sample version of the book.

# Work in progress

Files in progress, not to be published as-is, have their name starting with '_', which is handy to have them sorted first in each folder

# Images management

- Because Leanpub expects every image to be in the single images/ folder, whereas Markdowm editors use regular relative links, I stored all images in a local images/ folder within each folder in the manuscript. Then I used a one line command line (update_images.command) to copy them all flat into the one official folder for Leanpub. It's far from perfect, but it works.

- Images that are not in images/ folders are images to use later

# TODO

Files with TODO in the same mean these files are todo list in some aspect:

- courtesy_TODO is all about asking permission to other authors to publish stuff they own
- releasenotes_TODO is all about informing readers of the new content
- humor_TODO is about including the WTF questions where appropriate to entertain a bit the reader; they should come with a funny drawing of a stupid boss, business analyst, developer or tester (à la troll face but novel)

Files with lines starting with %% TODO also need some action

# Interviews and contributions

Pierre Irmann (RFQHub -> various documentation approaches, literate-programming style)
Jeremie Chassaing (AvailPro -> BDD with Event Sourcing)
Gilles Philippart (SGCIB/FCC -> Declarative Puppet)
Romeu Moura (Arolla -> Mob-Programming, Literate Programming?)
Arnauld Loyer (Arolla -> BDD to living documentation)
