# Introduction to Spatial Data

the *Geographic Data problem*

or

**Spacial is Special**

___

## GEO Problem?

![ORLY](img/orly.jpg)

You have to deal with data that has special rules.

Rules based on a reality not told in schools

---

# Earth is not a sphere

![Typical representation of the Earth as sphere](img/sphere.jpg)

___

## Earth is more like a potato


![Image of a free range potato](img/potato.jpg)

___

## Earth has the shape of a potato

Believe me, I know what I'm talking about

![Image of a geoid](img/geoide.jpg)

___


## Geoids are physical

Although its the true shape of the Earth, we can't measure over it.

![No measure is possible](img/nomeasure.jpg)

___

## For measuring we need mathematics

We need an **Ellipsoid**

![Image of an ellipsoid](img/ellipsoid.jpg)

___

## Ellipsoid vs Geoid

On average, they are quite similar

![Ellipsoid compared to geoid](img/ellip_vs_geoid.jpg)

___

## Datum is the name of the game 

The Ellipsoid and a couple more of things is what we call:

### the **DATUM**

(And there are not one but several Datums, understanding this takes several courses of Geodesy, trust me on this)

___

## Earth is not a sphere: Conclusion

*Remember*

> The **GEO** information lays over something *mathematical* that has its own rules.

> **THE DATUM**


---

# Maps are flat

![Image of a flat screen with a map](img/flat_screen.jpg)

___


## Making things flat

But you can't turn **flat** something spherical

(without breaking it)

![Image of a map on an orange skin](img/orange_map.jpg)

___

## Breaking Flat

You have to choose what you want to *break*:

* **Areas**
* **Angles**
* **Distances**

In the best case you can choose two of the three.

(I'm skipping several courses on Cartography with this slide, trust me on this)

___

## Choose your weapon!: The Projection

The cartographers have some tricks for breaking things **mathematically**

[![xkcd on map projections](img/map_projections.jpg)](https://xkcd.com/977/)

___

## Maps are flat: Conclusion

*Remember*

> The **GEO** information uses a *mathematical* trick to make things **flat** orderly.

> **THE PROJECTION**


___

# SRS and CRS

Toghether a *DATUM* and a *PROJECTION* make a **CRS**

The most famous catalog of *CRS* is **EPSG**

* EPSG:4326
* EPSG:3857 or EPSG:900913
* EPSG:4258
* EPSG:25830, EPSG:25831

---

# Geo data types

These one are easy

Because you are more used to it

___

## Raster and Vector data

![Raster data model](img/raster_data.jpg)

![Vector data model](img/vector_data.jpg)

---

# Data model

How many geometry types do you know?

... Point, Line, Surface ...

___

## Well, it's complicated...

OGC Simple Feature Access 

![OGC Simple Feature Specification](img/ogc_sfs.jpg)

---

# lon/lat vs lat/lon

There's a little bit of fuss

In theory it should be lon/lat (x,y)

But we are used to lat/lo

## Always check things ... twice

---

# Recap

* Know your **Datum**
* Know your **Projection**
* Know your **Data Type**
* Know your **Model**

## KNOW YOUR (geo) DATA!!!
