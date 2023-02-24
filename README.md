# Grassmannians for Nearest Neighbor Identification (GraNNI)

Alexander Kolpakov (University of Neuchatel, Switzerland), Michael Werman (HUJI, Israel)

A new algorithm, GraNNI (Grassmannians for Nearest Neighbours Identification) to solve the problem of affine registration is proposed. The algorithm is based on the Grassmannian of $k$-dimensional planes in $\mathbb{R}^n$ and minimizing the Frobenius norm between the two elements of the Grassmannian. The results of the experiments show that the algorithm is more robust to noise and point discrepancy in point clouds than  previous approaches. Our main comparison is with GrassGraph that appears to be state-of-the-art [IEEE Trans. Image Proc., vol. 29, pp. 3374-3387, 2020, doi: 10.1109/TIP.2019.2959722]. 

Files included:

1) GraNNI_tests.ipynb : GraNNI algorithm realized in Python / SageMath, numerical experiments and statistcs for tests with different levels of noise and point discrepancy

2) (filename).csv : point cloud filename = (Teapot | Bunny | Cow)

3) GraNNI_stats_(filename).csv : test stats for GraNNI saved in csv format (see the manuscript for description) for point cloud "filename"

4) GrassGraph_comparison.ipynb : GrassGraph algorithm realized in Python / SageMath, numerical experiments and statistcs for tests with different levels of noise and point discrepancy

5) GrassGraph_stats_(filename).csv : test stats for the "standard" GrassGraph with 3 Laplacian eigenvectors for point cloud "filename"

6) GrassGraph_stats_mod_(filename).csv : test stats for the "modified" GrassGraph with 10 Laplacian eigenvectors for point cloud "filename"

7) GraNNI.pdf : manuscript with the algorithm's description

Using:

Caerbannog point clouds from https://data.nrel.gov/submissions/153 (unoccluded teapot, bunny, cow).

Required:

SageMath (https://www.sagemath.org) installed to run the worksheets.
