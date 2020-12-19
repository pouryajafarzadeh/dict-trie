Trie with Levenshtein for Persian Language (Khayyam).
=========================================
I will try to set the package for **Persian** language. I used the useful `Repository <https://github.com/jfjlaros/dict-trie>`_, and you can see guides of the main package from `Here <https://dict-trie.readthedocs.io/en/latest/usage.html#basic-operations>`_.
Some Persian characters have the same sounds approximately such as 'س' and 'ص'. Therefore, We consider the cost of the substitution of them lower than the pair of characters that are completely different, such as: 'پ' and 'گ'.
In order to use the package, you can use the .whl file in the `Linke <https://drive.google.com/drive/folders/1z81IHTTkZKwlN6aJAILw9vLUva-SbtJL?usp=sharing>`_. Moreover, the two CSV files that are the confusion matrix of the Persian characters and the list of the characters are available. Additionally, some letters in the Persian language are common with Arabic characters like 'ی'‌ (Persian) and 'ي'(Arabic). Consequently, we should both of them as one character.


.. code-block:: python

  from dict_trie_persian import Trie

  trie = Trie(['جعفرزاده','جعفرذاده','کیائی','کیايي'])
  

I name the package Khayyam, to pay tribute to the great scientist and poet of Iran, Hakim Omar Khayyam.