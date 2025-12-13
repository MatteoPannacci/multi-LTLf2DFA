# multi-ltlf2dfa

A fork of `LTLf2DFA` which supports multiple processes and threads using MONA at the same time by using temporary files instead of the `automa.mona` file in the package folder when calling `invoke_mona()`. This package is a replacement for `LTLf2DFA`.


## Install

- Remove `LTLf2DFA` if present:
```
pip uninstall ltlf2dfa
```

- Clone the repository and install it:
```
git clone https://github.com/matteopannacci/multi-LTLf2DFA.git
cd multi-LTLf2DFA
pip install .
```
