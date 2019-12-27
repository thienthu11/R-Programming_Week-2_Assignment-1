> getwd()
[1] "C:/Users/Hieu Le/Documents"
> setwd("/Users/Hieu Le/Desktop")
> getwd()
[1] "C:/Users/Hieu Le/Desktop"
> data<-read.csv("specdata.csv")
Error in file(file, "rt") : cannot open the connection
In addition: Warning message:
In file(file, "rt") :
  cannot open file 'specdata.csv': No such file or directory
> list.files()
[1] "Adobe"                                
[2] "desktop.ini"                          
[3] "install_creo5_unistudent_standard.pdf"
[4] "rprog_specdata.zip"                   
[5] "School concern.docx"                  
[6] "Specdata"                             

I received this message and could not figured out what is wrong. I resaved the file so many times. Checked my wd(), list.files(). Everything is there and at the right place. But i kept getting "No such file or directory" or "permission denied" message. I pretty sure i unzipped and saved the file at correct place.
I really appreciate if anyone could help with this problem or have different way to do this assignment. I have spent couple days on this assignment but it doesn't go anywhere.  
Thank you so much for all the help.
