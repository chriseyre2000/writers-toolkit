# Writers Toolkit

This is a digital publishing starter kit.

This was extracted from the toolchain for my first book Development (https://leanpub.com/development2019)

Currently the setup script is mac only but could easily be ported to windows and linux.

Run `setup.sh` to install the required tools using `brew`

To get started update `make_book.sh` with the name of the file that you want to build.

Update `meta.yml` with your own details.

Write your book in the files named part_xx.md

Run ./make_book.sh to generate the epub, mobi and pdf

./make_book.sh expects a cover image to be in the path `cover/cover.png` you need to replace the sample file with a larger real image.

