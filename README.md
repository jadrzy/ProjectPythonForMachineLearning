# Handling repo files
## Initial setup in colab
Follow this steps:
- connect colab to your git account
- create an access token for your account on github
- add token to your colab:
  
<p>
  <img src="https://github.com/jadrzy/PythonForMachineLearning/blob/main/images/Token.png" 
       width=400/>
</p>

- clone repository into colab (this line should be executed at the start of every notebook):
```
!git clone https://{token}@github.com/jadrzy/PythonForMachineLearning.git
```

## Opening notebooks from github
As simple as that:
<p>
  <img src="https://github.com/jadrzy/PythonForMachineLearning/blob/main/images/github_hint.png" 
       width=600/>
</p>

## Opening notebooks from colab
Github account connection is mandatory. To open any notebook within this repository (XYZ represents your username):
<p>
  <img src="https://github.com/jadrzy/PythonForMachineLearning/blob/main/images/colab_hint.png" 
       width=600/>
</p>

## Pushing files into github
### First approach
Using basic git commands such as:
```
!git add .
!git commit -m <info>
!git push https://{token}@github.com/jadrzy/PythonForMachineLearning.git <branch>
```
### Second approach
Using colab embedded functions:
<p>
  <img src="https://github.com/jadrzy/PythonForMachineLearning/blob/main/images/push_git_1.png" 
       width=400/>
</p>

<p>
  <img src="https://github.com/jadrzy/PythonForMachineLearning/blob/main/images/push_git_2.png" 
       width=600/>
</p>
