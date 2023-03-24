Experimentations:

**Normalization testing**
AT&T with and without normalization:
Normalization improves result very slightly

Mean normalization is better than min
Max normalization is better than mean

Multiple images:
Without normalization: All the faces face straight, to preserve the global property. Most of the images look straight, so the reconstruction provides straight faced images
Minimal difference between Lee-Seung and Robust non negative matrix factorization

Min-max normalization: No significant difference. The orientation of image is lost both in Lee-Seung and robust

Further tests will be conducted by min max scalar

**Initialization testing**
‘nndsvdar’: NNDSVD with zeros filled with small random values (generally faster, less accurate alternative to NNDSVDa for when sparsity is not desired)

Better performance because of initialization. Effect of initialization not visible. It maybe just that the algorithm is good.
