### How to create repo with relative submodule

```
git submodule add ../child-submodule relative-submodule
git commit -m "add relative submodule"
```

This only works if the remote for your repo is `https://github.com/AlanCoding/*`
Adjust as necessary.
