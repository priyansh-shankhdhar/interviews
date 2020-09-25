# interviews

In this project we have to diffrentiate the applicants in the jobs.csv file with respect to their inputs, So that either they are the one who needs to be given an interview or not.

To do so we have at first, cleaned the data using stattistical, mathematical and general approaches the in order to diffrentiate the we have used KMEANS Algorithim.

Now to use this:
  1) dowload the hope_this_works.ipynb
  2) include it in your file and add rest all the files in a directory 
  3) then we have to write 3 lines of code:
      
      >>>d=interview() #instantiate the interview class
      
      >>>d.run() #this might take a few moment maybe a minute or two
      
      >>>d.pred(dataset) # in this dataset is the the dataset for which you want to predict , this return a dataset of people to give interview.
more information is inside hope_this_works.ipynb
