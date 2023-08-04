# lsp-client

modified sample of how to use LSP after 2023

Only tested `clangd`.

Install clangd, and then modify `./test_clangd.py:52` to set `--compile-commands-dir=/root/ls-interact/cpp-test/build-1/` as your own path.

Then `python ./test_clangd.py`

LSP communicate process:

1. initialize
2. DidOopenTextDocument
3. Query stuff
4. Close
