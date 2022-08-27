# Porous 3D Demo
![logo](https://user-images.githubusercontent.com/60841136/187030253-bdb85cf1-e946-4a67-8178-9e2e64f0476d.png)

Python based application to generate porous triply periodical surface (TPS) models based on different chemical compounds.

## How to use?

This is a demo version of Porous 3D which is designed for visualizing, smoothing and thickening the TPS model, as well as for exporting the results into a 3D printable STL-format file.

This program uses .t3g files generated by [ToposPro](https://topospro.com/). Some of .t3g files examples are in this repositry in `/examples`. All of the algrorithms used in this program are described in [[1]](#1).
1. To open file press ![p3d_open_files](https://user-images.githubusercontent.com/60841136/187031105-05d42104-c30b-4b7a-8ada-b5311e1d74f0.png). To delete all exported surfaces press ![p3d_close_all](https://user-images.githubusercontent.com/60841136/187031113-601a70b0-464f-414f-8d9a-1a5a8e7bb784.png). To duplicate surface press ![p3d_duplicate](https://user-images.githubusercontent.com/60841136/187031121-b89967b3-ca6c-42bc-9b5d-9181cb0dd3f7.png). To delete single surface press 
![p3d_delete](https://user-images.githubusercontent.com/60841136/187031128-8469a05a-fd13-498b-aff4-563051dd17fd.png).



https://user-images.githubusercontent.com/60841136/187031183-b3c3e992-9d85-4520-b48f-23beb361cdef.mp4



2. You can translate exported models by pressing ![p3d_translate](https://user-images.githubusercontent.com/60841136/187031206-f5c9bbe7-df37-4ef8-a099-4841b959dff1.png)
. You can press ![p3d_complite_decline](https://user-images.githubusercontent.com/60841136/187031218-dfa5375a-57a1-4725-af50-072d8baa09fc.png) to abort translation or ![p3d_complite_accept](https://user-images.githubusercontent.com/60841136/187031225-f590d5c3-fe1f-42a8-ae9c-ce661dd76aa6.png) to apply it.



https://user-images.githubusercontent.com/60841136/187031291-2cb49ef7-ace5-4f74-b608-7ec0a91c0f33.mp4



## References
<a id="1">[1]</a> 
M. I. Smolkov, O. A. Blatova, A. F. Krutov and V. A. Blatov
Generating triply periodic surfaces from crystal structures: the tiling approach and its application to zeolites. 
Acta Cryst. (2022). A78, 327-336
https://doi.org/10.1107/S2053273322004545
