# 3D Object sample
This is 3D object smaple using Qt.

## Requirement

- Qt 5.15 +
- QtQuick3D 1.15

## Point
This project has two points.

1. Write the following code in main.cpp
```cpp
QGuiApplication app(argc, argv);
QSurfaceFormat::setDefaultFormat(QQuick3D::idealSurfaceFormat());

// qml engine...
```


2. Convert three-dimensional object file to qml
Convert the data of the three-dimensional object file to qml to use as a model in Qml.
The conversion method is described below.

### Convert *.ob to *.qml file.
```sh
./balsam -o . airplane.obj
```

The `balsam` command comes with Qt project.
It is supported types.
- Wavefront (.obj)
- COLLADA (.dae)
- FBX (.fbx)
- Blender (.blend)
- GLTF2 (.gltf, .glb)



