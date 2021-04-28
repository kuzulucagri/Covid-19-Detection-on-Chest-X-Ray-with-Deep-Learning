# Covid-19-Detection-on-Chest-X-Ray-with-Deep-Learning

### In this project I used deep learning algorithm and pythorch.

### Before begin to project I used chest x-ray dataset on kaggle here it's address https://www.kaggle.com/tawsifurrahman/covid19-radiography-database 

### Now let me explain you project.

### Firstly I imported library as I showed in project.

### Secondly I split my dataset which name is training and test.

### Then define my class for images and filepath.

### In image transformations tittle, I use pythorch library for size and normalize my x-ray

### After that I defined train and test directories and invoke that functions as you see in project.

### In my opinion visualization is the most important thing to understand what are we doing in project that is why I visualized it.

### That is train set's result

![vis1](https://user-images.githubusercontent.com/70862062/116479491-677a0280-a888-11eb-8827-9873e1f0ac47.PNG)

### That is test set's result

![vis2](https://user-images.githubusercontent.com/70862062/116479563-84163a80-a888-11eb-8e68-71ecc854c610.PNG)


### After on, created the model with resnet18 in pytorch model. Then used Adam optimizer and show predicts.

![vis3](https://user-images.githubusercontent.com/70862062/116479810-eec77600-a888-11eb-860d-afc7e7a162f2.PNG)

### Now that is time to training model, I like that part, in here I trained my datas and define accuracy, loss. My algorithm is working on higher 95 percent of accuracy.

![vis4](https://user-images.githubusercontent.com/70862062/116480143-71e8cc00-a889-11eb-8e39-4e1ad84d11de.PNG)

### Finally I am testing my test file with 95 percent of accuracy.

![vis5](https://user-images.githubusercontent.com/70862062/116480200-95137b80-a889-11eb-9e0f-5c9b00e81877.PNG)
