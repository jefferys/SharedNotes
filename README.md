# SharedNotes

Public notes based on private source documents.

The "private" source documents are reference under `ExtRepo/` as
`NoShareSourceDoc`. This is a soft link to an external repository. It will be
broken on windows and on Linux or Mac when the referenced repo is not also
available. The referenced repo must be cloned separately into the same
directory as this repo was; as it is private, it may not be available. This
repo should work without it, although the entire purpose is to show how
external repositories can be linked :)

To use:

```
cd <base-dir>
git clone https://github.com/jefferys/SharedNotes
git clone https://github.com/jefferys/NoShareSourceDoc.git
```
