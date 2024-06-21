
# Building Footprints Detection (from LiDAR)


A Python programme for the detection, vectorization, and regularization of building footprints from LiDAR data.




![](/img/img1.png)



## Description

The custom Python programme addresses the issue of building footprint detection in LiDAR data using advanced clustering and polygonization techniques. It employs the HDBSCAN algorithm to cluster point clouds into distinct building groups. The alpha-shape method is then used to polygonize these clusters, accurately defining the building boundaries. Subsequent steps include data cleaning to remove non-building objects, polygon simplification using L1 trend filtering to smooth boundaries, and polygon orthogonalization to achieve regular shapes with 90° angles. The programme also includes automated checks and corrections to ensure the accuracy of the final building footprint geometries. The script supports the LAS file format for input and generates outputs in GeoJSON format that contain building footprint geometries.


## License

[Apache License](/LICENSE)

