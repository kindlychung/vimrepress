# DESCRIPTION

Vimrepress is a plugin for managing wordpress blog from Vim.

This is a modified version of [vimscript 3510](http://www.vim.org/scripts/script.php?script_id=3510)

# CHANGE

I changed a few things, which IMHO makes this addon more userful:

* Automatically set filetype of post to markdown, this makes sense because markdown is the format you are using.
* Automatically set wrap
* Added `/usr/local/lib/python2.7/site-packages/` to `sys.path`, so fixed the "python-markdown required" error in Mac OSX 10.9

# REQUIREMENT

- Vim 7.3+ with python 2.6/2.7 support
- Python Environment matched wtih Vim's support
- python-markdown /  python-markdown2 installed
- wordpress 3.0.0 +


# COMMAND EXAMPLES

Some commands list above contain special usage, example below may clearify them for you.


    :BlogList             -  List 30 recent posts.
    :BlogList page        -  List 30 recent pages.
    :BlogList post 100    -  List 100 recent posts.

    :BlogNew post         -  Write an new post.
    :BlogNew page         -  Write an new page.

    :BlogSave             -  Save (defautely published.)
    :BlogSave draft       -  Save as draft.

    :BlogPreview local    -  Preview page/post locally in your browser.
    :BlogPreview publish  -  Same as `:BlogSave publish' with brower opened.

    :BlogOpen 679
    :BlogOpen http://your-first-blog.com/archives/679
    :BlogOpen http://your-second-blog.com/?p=679
    :BlogOpen http://your-third-blog.com/with-your-custom-permalink

# DOCUMENTATION

More detailed about this commands, type :help vimpress while you have vimrepress installed.
