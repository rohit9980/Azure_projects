1. Created the ADF
   a. created the link service for source and target
   b. copied data from HTTP to Gen2 lake storage

2. after loading the file to raw layer mounted the location to the databricks
   a. created the app
   b. stored the app id, tenent id, secret key
   c. used the mount configuration in databricks
   d. created the role in gen2 lake for the created app(contributor role)
3. read the all file from the gen2 to using the mounted location
4. did transformation and write the tables to the target in gen2 location
