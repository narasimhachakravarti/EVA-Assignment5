# EVA-Assignment5
1. File 1:
    1. Target : Get the skeleton right and try to decrease the params we get
    2. Result:
        1. Parameter:251K
        2. Best training Accuracy : 99.83
        3. Best testing Accuracy : 99.00
    3. Analysis:
        1. Quite a heavy model
        2. we do have a overfitting model we need to find out the solution for that
        
        
2. File 2:
    1. Target:  Reduce the model size bring the parameters down and try to reduce overfitting by adding Normalization
    2. Result
        1. Parameter : 10.5k
        2. Best training Accuracy : 99.9
        3. Best testing Accuracy: 99.39
    3. Analysis:
        1. we reduce the parameters but still we are seeing some overfitting
        
        
3. File 3:
    1. Target: Time to add Normalisation and Regularisation
    2. Result
        1. Parameter:10.9k
        2. Train:99.39
        3. Test:99.30
    3. Analysis
        1. We know have a lite model but can be pushed further
        2. we will use gap to get rid of big size kernel
        
        
4. File 4: 
    1. Target: Getting rid of big size kernel and Using of GAP may reduce the capacity of the model - so increase the weight of the mode
    2. Result:
        1. Parameter:11.9k
        2. Train:99.30
        3. Test:99.00
    3. Analysis:
        1. We can analyse that size 5 kernel is where we can start seeing patterns
        2. Model is still overfitting , may be we are thinking apun hi Bhagwan hai :P and I also need params less than 10k to pass the assignment
        
        
5. File 5: Increase modal capacity, by see the data we see we need little transformation of slight rotation
    1. Result:
        1. Parameter:8,346
        2. Train:99.14
        3. Test:99.41 (7th EPOCH)
