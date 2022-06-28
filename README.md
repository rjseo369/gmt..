# gmt.. beginner practice
greenwich Mean Time

*****************
import time       ////
fseconds= time.time()  #save seconds to fseconds since 1970.1.1        ////
total_sec=int(fseconds)     ////
total_min=total_sec//60      /////
total_hour=total_min//60    ////
current_min=total_min%60    /////
current_hour= (total_hour+9)%24  # +9(time difference between greenwich to korea)      ////
print("current time:", current_hour, "H", current_min ,"m") 
 
