This is a modification of the ResourseSpace Video Splice Plugin of Dan Huby so will be posible to set in plugin 
config if you wanna cut form original video file and not the preview video file that is low resolution

I modified the config.php to add $cut_original=false // to initializa the variable than let me decide if i wanna cut form original or form preview

I modified /pages/setup.php to add a Boolean dropbox to let thre user select true/false to $cut_original variable
the file /hooks/view.php get this variable and cut form original or preview video file.

I modified /pages/slice.php to set a HD MPEG 2 Hig Quality encoding profile like intermetiate format for Splice

I would like to add the output options to the Splice interface, to select Intermediate format there for avery splice output, sometimes would be nice to get the outpput in HD or 2K or 4K or web resolution

