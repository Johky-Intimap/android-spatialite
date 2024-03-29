# Change Notes

## Release 1.1.0

2019-07-27

### Important / Breaking Changes

- Support for tolerance/precision=0 added, -1 is the new value
  for automatic computation of minimal tolerance.

- The getEdgeWithinBox2D backend callback needs to support a NULL
  value as BBOX pointer (to return all edges)

### New Features

- Function `rtt_AddLineNoFace`, to add lines w/out determining new
 faces (WARNING: leaves topology in an invalid state)

- Function `rtt_Polygonize`, to determine all faces generated by
  existing edges.

- Function `rtt_tpsnap`, to snap linear components of a geometry
  to edges of a topology.

## Release 1.0.0

2016-05-19

  Initial release