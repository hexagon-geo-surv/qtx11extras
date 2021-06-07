# QtX11Extras

**The QtX11Extras module has been deprecated and is no longer part of Qt.**

The functionality of the module has been incorporated into other parts of Qt, or in some cases removed due to being obsolete or better suited as cross platform APIs.

For more details, see [QTBUG-93633](https://bugreports.qt.io/browse/QTBUG-93633) in the Qt issue tracker.

## Porting away from QtX11Extras

To learn more about how to port from QtX11Extras to alternative APIs please visit the [Qt 6 porting guide](https://doc.qt.io/qt-6/portingguide.html).

## Working on Qt 5

To work on patches for the Qt 5 series, check out a local branch of the relevant Qt version, e.g.:

```bash
$ git checkout 5.15
Branch '5.15' set up to track remote branch '5.15' from 'origin' by rebasing.
Switched to a new branch '5.15'
```

## Going back in time

To inspect the code in the `dev` branch prior to its removal, follow these steps:

```bash
$ git checkout -b my-dev 0e67fb41c
Switched to a new branch 'my-dev'
```
