# How to get model file

Blender:

Skinning animation with bones and armatures, then export to morph animation format (JSON)
###### Need three.js exporter addon for Blender ######

# How to run 

###### `pub get` #######

###### `pub serve` #######


# Note: change pubspec.yaml to this

```
name: dart_webgl
version: 0.0.1-dev
description: Samples for Dart
homepage:
environment:
  sdk: '>=0.6.17'
dependencies:
  browser: any
  dart_to_js_script_rewriter: ^1.0.1
  vector_math: any
  three:
    git: git@github.com:orklann/three.dart.git
transformers:
- dart_to_js_script_rewriter
```
