# multi-ltlf2dfa

A fork of `LTLf2DFA` which supports multiple processes and threads using MONA at the same time by using temporary files instead of the ```automa.mona``` file in the package folder when calling ```invoke_mona()```. This package is a replacement for `LTLf2DFA`.