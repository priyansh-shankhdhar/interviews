# interviews

In this project we have to diffrentiate the applicants in the jobs.csv file with respect to their inputs, So that either they are the one who needs to be given an interview or not.

To do so we have at first, cleaned the data using stattistical, mathematical and general approaches the in order to diffrentiate the we have used KMEANS Algorithim.

Now to use this:
  1) dowload the the_file.py
  2) include it in your file
  3) then we have to write 3 lines of code:
  
      >>>import the_file.py
      
      >>>d=interview() #instantiate the interview class
      
      >>>d.run() #this might take a few moment maybe a minute or two
      
      >>>d.pred(dataset) # in this dataset is the the dataset for which you want to predict , this return a dataset of people to give interview.
