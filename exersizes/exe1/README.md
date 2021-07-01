This excersize mainly make you familiar with our projects.

# 1. How  to use github

1. Use command:
```bash
git clone https://github.com/celtics1863/PaparCameraSensor
```
You can download all files to PC.

2. download Github Desktop (recommonded)  
This software will help you quickly get familiar with github


3. You can learn other useful techniques by search engine.  
For the beginning, we don't need many other functions of git.

# 2. Log in Colab

## 2.1 log in colab and register with google drive
Open this link: [colab](https://colab.research.google.com/drive/)  

If you have a google account, you can log in colab.

Why we use colab:  
1. Free to use GPU resource
2. Free to own large storage
3. Free to set deeplearning environment
4. Good interactivity with google drive and github


Your can new a Jupyter Notebook.
And  paste following commands to get Notebook linked your google drive:

```bash
from google.colab import drive
drive.mount('/content/drive')
```
Press `ctrl+enter` and run the code.
In this step, Your may open a url and register as the information mentioned.

```
cd /content/drive/MyDrive/
```
You can enter your own drive.

## 2.2 Basic commands with shell
This part we use colab with google drive to complete basic targets.

If there is "!" in the front of the command, it means run this code in shell. You can think of it as directly interacting with google drive.   
Following is the frequent commands to use `shell`.(shell is kind of programming language to interactive with linux , just like `cmd` in windows)

- show the derectories and files
```
!ls
```
- Create a new derectory
```
!mkdir derectory
```
- Enter some derectory
use relative path.
```
cd derectory
```
use absolutely path.
```
cd /content/drive/MyDrive/derectory
```
- Copy files
If there is a file named 'file'(otherwise you can upload a file)
```
!copy file file.bak
```
means copy the file as file.bak

- Delete file
If there is a file named 'file.bak'
```
!rm file.bak
```
means remove 'file.bak'

- Delete directory
If there is a directory named 'directory'
```
!rm -r directory
```
-r means remove recursively

and you can learn other commands from this website 
[linux bash command](https://www.pianshen.com/article/93991779853/)
, but we don't need learn all the commands .We only need to learn how to search it when needed.

## 2.3 Basic python with jupyter notebook

You can try all the python commands in the opened jupyter notebook.

Use jupyter notebook to complete [Tourial](python-tutorial-v4.0.pdf) `Basic of Python` part.
This will take your a lot of time, but you will also get familiar with python after this excersizes.

# 3. Run Mask R-CNN

open mask r-cnn url [mask rcnn](https://github.com/facebookresearch/detectron2)

Open the  Colab Notebook link in the readme file.

And you should run this Colab Notebook and try to understand what the each step does.

After you run all the code, you will find it may be not so hard to use Deep Learning Models.

# 4. Some papers to read
Read the papers and get a big picture of the paper sensor.

