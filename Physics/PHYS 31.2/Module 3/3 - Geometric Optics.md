As discussed in [[1 - Reflections and Refractions]], light rays from a source will radiate in all directions, reflect from mirrored surfaces, and bend if they pass from a material of one index to another.

//todo: insert pics :)

### Constructing the Image from a Plane Mirror
Following the light rays to from an image of an object:
//pic

#### Sign Rules
//pic
##### For Object Distance
When the object is on the same side of reflecting or refracting surface as the incoming light, the object distance $s$ is positive, otherwise it is negative.

##### For Image Distance
When the image is on the same side of the reflecting or refracting surface as the outgoing light, the image distance $s'$ is positive, otherwise it is negative.

##### For Radius of Curvature of Spherical Surface
When the center of curvature $C$ is on the same side as the outgoing light, the radius of curvature $R$ is positive, otherwise it is negative.

//pic

Now, consider an object that only has one direction: a slender arrow oriented parallel to the reflecting surface.
//pic

#### Lateral Magnification
$$
m = \frac{y'}{y}
$$
For a plane mirror, the lateral magnification is unity. Also note that the image arrow is pointing in the same direction as the object arrow, i.e. the image is erect. In this case, an image formed by a plane mirror is always erect.

 Now consider a three dimensional object and its virtual image. The image from a plane mirror show a left/right reversal.
//pic

### Reflections from a Spherical Mirror
Consider a spherical mirror with a radius of curvature $R$, where the concave side faces the incident light.
//pict

We have the center of curvature (C) of the surface, i.e. the center of the sphere of which the surface is a part. Meanwhile, our vertex V goes through the center of the mirror surface.

It is possible to find the location of real image $P'$, alongside the optic axis.
#### Paraxial Approximation
//picture
When $\alpha$ is small, the the rays intersect at $P'$, on the vertex, which results in a sharp image. Otherwise, the image is elongated (spherical aberration).

Assume that the distance of $P$ to $V$ is $> R$. We want to find the location of the real image $P'$. Remember the theorem that an exterior angle of a triangle is equal the sum of two opposite interior angles. From this, we can then apply that to triangles $PBC$ and $P'BC$.
$$
\phi = \alpha + \theta \,\,\,\,\,\, \beta = \phi + \theta
$$
$$
\alpha + \beta = 2\phi
$$
Then we let $h$ be the height of point $B$ above the optic axis and $\delta$ be the distance from $V$ to the foot of the vertical line. So we get
$$
\tan{\alpha} = \frac{h}{s-\delta} \,\,\,\,\,\,\, \tan{\beta} = \frac{h}{s'-\delta}
$$
$$
\tan{\phi} = \frac{h}{R-\delta}
$$
For small $\alpha$, then $tan{\alpha} \approx \alpha$ and $\delta \approx 0$. Then
$$
\alpha = \frac{h}{s} \,\,\,\,\,\,\, \beta = \frac{h}{s'}
$$
$$
\phi = \frac{h}{R}
$$

We then get the object-image relationship for a spherical mirror:
$$
\frac{1}{s}+\frac{1}{s'} = \frac{2}{R}
$$
In this approximation, the rays are nearly parallel to the axis (these are called paraxial rays). The concave mirror becomes a converging mirror.

Note that when $R \rightarrow \infty$, then the mirror becomes a plane mirror.

#### Focal point and Focal Length
Consider the incoming rays to be parallel, the object point is very far ($s = \infty$) from the mirror (e.g. a star).

//pic

Then
$$
\frac{1}{\infty} + \frac{1}{s'} = \frac{2}{R} \,\,\,\,\,\,\,\, s'=\frac{R}{2}
$$
$$
$$
All the incoming rays will then converge at the focal point $F$. The focal point $F$ is at half of the mirror's radius of curvature, i.e.
$$
f = \frac{R}{2}
$$
Then
$$
\frac{1}{s} + \frac{1}{s'} = \frac{1}{f}
$$
Now consider an object placed at the focal point $F$, and the reflected rays are parallel to the optic axis. The image will be at infinity.

The focal point of a spherical mirror has the following properties:
1. Any incoming ray parallel to the optic axis is reflected through the focal point.
2. Any incoming ray that passes through the focal point is reflected parallel to the optic axis.
Note that this is only true for paraxial rays.

#### Image of an Extended Object: Spherical Mirror
//pic
Rays are drawn with regard to the object, the optical axis, the focal point, and the center of a curvature to locate the image.

$PVQ$ and $P'VQ'$ are similar triangles, so therefore $\displaystyle \frac{y}{s} = -\frac{y'}{s'}$. Then
$$
\begin{align}
m = \frac{y'}{y} = -\frac{s'}{s} \tag{lateral magnification, spherical mirror}
\end{align}
$$
If $m > 0$, then the image is upright. If $m < 0$, then the image is inverted.