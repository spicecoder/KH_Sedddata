# KH_Seeddata

each directory under mongodata directory corresponds to a collection name ; each such directory has a single .js file corresponding to each document in the collecton.

You can upload data by running this command in the diectory mongodata:
seed -u 'mongodb://127.0.0.1:27017/khseeddb' .  

=>the khseeddb is the data base name where data is uploaded.
