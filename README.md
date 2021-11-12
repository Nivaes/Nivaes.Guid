# Nivaes Guid

GuidHelper is a set of utilities to convinar several Guid in one. If we agreed several Guid in one, we can know if the origin of several identifiers is common.

``` C#
    var guid1 = Guid.NewGuid();
    var guid2 = Guid.NewGuid();

    var combineGuid1 = GuidHelper.Combine(guid1, guid2);
```

### Actions

![CI](https://github.com/Nivaes/Nivaes.Guid/workflows/CI/badge.svg)

![Build Release](https://github.com/Nivaes/Nivaes.Guid/workflows/Build%20Release/badge.svg)

![Publish Release](https://github.com/Nivaes/Nivaes.Guid/workflows/Publish%20Release/badge.svg)
