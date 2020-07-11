# Linear and Binary Search (Optional)
> 
> * * *
> 
> If you're curious about how linear and binary search look in code, here are a couple of implementations in Python:
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;">
> 
> def linear_search(list, key):
> 
>     """If key is in the list returns its position in the list,
> 
>        otherwise returns -1."""
> 
>     for i, item in enumerate(list):
> 
>         if item == key:
> 
>             return i
> 
>     return -1
> 
> Enter to Rename, Shift+Enter to Preview
> 
> .monaco-list.list_id_3:focus .monaco-list-row.focused { background-color: #d6ebff; }
> .monaco-list.list_id_3:focus .monaco-list-row.focused:hover { background-color: #d6ebff; }
> .monaco-list.list_id_3:focus .monaco-list-row.selected { background-color: #0069d1; }
> .monaco-list.list_id_3:focus .monaco-list-row.selected:hover { background-color: #0069d1; }
> .monaco-list.list_id_3:focus .monaco-list-row.selected { color: #ffffff; }
> 
> 				.monaco-drag-image,
> 				.monaco-list.list_id_3:focus .monaco-list-row.selected.focused { background-color: #0074e8; }
> 
> 				.monaco-drag-image,
> 				.monaco-list.list_id_3:focus .monaco-list-row.selected.focused { color: #ffffff; }
> 
> .monaco-list.list_id_3 .monaco-list-row.focused { background-color:  #d6ebff; }
> .monaco-list.list_id_3 .monaco-list-row.focused:hover { background-color:  #d6ebff; }
> .monaco-list.list_id_3 .monaco-list-row.selected { background-color:  #e4e6f1; }
> .monaco-list.list_id_3 .monaco-list-row.selected:hover { background-color:  #e4e6f1; }
> .monaco-list.list_id_3:not(.drop-target) .monaco-list-row:hover:not(.selected):not(.focused) { background-color:  #f0f0f0; }
> 
> 				.monaco-list.list_id_3.drop-target,
> 				.monaco-list.list_id_3 .monaco-list-rows.drop-target,
> 				.monaco-list.list_id_3 .monaco-list-row.drop-target { background-color: #d6ebff !important; color: inherit !important; }
> 
> .monaco-list-type-filter { background-color: #efc1ad }
> .monaco-list-type-filter { border: 1px solid rgba(0, 0, 0, 0); }
> .monaco-list-type-filter.no-matches { border: 1px solid #be1100; }
> .monaco-list-type-filter { box-shadow: 1px 1px 1px #a8a8a8; }
> 
> </pre>
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;">
> 
> 
> def binary_search(list, key):
> 
>     """Returns the position of key in the list if found, -1 otherwise.
> 
>     List must be sorted.
> 
>     """
> 
>     left = 0
> 
>     right = len(list) - 1
> 
>     while left <= right:
> 
>         middle = (left + right) // 2
> 
>         if list[middle] == key:
> 
>             return middle
> 
>         if list[middle] > key:
> 
>             right = middle - 1
> 
>         if list[middle] < key:
> 
>             left = middle + 1
> 
>     return -1
> 
> Enter to Rename, Shift+Enter to Preview
> 
> .monaco-list.list_id_4:focus .monaco-list-row.focused { background-color: #d6ebff; }
> .monaco-list.list_id_4:focus .monaco-list-row.focused:hover { background-color: #d6ebff; }
> .monaco-list.list_id_4:focus .monaco-list-row.selected { background-color: #0069d1; }
> .monaco-list.list_id_4:focus .monaco-list-row.selected:hover { background-color: #0069d1; }
> .monaco-list.list_id_4:focus .monaco-list-row.selected { color: #ffffff; }
> 
> 				.monaco-drag-image,
> 				.monaco-list.list_id_4:focus .monaco-list-row.selected.focused { background-color: #0074e8; }
> 
> 				.monaco-drag-image,
> 				.monaco-list.list_id_4:focus .monaco-list-row.selected.focused { color: #ffffff; }
> 
> .monaco-list.list_id_4 .monaco-list-row.focused { background-color:  #d6ebff; }
> .monaco-list.list_id_4 .monaco-list-row.focused:hover { background-color:  #d6ebff; }
> .monaco-list.list_id_4 .monaco-list-row.selected { background-color:  #e4e6f1; }
> .monaco-list.list_id_4 .monaco-list-row.selected:hover { background-color:  #e4e6f1; }
> .monaco-list.list_id_4:not(.drop-target) .monaco-list-row:hover:not(.selected):not(.focused) { background-color:  #f0f0f0; }
> 
> 				.monaco-list.list_id_4.drop-target,
> 				.monaco-list.list_id_4 .monaco-list-rows.drop-target,
> 				.monaco-list.list_id_4 .monaco-list-row.drop-target { background-color: #d6ebff !important; color: inherit !important; }
> 
> .monaco-list-type-filter { background-color: #efc1ad }
> .monaco-list-type-filter { border: 1px solid rgba(0, 0, 0, 0); }
> .monaco-list-type-filter.no-matches { border: 1px solid #be1100; }
> .monaco-list-type-filter { box-shadow: 1px 1px 1px #a8a8a8; }
> 
> </pre>
> 
> Don't worry if this seems complex! Understanding this code isn’t required for understanding how to use binary search in troubleshooting.
>
> -- https://www.coursera.org/learn/troubleshooting-debugging-techniques/supplement/TCank/linear-and-binary-search-optional#main
