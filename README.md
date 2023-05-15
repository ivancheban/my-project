# MkDocs Material with versioning

This is MkDocs Material with versioning using mike.

# How to use versioning

To publish a new version:

1. Run this command to delete all previous versions of documentation:

    ```sh
    mike delete --all
    ```

1. In the project folder, run this command:

    ```sh
    mike deploy --push --update-aliases 0.1 latest
    ```

    Use your version instead of `0.1`.

1. Run this command:

    ```sh
    mike set-default --push latest
    ```

1. When published, clear the cache in your browser to see the new version in the dropdown.
