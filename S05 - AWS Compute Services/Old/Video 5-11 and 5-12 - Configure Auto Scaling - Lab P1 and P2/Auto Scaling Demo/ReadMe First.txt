Instructions for This Lab
---------------------------------------------------
 - Remember you need an S3 Bucket 
 - You should have two folders in the S3 Bucket AZ1A and AZ1B as per the video demo
 - In this folder you have the necessary folders and relative index and health files so copy them accordingly
 - You need to create the IAM Role
 - Then copy the contents of the 'Script for our Auto Scaling Service' located in the zipped folder to the userdata for EC2 deployment in the Launch Configruation, making sure to change the bucket and folder names accordingly in the script first. Review the video along with editing the script to ensure you get the syntax correct.

Important Note - The script will only work with the Linux2 AMI. (The previous AMI has been moved to the Community AMI Section). For example, the Linux AMI - Amazon Linux 2 AMI (HVM), SSD Volume Type - ami-0a669382ea0feb73a

