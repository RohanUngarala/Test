# Instructions to run the project

There are two methods to run this project..

## Method 1: Using Google Colab

[1] Open Google Colab

[2] Run the following code to install and import the gdown
```
!pip install gdown
import gdown
```
[3] Download the project files with the below code.
```
FILE_ID = "1UIXzYG3wRyP4RskORQpWNioUiCnJI9QA"

# Specify the desired output file path and 
OUTPUT_PATH = "/content/"
namegdown.download(f"https://drive.google.com/uc?id={FILE_ID}", OUTPUT_PATH)
```


[4] After running the above code refresh the folder in files section, the project zip folder will be downloaded named `Fake_Job_Prediction.zip`


[5] Now run the below commands..

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; To create a directory 
```
!mkdir /content/Fake_Job_Prediction" 
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Unzip the folder 
```
!unzip /content/Fake_Job_Prediction.zip -d /content/ 
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Create a current directory
``` 
%cd /content/Fake_Job_Prediction
```

[6] Finally, run the below command to start execution.
```
!python main.py
```
 This might take around 25 to 30 minutes to execute and will display the output.



## Method 2: Local Machine 
[1] Download the project files [here.](https://drive.google.com/file/d/1UIXzYG3wRyP4RskORQpWNioUiCnJI9QA/view?usp=sharing)

[2] After downloading, save the file in desired folder and unzip the file (it will be named as **Fake_Job_Prediction**)

[3] Open Command Prompt and run the below commands. Make sure to replace **`<FILE_PATH>`** with your file's path.
```
cd <FILE_PATH>
python main.py
```

[5] These commands might take around 25 to 30 minutes to finish execution. After execution, output is displayed.

## Team Members contribution to the project 

Team Members Details:

1) Kartik Mukkavilli

2) Rohan Naga Venkata Mayukh Ungarala

3) Sai Nikith Danday 

Contribution of each member:

| Tasks | Assignee |
|----------|----------|
| Data Collection   | All   |
| Data Cleaning  | Rohan & Sai Nikith    |
| Data Preprocessing    | Rohan & Sai Nikith   |
| Model Selection    | All    |
| Data Prediction    | All   |
| Model Evaluation   | All    |
| Deployment     | Rohan & Sai Nikith    |
| Presentation/Final Report    | All  |
