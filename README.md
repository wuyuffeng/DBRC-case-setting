<div align="center">
  <img src = "title.png"/>
</div>  

# Overview  
### This project is a instruction for the parameters of the case studies in our paper  _**"A Behavior-Based and Fast Convergence Energy Sharing Mechanism for Prosumers Community"**_.  
> _**two_prosumer.npy**_:The parameters of the case studies on communities with 2 prosumers.  
> _**ten_prosumer.npy**_:The parameters of the case studies on communities with 10 prosumers.  
> _**fifty_prosumer.npy**_:The parameters of the case studies on communities with 50 prosumers.  
> _**hundred_prosumer.npy**_:The parameters of the case studies on communities with 100 prosumers.
# Requirements
>Python 3  
>Numpy  
# Opening method
### Take _**two_prosumer.npy**_ as an example, run the following code in Python to open the file.  
```Python
import numpy as np
dict_ = np.load('two_prosumer.npy',allow_pickle = True).item()
```
# Parameters Description
### Our data is structured in the form of a dictionary, where the meaning of different key is explained as follows:  

>_**'A11'**_ :  
>_**'A12'**_ :  
>_**'A21'**_ :  
>_**'A22'**_ :  
>_**'b'**_ :  
>_**'B21'**_ :  
>_**'c'**_ :  
>_**'d1'**_ :  
>_**'d2'**_ :  
>_**''G**_ :  
>_**'m1'**_ :   
>_**'m21'**_ :  
>_**'m22'**_ :  
>_**'n1'**_ :  
>_**'n1'**_ :  
