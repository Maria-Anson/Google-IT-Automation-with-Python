# Reading and Writing Files Cheat-Sheet
> 
> * * *
> 
> Check out the following link for more information:
> 
> *   [https://docs.python.org/3/library/functions.html#open](https://docs.python.org/3/library/functions.html#open)
>
> -- https://www.coursera.org/learn/python-operating-system/supplement/INLPJ/reading-and-writing-files-cheat-sheet#main

> `open`(_file_, _mode='r'_, _buffering=-1_, _encoding=None_, _errors=None_, _newline=None_, _closefd=True_, _opener=None_)[¶](https://docs.python.org/3/library/functions.html#open "Permalink to this definition")
> 
> Open _file_ and return a corresponding [file object](https://docs.python.org/3/glossary.html#term-file-object). If the file cannot be opened, an [`OSError`](https://docs.python.org/3/library/exceptions.html#OSError "OSError") is raised.
> 
> _file_ is a [path-like object](https://docs.python.org/3/glossary.html#term-path-like-object) giving the pathname (absolute or relative to the current working directory) of the file to be opened or an integer file descriptor of the file to be wrapped. (If a file descriptor is given, it is closed when the returned I/O object is closed, unless _closefd_ is set to `False`.)
> 
> _mode_ is an optional string that specifies the mode in which the file is opened. It defaults to `'r'` which means open for reading in text mode. Other common values are `'w'` for writing (truncating the file if it already exists), `'x'` for exclusive creation and `'a'` for appending (which on _some_ Unix systems, means that _all_ writes append to the end of the file regardless of the current seek position). In text mode, if _encoding_ is not specified the encoding used is platform dependent: `locale.getpreferredencoding(False)` is called to get the current locale encoding. (For reading and writing raw bytes use binary mode and leave _encoding_ unspecified.) The available modes are:
> 
> Character
> 
> Meaning
> 
> `'r'`
> 
> open for reading (default)
> 
> `'w'`
> 
> open for writing, truncating the file first
> 
> `'x'`
> 
> open for exclusive creation, failing if the file already exists
> 
> `'a'`
> 
> open for writing, appending to the end of the file if it exists
> 
> `'b'`
> 
> binary mode
> 
> `'t'`
> 
> text mode (default)
> 
> `'+'`
> 
> open for updating (reading and writing)
> 
> The default mode is `'r'` (open for reading text, synonym of `'rt'`). Modes `'w+'` and `'w+b'` open and truncate the file. Modes `'r+'` and `'r+b'` open the file with no truncation.
> 
> As mentioned in the [Overview](https://docs.python.org/3/library/io.html#io-overview), Python distinguishes between binary and text I/O. Files opened in binary mode (including `'b'` in the _mode_ argument) return contents as [`bytes`](https://docs.python.org/3/library/stdtypes.html#bytes "bytes") objects without any decoding. In text mode (the default, or when `'t'` is included in the _mode_ argument), the contents of the file are returned as [`str`](https://docs.python.org/3/library/stdtypes.html#str "str"), the bytes having been first decoded using a platform-dependent encoding or using the specified _encoding_ if given.
> 
> There is an additional mode character permitted, `'U'`, which no longer has any effect, and is considered deprecated. It previously enabled [universal newlines](https://docs.python.org/3/glossary.html#term-universal-newlines) in text mode, which became the default behaviour in Python 3.0\. Refer to the documentation of the [newline](https://docs.python.org/3/library/functions.html#open-newline-parameter) parameter for further details.
>
> -- https://docs.python.org/3/library/functions.html#open
