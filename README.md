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
    * Code sample, empty line, same indentation [is taken as belonging to the parent list item]

    ```erlang
    error_logger:info_msg("This indentation belongs to the apparent parent~n", []).
    ```

    * Code sample, empty line, indented

        ```http
        POST /api/foo/var HTTP/1.1
        Content-Type: application/x-www-form-urlencoded
        ```

        Continuation of list item can go here.

        You can even add more code samples:

        ```erlang
        foo:bar(Baz).
        ```

    * Sub-sublists
        * Code sample, empty line, same indentation [is taken as belonging to the parent list item]

        ```erlang
        error_logger:info_msg("This indentation belongs to the apparent parent~n", []).
        ```

        * Code sample, empty line, indented

            ```http
            POST /api/foo/var HTTP/1.1
            Content-Type: application/x-www-form-urlencoded
            ```

            Continuation of list item can go here.

            You can even add more code samples:

            ```erlang
            foo:bar(Baz).
            ```

* More list items
