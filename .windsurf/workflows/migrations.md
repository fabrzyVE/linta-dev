# Task: Migrations

please examine the current init.csv files within my /migrations directory. Your job is to create a whole new file whenever making changes to the csv. 

## Step 1 : Service Locations

With service locations the only change is to go into the column "hs_path" and change every value to a new format. Currently it is "{service}-{location}" the new standard will be "{service}-in-{location}" for every row correlated to that column and everything else stays the same. Please name the file as a timestamp so migration files will go in order. 

