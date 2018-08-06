# StudentsAdmissions
**Udacity - Artificial Intelligence Nanodegree Program**
AI - Students Admissions Project in Keras

# Students Admissions Project using Keras

This project is part of **Udacity´s Artificial Intelligence Nanodegree Program**. Here you will find my personal solution to the challenge. I first explain how you can download it and test it. Next, I have added Udacity´s original instructions for completing the project.

--------------------------------------------------------------------

## Project Requirements
To fully test the project, you might need to install some required packages. Please start by downloading **Anaconda** using the following link: [Download Anaconda](https://www.continuum.io/downloads). Once installed, clone this repository and access the downloaded folder through a **terminal** window. Next, you need to install the required packages:

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/pablomateo/StudentsAdmissions.git
		cd StudentsAdmissions
	```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  
	
	For __Mac/OSX__:
	```
		conda env create -f requirements/pmaienv-mac.yml
		source activate pmaienv
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/pmaienv-windows.yml
		activate pmaienv
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```

	For __Linux__:
	```
		conda env create -f requirements/pmaienv-linux.yml
		source activate pmaienv
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```
	
3. Enjoy!
    
If you want to check my submitted solution, instead run

     (pmaienv)$ jupyter notebook Student_Admissions.ipynb

--------------------------------------------------------------------
--------------------------------------------------------------------
