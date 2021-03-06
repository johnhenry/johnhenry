### Hi there š

- ā” Fun fact: I'm a programmer!

<!--
**johnhenry/johnhenry** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
-->

<form>

Github Markdown can render:

- [Diagrams via Mermaid](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams#creating-mermaid-diagrams)
  ```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
      D-->E;
      D-->F;
  ```
- [Map Data via GeoJSON and TopoJSON](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams#using-geojson)
<!--   
  ```geojson
  {
    "type": "Polygon",
    "coordinates": [
        [
            [-90,30],
            [-90,35],
            [-90,35],
            [-85,35],
            [-85,30]
        ]
    ]
  }
  ``` -->
  ```topojson
  {
    "type": "Topology",
    "transform": {
      "scale": [0.0005000500050005, 0.00010001000100010001],
      "translate": [100, 0]
    },
    "objects": {
      "example": {
        "type": "GeometryCollection",
        "geometries": [
          {
            "type": "Point",
            "properties": { "prop0": "value0" },
            "coordinates": [4000, 5000]
          },
          {
            "type": "LineString",
            "properties": { "prop0": "value0", "prop1": 0 },
            "arcs": [0]
          },
          {
            "type": "Polygon",
            "properties": { "prop0": "value0", "prop1": { "this": "that" } },
            "arcs": [[1]]
          }
        ]
      }
    },
    "arcs": [
      [
        [4000, 0],
        [1999, 9999],
        [2000, -9999],
        [2000, 9999]
      ],
      [
        [0, 0],
        [0, 9999],
        [2000, 0],
        [0, -9999],
        [-2000, 0]
      ]
    ]
  }
  ```
- [3D Objects via STL](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams#creating-stl-3d-models)
  ```stl
  solid cube_corner
    facet normal 0.0 -1.0 0.0
      outer loop
        vertex 0.0 0.0 0.0
        vertex 1.0 0.0 0.0
        vertex 0.0 0.0 1.0
      endloop
    endfacet
    facet normal 0.0 0.0 -1.0
      outer loop
        vertex 0.0 0.0 0.0
        vertex 0.0 1.0 0.0
        vertex 1.0 0.0 0.0
      endloop
    endfacet
    facet normal -1.0 0.0 0.0
      outer loop
        vertex 0.0 0.0 0.0
        vertex 0.0 0.0 1.0
        vertex 0.0 1.0 0.0
      endloop
    endfacet
    facet normal 0.577 0.577 0.577
      outer loop
        vertex 1.0 0.0 0.0
        vertex 0.0 1.0 0.0
        vertex 0.0 0.0 1.0
      endloop
    endfacet
  endsolid
  ```
