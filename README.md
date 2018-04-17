# Initializing-a-Neural-Net
Zero Initialization vs Random Initialization vs He Initialization

<h4>The dataset visualization:</h4>

![datasetr](https://user-images.githubusercontent.com/19201530/38847064-56acdd3a-421d-11e8-84a0-72d315db3614.PNG)


<h4>Zero Initialization:</h4>

![zero](https://user-images.githubusercontent.com/19201530/38847045-349065fa-421d-11e8-8d05-90380736ee9a.PNG)
```html

On the train set:
Accuracy: 0.5
On the test set:
Accuracy: 0.5
The performance is really bad, and the cost does not really decrease, and the algorithm performs no better than random guessing.

```

<h4>Random Initialization:</h4>

![random](https://user-images.githubusercontent.com/19201530/38847046-34c79e30-421d-11e8-91d1-25b858dc16ab.PNG)
```html
On the train set:
Accuracy: 0.83
On the test set:
Accuracy: 0.86
This gives better results. than before. The model is no longer outputting all 0s. 
```

<h4>He initialization:</h4>

![he_initialisation](https://user-images.githubusercontent.com/19201530/38847047-3500bb8e-421d-11e8-8a21-f58cea89da04.PNG)
```html
On the train set:
Accuracy: 0.993333333333
On the test set:
Accuracy: 0.96
The model with He initialization separates the blue and the red dots very well in a small number of iterations.
```



<h3> Conclusion</h3>
 For the same number of iterations and same hyperparameters the comparison is:

3-layer NN with zeros initialization

50% 

fails to break symmetry 
<br>


3-layer NN with large random initialization 

83% 

too large weights 
<br>



3-layer NN with He initialization 

99% 

recommended method 



