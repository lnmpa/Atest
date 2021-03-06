The Markdown Guide is a free and open-source reference guide that explains how to use Markdown, the simple and easy-to-use markup language you can use to format virtually any document.


What’s Markdown?
Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages.

Using Markdown is different than using a WYSIWYG editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.

For instance, to denote a heading, you add a number sign before it (e.g., # Heading One). Or to make a phrase bold, you add two asterisks before and after it (e.g., **this text is bold**). It may take a while to get used to seeing Markdown syntax in your text, especially if you’re accustomed to WYSIWYG applications. The screenshot below shows a Markdown file displayed in the Atom text editor.

Markdown file in the Atom text editor
You can add Markdown formatting elements to a plaintext file using a text editor application. Or you can use one of the many Markdown applications for macOS, Windows, Linux, iOS, and Android operating systems. There are also several web-based applications specifically designed for writing in Markdown.

Depending on the application you use, you may not be able to preview the formatted document in real time. But that’s okay. According to Gruber, Markdown syntax is designed to be readable and unobtrusive, so the text in Markdown files can be read even if it isn’t rendered.

The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.

Kicking the Tires
The best way to get started with Markdown is to use it. That’s easier than ever before thanks to a variety of free tools.

You don’t even need to download anything. There are several online Markdown editors that you can use to try writing in Markdown. Dillinger is one of the best online Markdown editors. Just open the site and start typing in the left pane. A preview of the rendered document appears in the right pane.

Dillinger Markdown editor

You’ll probably want to keep the Dillinger website open as you read through this guide. That way you can try the syntax as you learn about it. After you’ve become familiar with Markdown, you may want to use a Markdown application that can be installed on your desktop computer or mobile device.

How Does it Work?
Dillinger makes writing in Markdown easy because it hides the stuff happening behind the scenes, but it’s worth exploring how the process works in general.

When you write in Markdown, the text is stored in a plaintext file that has an .md or .markdown extension. But then what? How is your Markdown-formatted file converted into HTML or a print-ready document?

The short answer is that you need a Markdown application capable of processing the Markdown file. There are lots of applications available — everything from simple scripts to desktop applications that look like Microsoft Word. Despite their visual differences, all of the applications do the same thing. Like Dillinger, they all convert Markdown-formatted text to HTML so it can be displayed in web browsers.

Markdown applications use something called a Markdown processor (also commonly referred to as a “parser” or an “implementation”) to take the Markdown-formatted text and output it to HTML format. At that point, your document can be viewed in a web browser or combined with a style sheet and printed. You can see a visual representation of this process below.

 Note: The Markdown application and processor are two separate components. For the sake of brevity, I've combined them into one element ("Markdown App") in the figure below.
The Markdown Process
To summarize, this is a four-part process:

Create a Markdown file using a text editor or a dedicated Markdown application. The file should have an .md or .markdown extension.
Open the Markdown file in a Markdown application.
Use the Markdown application to convert the Markdown file to an HTML document.
View the HTML file in a web browser or use the Markdown application to convert it to another file format, like PDF.
From your perspective, the process will vary somewhat depending on the application you use. For example, Dillinger essentially combines steps 1-3 into a single, seamless interface — all you have to do is type in the left pane and the rendered output magically appears in the right pane. But if you use other tools, like a text editor with a static website generator, you’ll find that the process is much more visible.

What’s Markdown Good For?
Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents.

It doesn’t take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere. Most people use Markdown to create content for the web, but Markdown is good for formatting everything from email messages to grocery lists.

Here are some examples of what you can do with Markdown.

Websites
Markdown was designed for the web, so it should come as no surprise that there are plenty of applications specifically designed for creating website content.

If you’re looking for the simplest possible way to create a website with Markdown files, check out blot.im and smallvictori.es. After you sign up for one of these services, they create a Dropbox folder on your computer. Just drag and drop your Markdown files into the folder and — poof! — they’re on your website. It couldn’t be easier.

If you’re familiar with HTML, CSS, and version control, check out Jekyll, a popular static site generator that takes Markdown files and builds an HTML website. One advantage to this approach is that GitHub Pages provides free hosting for Jekyll-generated websites. If Jekyll isn’t your cup of tea, just pick one of the many other static site generators available.

 Note: I used Jekyll to create the Markdown Guide. You can view the source code on GitHub.
If you’d like to use a content management system (CMS) to power your website, take a look at Ghost. It’s a free and open-source blogging platform with a nice Markdown editor. If you’re a WordPress user, you’ll be happy to know there’s Markdown support for websites hosted on WordPress.com. Self-hosted WordPress sites can use the Jetpack plugin.

Documents
Markdown doesn’t have all the bells and whistles of word processors like Microsoft Word, but it’s good enough for creating basic documents like assignments and letters. You can use a Markdown document authoring application to create and export Markdown-formatted documents to PDF or HTML file format. The PDF part is key, because once you have a PDF document, you can do anything with it — print it, email it, or upload it to a website.

Here are some Markdown document authoring applications I recommend:

Mac: iA Writer, Ulysses, Marked, or MacDown
iOS / Android: iA Writer or Ulysses (iOS only)
Windows: MarkdownPad
Web: Dillinger or StackEdit
 Tip: Both iA Writer and Ulysses provide templates for previewing, printing, and exporting Markdown-formatted documents. For example, iA Writer's "Academic – MLA Style" template indents paragraphs and adds double sentence spacing.
Notes
In nearly every way, Markdown is the ideal syntax for taking notes. Sadly, Evernote and OneNote, two of the most popular note applications, don’t currently support Markdown. The good news is that several other note applications do support Markdown:

Simplenote is a free, barebones note-taking application available for every platform.
Bear is an Evernote-like application available for Mac and iOS devices. It doesn’t exclusively use Markdown syntax by default, but you can enable Markdown compatibility mode.
Boostnote bills itself as an “open source note-taking app designed for programmers.”
If you can’t part with Evernote, check out Marxico, a subscription-based Markdown editor for Evernote, or use Markdown Here with the Evernote website.

Books
Looking to self-publish a novel? Try Leanpub, a service that takes your Markdown-formatted files and turns them into an electronic book. Leanpub outputs your book in PDF, EPUB, and MOBI file format. If you’d like to create paperback copies of your book, you can upload the PDF file to another service such as Kindle Direct Publishing or CreateSpace. To learn more about writing and self-publishing a book using Markdown, read this blog post.

Presentations
Believe it or not, you can generate presentations from Markdown-formatted files. Creating presentations in Markdown takes a little getting used to, but once you get the hang of it, it’s a lot faster and easier than using an application like PowerPoint or Keynote. Remark (GitHub project) is a popular browser-based Markdown slideshow tool, as is Cleaver (GitHub project). If you use a Mac and would prefer to use an application, check out Deckset or Marked.

Email
If you send a lot of email and you’re tired of the formatting controls available on most email provider websites, you’ll be happy to learn there’s an easy way to write email messages using Markdown. Markdown Here is a free and open-source browser extension that converts Markdown-formatted text into HTML that’s ready to send.

Documentation
Markdown is a natural fit for technical documentation. Companies like GitHub are increasingly switching to Markdown for their documentation — check out their blog post about how they migrated their Markdown-formatted documentation to Jekyll. If you write documentation for a product or service, take a look at these handy tools:

Read the Docs can generate a documentation website from your open source Markdown files. Just connect your GitHub repository to their service and push — Read the Docs does the rest. They also have a service for commercial entities.
MkDocs is a fast and simple static site generator that’s geared towards building project documentation. Documentation source files are written in Markdown and configured with a single YAML configuration file. MkDocs has several built in themes, including a port of the Read the Docs documentation theme for use with MkDocs. One of the newest themes is MkDocs Material.
Docusaurus is a static site generator designed exclusively for creating documentation websites. It supports translations, search, and versioning.
VuePress is a static site generator powered by Vue and optimized for writing technical documentation.
Jekyll was mentioned earlier in the section on websites, but it’s also a good option for generating a documentation website from Markdown files. If you go this route, be sure to check out the Jekyll documentation theme.
Additional Resources
There are lots of resources you can use to learn Markdown. Here are some other introductory resources:

John Gruber’s Markdown documentation: The original guide written by the creator of Markdown.
Markdown Tutorial: An open source website that allows you to try Markdown in your web browser.
Awesome Markdown: A list of Markdown tools and learning resources.
