## Vanilla CNN for MNIST Classification 
<h3> Designed to run on Google Colab (change the path otherwise) </h3>

<ul>
    <li>Training set size: 50 000</li>
    <li>Validation and Test set of 5 000 </li>
    <li> 10 epochs training </li>
</ul>
<h2> Network architecture </h2>
<ul>
    <li> Batch size of 4 </li>
    <li>6 convolution operations</li>
    <li> 2 Maxpooling operations</li>
    <li> ReLU activation </li>
    <li> No batch normalization </li>
    <li> Last fully connected layer with SoftMax activation </li>
    <li> Cross entropy loss, no weight decay / no momentum </li>
</ul>