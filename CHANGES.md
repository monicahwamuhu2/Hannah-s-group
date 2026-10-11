# What changed in Hannah's website, and why

All the words, pages, photos and colours are still your group's. These changes fix bugs and make the five pages look like one website.

## Bugs fixed

- **Invalid CSS.** `background: aquamari` (a spelling mistake) and `box-shadow: red` (missing sizes) did nothing. Both are fixed.
- **Hard-to-read text.** White text on light pink and blue text on aquamarine were very hard to read. Headings now use a darker green.
- **Missing `<body>` tag** on the Problems page, and an unclosed `<ul>` on the Contact page.
- **Form fields had no labels or names.** Each box now has a label, so screen readers can say what it is for, and a name, so the form sends something.

## Improvements

- **One stylesheet for all pages.** Each page used to have its own `<style>` block with different colours. Now all five pages link to `style.css`, so one change updates the whole site.
- **Your colours, made readable:** green for the header, a soft pink background, and aquamarine for the title banners and card borders.
- **`goal.html` is now `index.html`.** A website's front page must be called `index.html`, so it opens when someone visits the link.
- **"You are here" in the menu:** the page you are on is underlined in yellow, using `aria-current="page"`.
- **Problems split into Causes and Effects**, still using your own words.
- **Works on phones:** the menu wraps, and the cards and photos stack.
- **Thank you page:** sending the form opens `thanks.html`.

## Try this next

- **Alt text:** in `gallery.html`, change each `alt="Healthy food, photo 1"` to describe what is really in that photo. This is how blind visitors "see" your gallery.
- Add one fact about malnutrition in Kenya, and write where you found it.
