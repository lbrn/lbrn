I've build a custom theme for geeklog that is based around Bootstrap and the Denim theme from geeklog 2.0. The test working website and theme can be found on test.lbrn.lsu.edu and is running Geeklog 2.0 RC1. 

Some things to note..

* The big action box changes from a welcome message to a scrolling gallery of images when users are logged in. The welcome message is only visible to Admins and anonymous users. Admins will see both, regular users will just see the gallery.
* I've gone ahead and created a brand new geeklog site for test. It does not have the old geeklog database, it's completely brand new. I'm working to see if there's a way to only import certain tables from another geeklog database, which would allow us to keep all the users and any old posts that we want to keep.
* Alternatively, we may be able to use the old database, but heavily modify the existing blocks and content to move on with the new website. We'll have to see.
* The 'configuration' link in the admin block doesn't work. I'm working on a fix. All other admin functions should be fine.
* I'm working to add the acknowledgements to the new theme. There's two options for this: either have it in the header like we did before, or have it in a nice-looking box near the footer of the page.
* Since this is a completely new installation, none of the old pages exist on this site. However, it's very easy to copy over old content, and I've already copied over the "about" section of the website.

## Todo List
*(List any issues or features that you would like to add to the new website)*

* Add acknowledgments to theme
* Change "BBC Core" to "BB Core" (haha)
* Implement search
* LBRN link in navbar should be smaller font (?) and point to homepage
* Implement utf-8
* Change default font on block/page editing to monospace (Monaco)
* Replace placeholder content in gallery with images
