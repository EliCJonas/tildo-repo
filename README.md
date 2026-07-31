# <h1 align="center">tildo-repo</h1>

<p align="center">
  A repository of tildo-friendly packages.
</p>

<p align="center">
  ⚠️ <b>Work in progress!</b>
</p>

---

## How to Contribute

Before contributing, PLEASE ensure the package works with tildo.

To add a package, follow these steps:

1. Make a fork of the repo
2. Modify the pkgs/pkgs.list file and add your package name
3. Add an ikeg file with the naming scheme: [name_of_package].ikeg
4. Create a pull request

An ikeg file is formatted like this:
```json
{
  "name": "name",
  "version": "version",
  "author": "author",
  "description": "description",
  "download-url": "url to the keg package"
}
```



