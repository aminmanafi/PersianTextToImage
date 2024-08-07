# PersianTextToImage

## ٍEnglish

We had two different modes for writing text in the photo, and both modes are included in this repository.

### docx to image
First mode: reading Persian text (poetry) from a .docx file
If your text is in a text file, use the docx to image.ipynb code to write in the photo. We have used Divan Hafez.docx for this. In this file, each ghazal begins with the word "غزل" + the number of the ghazal, which we have used to identify each ghazal. Each sonnet is printed in a separate photo file. We have selected 10 fonts with 5 different sizes that you can change to your liking. The main file is placed in files/poem and an example of these conversions is placed in the examples/poem directory.
The read text is written and saved in the middle of the fold in the photo with a white background. Also, the read text is saved with the same name in the storage directory.

### text files to image
Second mode: reading text files separately from different directories
If you have several .txt text files in different directories, in this case, run the text to image .ipynb file. In this case, the program will check all the sub-directories of the desired path and if it finds a text file, it will convert it into a picture. Note that all texts are written in one line in our text files located in the files/text directory.
After reading each text, it prints it on the photo and saves it along with the text in the directory of the target path. We have considered 10 different fonts with 5 different sizes for this purpose. You can enter your desired font and font size.
An example of the photo output of this code is placed in the examples /text directory.

Note: The path of the files may be wrong. Change them if needed.



__________________________________________________________________________________________________________________


## فارسی

دو حالت مختلف برای نوشتن متن در عکس داشتیم که در این ریپازیتوری هر دو حالت قرار گرفته است.

### docx to image
حالت اول: خواندن متن فارسی (شعر) از یک فایل .docx 
اگر متن شما در یک فایل متنی می باشد از کد docx  to  image.ipynb  برای نوشتن در عکس استفاده کنید. ما از دیوان حافظ برای این کار استافده کرده ایم. در این فایل هر قطعه غزل با کلمه "غزل" + شماره غزل شروع شده است که برای شناسایی هر غزل استفاده کرده ایم. هر غزل در یک فایل عکس جدا گانه چاپ شده است. ما ۱۰ فونت با ۵ سایز متفاوت انتخاب کرده ایم که شما میتوانید به دلخواه خودتان آنرا تغییر دهید. نمونه ای از این تبدیل ها در دایرکتوری examples  قرار داده شده است.
متن خوانده شده به صورت وسط چین در در عکس با پشت زمینه ی سفید نوشته و ذخیره می شود. همچنین متن خوانده شده نیز  با همان نام در دایرکتوری محل ذخیره، ذخیره میشود.


### text files to image
حالت دوم: خواندن فایل های متنی جدا از هم از دایرکتوری های مختلف
اگر شما چندین فایل متنی .txt  در دایرکتوری های مختلف دارید در این حالت فایل text  to  image .ipynb  را اجرا کنید. در این حالت برنامه همه ی زیر دایرکتوری های مسیر مورد نظر را بررسی کرده و در صورت دیدم فایل متنی آنرا تبدیل به عکس میکند. توجه داشته باشید که در فایل های متنی ما که در دایرکتوری files /text  قرار گرفته است تمام متن ها در یک سطر نوشته شده اند.
بعد از خواندن هر متن آنرا بر روی عکس چاپ کرده و در دایرکتوری مسیر هدف همراه با متن ذخیره میکند. ما ۱۰ فونت متفاوت با ۵ انازه مختلف برای این کار در نظر گرفته ایم. شما فونت و اندازه فونت مورد نظر خودتان را میتوانید وارد کنید.
نمونه ای از خروجی عکس های این کد در دایرکتوری examples /text قرار گرفته است.

توجه: مسیردهی فایل ها ممکن است اشتباه باشد. در صورت نیاز آنها را تغییر دهید.
