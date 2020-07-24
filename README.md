# Snowflake-Snowpipe-REST-API-Python-Anaconda-Spyder
Load data to Snowflake table  using Snowpipe REST API  - Python Program running in Anaconda/Spyder 

See the attached document for detailed screenshots
<a href="https://github.com/hihisuresh/Snowflake-Snowpipe-REST-API-Python-Anaconda-Spyder/blob/master/SnowpipeRESTAPI.docx">SnowpipeRESTAPI.docx</a>


Refer:

https://docs.snowflake.com/en/user-guide/data-load-snowpipe-rest-overview.html

https://docs.snowflake.com/en/user-guide/data-load-snowpipe-rest-load.html#sample-program-for-the-python-sdk

1.	Create PIPE
See  previous posts
https://docs.snowflake.com/en/user-guide/data-load-snowpipe-rest-gs.html
https://github.com/hihisuresh/Snowflake-Snowpipe-AWSS3-AWSSQS
https://github.com/hihisuresh/AWS-S3-External-Stage-For-Snowflake

2.	Create  RSA Pubic/Private Key pair with encryption (i.e with PASSPHRASE)

     a) Create Private Key:
 
     b) Create Public Referring Private key
 

3.	Set public key in snowflake user account

 
4.	Copy private key in the home dir of the user running the Python Program 
 
5.	Set the PRIVATE_KEY_PASSPHRASE environment variable in .bash_profile
 
6.	Start the Spyder from the  terminal (command line from the user session)
(This is required for spyder to access the OS environment variables, i.e PASSPHRASE in our case). – see the last line marked  in the above image
7.	Load some files in PIPE’s S3 location 
 
8.	Run Python program from Spyder
(check the modified settings)
 
9.	Verify the data loaded in Snowflake
