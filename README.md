3D Models for SparkFun Products!
----------------

This is a repository of basic geometry and source CAD (if we have them) files for 3D models that appear on our website. Models are stored in real world scale.

## Directory Structure 

#### Product geometry model structure:
```
products/{product_id}/{rev_if_applicable}/{file_type}/

Ex: 
products/12099/iges/model.iges
products/12099/step/model.step
products/12099/stl/model.stl

If there were any revisions for this product_id:
products/11113/rev_1.0/stl/model.stl
products/11113/rev_1.1/stl/model.stl
```

#### Source model structure:
```
products/{product_id}/{rev_if_applicable}/source_{software}/

Ex:
products/11763/source_solidworks/model.sldprt

If there were any revisions for this product_id:
products/11763/rev_1.0/source_solidworks/model.sldprt
products/11763/rev_1.1/source_solidworks/model.sldprt

```

#### Product display structure:
We can display multiple stl or obj with mtl textures
```
products/{product_id}/display/modela.stl

Ex:
products/8601/display/modela.stl
products/8601/display/modelb.obj
products/8601/display/modelb.mtl
products/8601/display/modelb_texture.png
```