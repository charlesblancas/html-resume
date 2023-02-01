# HTML Resume

## How to run
Open the `resume.html` and `cover-letter.html` files with your browser.

## Editing Notes
Note that the header is copied and pasted between the resume and cover letter, so any changes must be done twice. The fix would be to make the header into a custom element, but that is likely a `wontfix` since the header is not likely to be changed often.

## Printing
To get the proper formatting in PDF format, when printing, make sure that `Fit to page width` or `Scale: default` is selected; otherwise, it might not fit the page correctly.

Make sure that you are choosing the correct paper size.

Uncheck `Print headers and footers` to remove URLs, dates, and other miscellaneous information the browser puts.

## Rationale
I decided to write my resume and cover letter in HTML and CSS. I was previously 
writing it with LibreOffice Writer, a "what you see is what you get" (WYSIWYG) 
editor. However, I was constantly battling against Writer's defaults,
so I decided to go with the plain text with markup route that gives me more control.

## Why not LaTeX?
HTML was not designed for making documents for print, whereas LaTeX was; however,  I still chose to write my resume in it. This is purely for convenience since I use HTML and CSS more than LaTeX. My resume is something that I need to update constantly, so I wanted to minimize the barrier for me to do so. 