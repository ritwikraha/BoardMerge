# BoardMerge 
BoardMerge is Python Command Line Script that allows you to merge several pdf files containing pcb art that one often uses for toner transfer method onto one single sheet of paper.

I came up with this during college days, when i had to get the PDFs printed on Glossy Sheet. The best quality sheet costs about **20 INR** and its often best to utilise the whole of it. Since, Eagle doesnt offer a way to arrange many prints on a single page. I had to use other photo editing tools which required some effort and a constant fear of *screwing* the dimensions. But this approach had the following issues :

- Printing on a sheet many times causes it to blacken due to the unhealthy state of drum on public printers
- The shop keeper usually charges 2-4 bucks for a single round in the printer and printing many times added to the costs.
- I had to always mark the point for the orientation of the print, else if the print goes the other way again, i can have the next file printed on the previous file , rendering the entire excercise useless. Actually that has happened twice :)

To obviate this i made this script, the syntax is pretty easy. Just copy the script to the folder and then in the terminal type :

`python merge.py file1.pdf file2.pdf .. .. .. ` 

The script is a bit slow, took about 90 secs to merge 18 files. But kind of serves the purpose.

*NOTE:* The only dependency is pyPDF that can be installed using pip :

`sudo pip install pypdf`
