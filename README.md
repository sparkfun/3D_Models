3D Models for SparkFun Products!
----------------

This is a repository of basic geometry and source CAD (if we have them) files for 3D models that appear on our website. Models are stored in real world scale.

*Directory Structure*

Product geometry model structure:
```
products/{product_id}/{rev_if_applicable}/{file_type}/

Ex: 
_products/12099/iges/model.iges_
_products/12099/step/model.step_
_products/12099/stl/model.stl_

If there were any revisions for this product_id:
_products/11113/rev_1.0/stl/model.stl_
_products/11113/rev_1.1/stl/model.stl_
```

Source model structure:
```
products/{product_id}/{rev_if_applicable}/source_{software}/

Ex:
_products/11763/source_solidworks/model.sldprt_

If there were any revisions for this product_id:
_products/11763/rev_1.0/source_solidworks/model.sldprt_
_products/11763/rev_1.1/source_solidworks/model.sldprt_

```

Product display structure:
_We can display multiple stl or obj with mtl textures_
```
products/{product_id}/display/modela.stl

Ex:
products/8601/display/modela.stl
products/8601/display/modelb.obj
products/8601/display/modelb.mtl
products/8601/display/modelb_texture.png
```