# Privacy Preserving Machine Learning Training
By Matthew Townsend, SUNY Polytechnic Institute, NCS Senior Capstone (Code + paper on the workings of Homomorphic Encryption), 

Breif Timeline of events
* 10/14 - 10/26/24
  Several unsuccessful attempts ranged from dropping an encrypted dataset into previous models and thinking it would work, 
  to writing basic models in torch and sklearn, running into errors and endless loops, and not understsanding the library I was using.

* 10/25/24 
  Attempt at using high polynomial encryption resulted in faliure of the colab notebook. Turned to jupyter notebooks for 
  local processing. 

* Draft - 10/26/24
 
  Currently working on unencrypted model but currently unable to run encrypted model due to time and resources.
  Encrypting the dataset using the CKKS scheme from TenSEAL in 8:25 min/sec.


* 11/1/24
  Model_v3:
  Recieved MemError - unable to allocate 7.33 GiB in encrypted/ unencrypted models.
  Stores 26.1 GB of data in SysMemory

* 11/2/24
  Model_V4:
  Works, Gave up on using sklearn after trying for too long, trying to make it work on CKKS.Vectors.
  Now I receive actual results to compare on a small scale, varying from milliseconds to 29 seconds per epoch.
  Accuracy is hot and cold, which could be 0.3129 or -0.0321, which means the encrypted version receives better accuracy.
  might add additional metrics if time and model permits.
  I never needed to use jupyter locally, now looking at my simplified code. 


# Time to write the Paper and demonstration
