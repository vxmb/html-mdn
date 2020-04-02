https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks
Use clear link wording
It's easy to throw links up on your page. That's not enough. We need to make our links accessible to all readers, regardless of their current context and which tools they prefer. For example:

Screenreader users like jumping around from link to link on the page, and reading links out of context.
Search engines use link text to index target files, so it is a good idea to include keywords in your link text to effectively describe what is being linked to.
Visual readers skim over the page rather than reading every word, and their eyes will be drawn to page features that stand out, like links. They will find descriptive link text useful.
Let's look at a specific example:

Good link text: Download Firefox

<p><a href="https://firefox.com/">
  Download Firefox
</a></p>
Bad link text: Click here to download Firefox

<p><a href="https://firefox.com/">
  Click here
</a>
to download Firefox</p>
Other tips:

Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a screen reader reads them out letter by letter.
Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users will also know there's a link, because links are generally styled in a different colour and underlined (this convention generally shouldn't be broken, as users are so used to it.)
Keep your link label as short as possible — long links especially annoy screen reader users, who have to hear the whole thing read out.
Minimize instances where multiple copies of the same text are linked to different places. This can cause problems for screenreader users, who will often bring up a list of the links out of context — several links all labelled "click here", "click here", "click here" would be confusing.