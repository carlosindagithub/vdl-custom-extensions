# IDEAS
Ideas for new extensions, adaptations to the system, etc..

### Entity Proxy
Tag that would be used to proxy entity data.

```
<vdlx-entity-proxy entity="IntArray" values="=[1,2,5,6]">  
```

Which would pass for an `array(integer) of integer`. In this case indices would be autogenerated from the natural indices of the unerlying array.

Variations would be needed to supply different types of entity and indices.

```
<vdl-entity-proxy set="IntSet" values="=[1,2,3]">

<vdl-entity-proxy scalar="IntScalar" value="=99">
```

Usage would then be as normal for other VDL tags. 

Values would be dynamic and changes would trigger normal updates to the VDL view.

### Custom Extensions
Code improvements to how custom extensions are defined.

Simpler syntax.

Auto-generating dynamic and static attributes to reduce boiler plate. 

### InsightArray
Helper functions to make working with InsightArray much easier.

### Graph network visualization
Adds new chart type to visualize graph networks (e.g. https://en.wikipedia.org/wiki/Graph_drawing)
