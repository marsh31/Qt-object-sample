# 3D Object sample
This is 3d object smaple using Qt.

## Requirement

- Qt 5.15 +



## Convert *.ob to *.qml file.
This project use QtQuick3D. The library can not use *.obj directly. If you want to use STL files, convert to qml.

```sh
./balsam -o . airplane.obj
```

The `balsam` command comes with Qt project.

