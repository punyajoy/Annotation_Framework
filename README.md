# A low cost annotation framework 
This repository contains a setup of the framework for annotation based on Docanno. This repository can serve as an effective replacement to giving excel sheets to the annotators. 

### Setting up instruction :hammer_and_wrench:
1. Our annotation framework is based on this [repository](https://github.com/doccano/doccano)
2. We especially use Heruko as it is low-cost for most of the mid-range datasets (10k-20k)
3. You can directly click the link here to deploy the annotation framework   [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fdoccano%2Fdoccano)
4. After you click, you have to follow some instructions.

### Creating an annotation project for each of the annotators. :man_technologist:
1. First you have to create a annotation account for each of the annotators. 
2. Go to  https://xxx.herokuapp.com/admin/auth/user/  (Replace xxx with your apps name in Heroku). In the left-top there is a option **Add user**. Click on it and add the user details. Optionally, you can also specify a *Group* to set same permissions for each of the annotators.
3. Next you also have to create seperate projects for each of the annotators here https://xxx.herokuapp.com/ (Project name can be "Annotation_Task_y" y being the name of the annotator and  Annotation_Task being the name of project. With each of the project you also write the annotation guidelines.
4. Finally you can add each of the annotators to their project in this url https://xxx.herokuapp.com/admin/api/project/ by adding the annotator to their projects

:green_circle: :green_circle: **Setup complete** :green_circle: :green_circle:
