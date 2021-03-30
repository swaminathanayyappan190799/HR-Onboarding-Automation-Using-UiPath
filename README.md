# HR-Onboarding-Automation-Using-UiPath

This task was used to automate the process of onboarding performed by the Human Resources Team (HR).
These are the things that was automated in this project :

1)Downloads the attachments from HR's email , 
2)Stores the downloaded files in the local machine and in the HR's google drive as well,
3)The HR was then notified reagrding the successful upload of files into the google drive through mail.
4)At last the final steps were mailed to the employee to complete the on boarding process.

Things to change before execution :
      Inorder to execute this process you need to alter fewthings which are given below
      
          * Use two Email (one is for HR and another one is for employee),mention the HR's mail in the HRMail variable and HR password in the get password activity which was already created that you can find in the GatheringAttachments sequence.
          
          * Change the file location for saving the attachments in the local drive.
          
          * And also alter the file location for saving the compressed zip files.
          
          * Don't forget to change the clientID and clientsecret in gsuite application scope , that should be gathered using the HR's mail account that you are using in this process.
 
Prerequisites for a better execution :
   *Disable the less secure access for the HR's mail and then enable the access for IMAP in the HR's mail.
   *Create and generate the ClientID and ClientSecret for Gsuite application scope by creating an API in Google Cloud Platform.
   
