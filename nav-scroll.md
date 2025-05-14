Hey coders!

->Today's repo is a tutorial on how navigation works through navigation bar on websites.

->When we visit websites, we  often see there are various options on the like home, contact us, about us, etc. 

->When clicked, they direct us to that location on the web page where content for that particular section is written.

How this works?
-> The anchor (a) tag has an attribute called "href" which stores the link.

-> And every element can have an id which is unique for every element.

-> Thus, the link in href does nothing but to locate the element which has the same id as the link name and boom - it's done!
-> In simple words, href="#faq" looks for id="faq" on the page.

->If it finds it, it scrolls you there — smoothly or instantly depending on your CSS.

->You stay on the same page, no reloading, no fetch, no JS needed.

-> html {
  scroll-behavior: smooth;
}
The above CSS code snippet is used to make the scrolling smooth. Feel free to ignore this if you want instant scrolling.
Add this code in your css file.

I hope you found this helpful.
Looking forward to drop more such practice lessons.
Till then, keep coding and keep growing!

(Aditi)
