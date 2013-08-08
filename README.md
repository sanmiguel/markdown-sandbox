h1 markdown-sandbox
================

h2 purpose
-------

A repository to experiment with how various markdown format edge-cases are rendered in github

# H1

## H2

### H3

* Lists Can contain
    * Sub-lists
    * Code samples

        ```http
        POST /api/foo/var HTTP/1.1
        Content-Type: application/x-www-form-urlencoded
        ```

        Continuation of list item can go here.

        You can even add more code samples:
        ```erlang
        foo:bar(Baz).
        ```
    * Code samples with no empty line and at same indent as list item render the same as
    code samples with an empty line indented more.
    ```erlang
    false.
    ```
    * Code sample, no empty line, extra indentation
        ```erlang
        error_logger:info_msg("This should be indented OK~n", []).
        ```
* More list items
