Markdown files are plain text files, which is great for version control.
Furthermore you won't have to care for style formatting, you can concentrate on the content.

Markdown files end with .md
Edit them with e.g. the popular Atom editor.
On Ubuntu you can install it with
sudo add-apt-repository ppa:webupd8team/atom
sudo apt update; sudo apt install atom

When you have a markdown file open in Atom, open the preview with Ctrl + Shift + M

The markup converter 'Pandoc' converts markdown to PDF.
LaTeX must be installed for that.
Install Pandoc with
sudo apt-get install pandoc 

Convert with
pandoc --template=template.latex thesis.md -o thesis.pdf


Advanced
If you like all this, I recommend an Atom plugin:
It scrolls the preview automatically to the your cursor position in the code.
Install it by going to the settings (Ctrl + Comma), then select the install tab at the bottom left, search for 'markdown-scroll-sync' and install it.