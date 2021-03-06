## Document Image Binarization using a Deep Learning Neural Network

Tensorflow implementation of a U-shape architecture based on U-net architecture. 
The model includes an attention mechanism inspired by CBAM attention mechanism

<p  align="center">
<img align="100"  src="images/attention_diagram.png"  width="500" > 
</p>


#### Examples:


<p float="left">
<img   src="images/112testing.png"  hspace="20" width="200" >  
<img   src="images/mybin_112.png"  hspace="20" width="200">   
<img   src="images/24testing.png"  hspace="20" width="200" >  
<img   src="images/mybin_24.png"  width="200">   
</p>



##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (a) noisy_document_image &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (b) binary_result_for(a) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (c) noisy_document_image &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (d) binary_result_for(c)


### Reference:

https://arxiv.org/pdf/1807.06521.pdf


There is also the ability to use the SAGAN self-attention mechanism or not to use one.

### Reference:

https://arxiv.org/pdf/1805.08318.pdf


### Images References: 

I. Pratikakis, B. Gatos and K. Ntirogiannis, "ICDAR 2011 Document Image Binarization Contest (DIBCO 2011)," 2011 International Conference on Document Analysis and Recognition, Beijing, 2011, pp. 1506-1510, doi: 10.1109/ICDAR.2011.299.

I. Pratikakis, K. Zagoris, X. Karagiannis, L. Tsochatzidis, T. Mondal and I. Marthot-Santaniello, "ICDAR 2019 Competition on Document Image Binarization (DIBCO 2019)," 2019 International Conference on Document Analysis and Recognition (ICDAR), Sydney, Australia, 2019, pp. 1547-1556, doi: 10.1109/ICDAR.2019.00249.

### Requirements 
```
Python (suggested 3.7.1)  
Numpy  
PIL  
ntpath  
os-sys  
OpenCv  
Tensorflow (suggested 2.4.0)  
```


### License

This project is licensed under the MIT License - see the LICENSE file for details

