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
> 
> Don't worry if this seems complex! Understanding this code isn’t required for understanding how to use binary search in troubleshooting.
>
> -- https://www.coursera.org/learn/troubleshooting-debugging-techniques/supplement/TCank/linear-and-binary-search-optional#main
