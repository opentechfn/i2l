When we call a human Intellignet what we mean is that person is lerned and has skills in specific area which is more than common sense.
Common sense is what we learn staring growing from a kid to adult what we learn around. All this we learn through our senses.
Like touch through hands, see through eyes, smell through nose, through memory etc. All this sensory preception leads to our brain interpreting it.
As a result it drives us to respond accordingly. Like if we see fire we try keep a distance from it so as not burn oneself.
Thus commonsense to inturion and hence to intelligence is a hunman nature resulting from the brain having a neural network.
However if we train a machine to behave similar to human being, we call it machine learning. HOw does one train machine. 

We traing a comute machine,  using set of test data and enable to provide a resulty based on some 
processing which is like an algoiriith or a simple model like linear equation. Thus set of inputs one or more when provided to it,
results in an output called inference. The model here can be a simple 2 or 3 or n dimension arbitary function. Mathematically y = f(x).
Thus if x is a real input and if its a line we might represent a line as y = (m*x) + c. In two dimension x  & y are co-ordinates and if slope m=1 and c=1,
we get Y= (1*1) + 1 =2. Thus our inference for one sample input 1 gives inference or result as 2 assuming the offert c=1. Depending on different
m values the  line can be converted to any curve. Important thing to note is when x and m change we will get a range of y values.

To represent real life examle say price of house y is proportional to area of house. If x say is 500 square feet house and m is the price 
per square feet say Rs 7500 (or $100) then y = 7500 x 500 + c. Assume c is commisision and is always 4 %. Then price of 500 sq ft house
will be 1.04 * 375000  = 3,75,000 +  15,000 = 3,90,000 or 3 lac 90 thousand Rs. Will 500 squarefeet house in Mumbai and Pune will be same? Not likely.
What it means is a city or location may have diffenet benifits besides just footage. Thus more than one input paramenter my result in differnet price.
Assume we have sample data in Mubai Thane and have 1000's of samples ranging from 500-1000 sq ft in a given area. 
Now if we want to find similat 500-100 sqaure foot area in vicinityof these houses we should be able to infer a proce that is close to real one.
Thgus we need test data smaples, a model and to infer an estimate for a nearby house in similar area ranges. Thus we can make a mchine learning
model for a house price calculator that can predit resoanblay well for aother 200 houses. What it means is because machine was able to lrearn based on
1000 relevant smples, it could predict for another 200 similar range house prices.This is called supervised learning. 

We could have not seperated the sample data and data and let it leran on its own dynamically be feeling through different smaples and start predicting.
This may then be called unsuservised learnig.Alternately one could use Bomay data for Pune and facor it down and that can be termed as trnasfer learning.

Our goal here is to understand , what is the model that provides a prediction and how by setting a feebdback loop between inference anbd acual resulats
in minimizing errors. Building model is coding or writing alogoriem. Rest is all data inpouts, oputputs or don't care.

The buiding of models can being using probability, theory, statistcis and other observations and forulating a mthematical and/or logical formulas.

The coding can be using all forms of Math & Stat libraries or specialized matrix (Octave or Matlab)  or tensor processing language libraries in
R / SAS, Python (PyTorch) libraries. refer - https://en.wikibooks.org/wiki/MATLAB_Programming/Differences_between_Octave_and_MATLAB 

Note these standard algoritms will be available in plenty, but to use what for which domain and are solution is key to machine learning.
Students here are expected to know minimum basics of Supervised and Unspuervised learning and able to run few models to show you understand
the concpets clearly. Hands on could be just try run some number or logic and help tem members to grasp and use ML as a tool with Jupyter Terminal.

Jupyter Notebook is a web-based interactive computational environment for creating Jupyter notebook documents
and is largely used for data analysis, data visualization and further interactive, exploratory computing. 
Jupyter Labs is a cloud based offering and supports Jupyter Notebook in the cloud.
Refer - https://jupyterlab.readthedocs.io/en/stable/user/terminal.html

Also watch - https://www.youtube.com/watch?v=EtZcWNkW9Qs&list=PL_b_MRp1BnEj4UuHv1jAGeO1a0VTRXsAk

Objective of this module is to take smaple codes of models and run and test them on Jupyter termimnal. Later apply the same models in production.
The production codes can be simple simulations or actual embeded deployments using various kits available like Rasberry pi, Adriano etc.
For more on a sample use refer to 


