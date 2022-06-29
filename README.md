# Recommenders Project 2

## Project description

This project is a recomender for hotel reservations which main goal was to train a content based recommender and achieve the best HR@10 result in the final evaluation.
The task contains:

- Package structure
- Readme file
- Input features, data preprocessing
- Recommender 
- Tuning
- Recommender performance
- Written summary
What's funny,  I obtained quit nice score by taking only user_id and item_id.

## How to launch

1.  Install Anaconda with Python 3.8.
2.  Clone the repository
3.  Prepare your conda environment

    1.  Open Anaconda Prompt as administrator.
    2.  Make sure you're in the repository main folder. Run the following command:

            	conda env create --name rs-class-env -f environment.yml>

        You can replace rs-class-env with your own environment name.

4.  In Git Bash open the repository folder and activate just created environment with the following command:

        conda activate rs-class-env

5.  In Git Bash type:

        jupyter notebook
	
## Results are in notebook: Project2_2
This notebook contains the whole recommender, unfortunatelly i had no time to make it better.
Notebook Project2 contains my first thought to prepare the data as images and use CNN's, but it doesnt work well as recommender.