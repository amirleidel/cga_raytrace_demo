# A CGA Approach to Raytracing

## _Abstract_
The five dimensional framework of Conformal Geometric Algebra (CGA), described by [1], lends itself as particularly convenient to work with three dimensional euclidean geometry. The geometric primitives, amongst them, lines, planes, and spheres that arise in the conformal representation are of particular interest in computer graphics, where these may be used in the modeling of more complex objects and whole scenes. A key step towards this is the introduction of parameterized objects, made up of CGA primitives. We will show how such descriptions of surfaces can be ray-traced, by analyzing their intersections with lines, representing light rays. The resulting equations are of polynomial type, making their roots easy to compute. Since this form of modeling objects also allows differentiation, we have direct access to the surface normals and tangents at every point. This enables the use of a Blinn-Phong lighting model, in order to shade scenes in natural lighting. In the end, these techniques are demonstrated by implementing them in the rendering of a final image. 

![Final render](render_refl_img(3).png "Final rendering of a scene, using the Blinn-Phong model described before, illustrating the lighting of a sphere by a light source behind the camera. The brighter part of the sphere shows diffuse reflection of light, producing the uniform gray glow. This is also seen in the in Fig. \ref{fig:comps} (top image). Additionally, there is a sharp, specular reflection of the light source visible (Fig. \ref{fig:comps}, center) . After hitting the sphere, the light rays were traced further until they intersect with the floor, creating the intricate reflection of the chequerboard pattern. Depth attenuation is visible as a black fog, making the background disappear. Lastly, the shadow attenuation produces the sphere's shadow on the ground surface. ")

## References

[1] J. Lasenby, A. Lasenby, and R. Wareham, “A covariant approach to geometry using geometric algebra,” Tech. Rep. CUED/F-INFENG/TR-483, 2004.

[2] H. Hadfield and J. Lasenby, “Direct linear interpolation of geometric objects in conformal geometric algebra,” Advances in Applied Clifford Algebras, vol. 29, Aug. 2019. doi: 10.1007/s00006-019-1003-y.

[3] D. Hildenbrand, Foundations of Geometric Algebra Computing. Berlin Heidelberg: Springer Science & Business Media, 2012, isbn: 978-3-642-31794-1.

[4] H. Hadfield, S. Achawal, J. Lasenby, A. Lasenby, and B. Young, “Exploring novel surface representations via an experimental ray-tracer in cga,” Advances in Applied Clifford Algebras, vol. 31, Apr. 2021. doi: 10.1007/s00006-021-01117-8.
