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

>_**'A11'**_ : It refers to the _**E**_ in formula (2c);  
>_**'B1'**_ : It refers to the _**D<sub>i</sub>**_ in formula (2c);  
>_**'A22'**_ : It refers to the _**A<sub>i</sub>**_ in formula (2b);  
>_**'B22'**_ : It refers to the _**B<sub>i</sub>**_ in formula (2b);  
>_**'c'**_ : It refers to the _**Q<sub>i</sub>**_ in formula (2a);  
>_**'d1'**_ : It refers to the _**d<sub>i</sub>**_ in formula (2a);   
>_**'d2'**_ : It refers to the _**c<sub>i</sub>**_ in formula (2a);
