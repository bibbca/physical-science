# physical-science
A Physical Science textbook for 9th grade science (Introduction to Physics, Chemistry, and Earth Science).

This textbook is motivated by the SDA NAD Science Standards and is licensed under the CC BY-NC-SA 4.0.


# How to Contribute

Teachers and students are welcome to help improve this book! If you spot a typo,
an error, or something that could be explained more clearly, click
**Report an issue** on any page of the book (or open an issue in this repository)
and describe what you found. If you're comfortable with GitHub, you can also
click **Edit this page** to suggest a change directly: GitHub will help you make
a copy of the book, edit the page, and submit a pull request for review. New
sections, practice problems, and images are welcome too; please open an issue
first so we can discuss where they fit. By contributing, you agree that your
contributions will be shared under the book's
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## Building the Book Locally

You can preview the book on your own computer before submitting changes.

1. Install [Quarto](https://quarto.org/docs/get-started/). To build the PDF
   version too, also run `quarto install tinytex`.
2. Clone this repository and open a terminal in its folder:

   ```bash
   git clone https://github.com/bibbca/physical-science.git
   cd physical-science
   ```
3. Start a live preview:

   ```bash
   quarto preview
   ```

   The book opens in your browser and refreshes each time you save a file.
4. To build the complete book (website and PDF), run:

   ```bash
   quarto render
   ```

   The output appears in the `_book/` folder.

Please don't commit the `_book/` or `.quarto/` folders. The website is built
and published automatically when changes are merged into `main`.
