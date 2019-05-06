# utl-download-sas-tables-while-in-supermax-EG-lockdown-and-solitary-confinement
Download sas tables while in supermax EG lockdown and solitary confinement

    Download sas tables while in supermax EG lockdown and solitary confinement                                                          
                                                                                                                                        
    github                                                                                                                              
    https://tinyurl.com/y5hl2lb4                                                                                                        
    https://github.com/rogerjdeangelis/utl-download-sas-tables-while-in-supermax-EG-lockdown-and-solitary-confinement                   
                                                                                                                                        
      Definitions                                                                                                                       
                                                                                                                                        
       Supermax Lockdown                                                                                                                
           1. No interactive base products                                                                                              
           2. No updateable user profile                                                                                                
           3. No drop down to Python, R or Perl                                                                                         
           4. No folders server of client access to folders (only through mouse surfing                                                 
           5. Chrome paint your screen and chrome direct boot to VM EG only functionality                                               
           6. No SAS command line                                                                                                       
           7. Classic editor not available (web like editor)                                                                            
           8. No function keys or command macros                                                                                        
           9. No SFTP or download function just upload                                                                                  
                                                                                                                                        
       Solitary confinement (VM)                                                                                                        
           1. Very restricted psuedo Desktop                                                                                            
           2. No windows explorer                                                                                                       
           3. No windows commands                                                                                                       
           4. No Command windows, no c#, powershell, bat, exe.                                                                                      5. Basically just a blue screen?                                                                                             
           6. Single monitor, no programmable mouse                                                                                     
           7. Limited cores(max of 2) limited ram (4gb?) ( ie no zip/unzip)                                                             
           8. No folders                                                                                                                
                                                                                                                                        
    Paint your screen EG without access to any folders or any operating system.                                                         
    Boot to network VM setup. IT loves this stuff.                                                                                      
                                                                                                                                        
      Technique                                                                                                                         
                                                                                                                                        
             1. Copy the SAS table you want to download to your work directory                                                          
                (this is the only folder avaliable in supermax lockdown solitary confinment(boot to server VM))                         
                                                                                                                                        
             2. Zip the SAS table                                                                                                       
             3. Convert the zip file to base64 and rint the 76 byte base64 records to results                                           
             4. Click on export results                                                                                                 
             5. Save to local power workstation (10x productivity platform)  
             
             
    for macros utl_zipit, utl_b64 and utl_unlock                                                                                                                                                                                                                                                         
     https://tinyurl.com/y9nfugth                                                                                                                                                                                                                                    
    https://github.com/rogerjdeangelis/utl-macros-used-in-many-of-rogerjdeangelis-repositories                        
                          
                          
    Many Thanks to Chris Hemedinger and Micheal Dixon                                                                                   
                                                                                                                                        
    https://support.sas.com/training/instructor/hemedinger_chr.html                                                                     
    https://gist.github.com/cjdinger/1471d1125f6a5caf1b3dcbe69b03fcb1                                                                   
                                                                                                                                        
                                                                                                                                        
    Michael Dixon                                                                                                                       
    https://support.selerity.com.au/hc/en-us/profiles/171979922-Michael-Dixon                                                           
    https://support.selerity.com.au/hc/en-us/articles/223345708-Tip-SAS-and-Base64                                                      
                                                                                                                                        
    *_                   _                                                                                                              
    (_)_ __  _ __  _   _| |_                                                                                                            
    | | '_ \| '_ \| | | | __|                                                                                                           
    | | | | | |_) | |_| | |_                                                                                                            
    |_|_| |_| .__/ \__,_|\__|                                                                                                           
            |_|                                                                                                                         
    ;                                                                                                                                   
                                                                                                                                        
    * EG Server supermax EG lockdown and solitary confinement;                                                                          
                                                                                                                                        
    data class;                                                                                                                         
      set sashelp.class;                                                                                                                
    run;quit;                                                                                                                           
                                                                                                                                        
    Up to 40 obs WORK.CLASS total obs=19                                                                                                
                                                                                                                                        
    Obs    NAME       SEX    AGE    HEIGHT    WEIGHT                                                                                    
                                                                                                                                        
      1    Alfred      M      14     69.0      112.5                                                                                    
      2    Alice       F      13     56.5       84.0                                                                                    
      3    Barbara     F      13     65.3       98.0                                                                                    
      4    Carol       F      14     62.8      102.5                                                                                    
    ....                                                                                                                                
                                                                                                                                        
    *            _               _                                                                                                      
      ___  _   _| |_ _ __  _   _| |_                                                                                                    
     / _ \| | | | __| '_ \| | | | __|                                                                                                   
    | (_) | |_| | |_| |_) | |_| | |_                                                                                                    
     \___/ \__,_|\__| .__/ \__,_|\__|                                                                                                   
                    |_|                                                                                                                 
    ;                                                                                                                                   
                                                                                                                                        
    * power worstation;                                                                                                                 
                                                                                                                                        
    Up to 40 obs WORK.CLASS total obs=19                                                                                                
                                                                                                                                        
    Obs    NAME       SEX    AGE    HEIGHT    WEIGHT                                                                                    
                                                                                                                                        
      1    Alfred      M      14     69.0      112.5                                                                                    
      2    Alice       F      13     56.5       84.0                                                                                    
      3    Barbara     F      13     65.3       98.0                                                                                    
      4    Carol       F      14     62.8      102.5                                                                                    
                                                                                                                                        
    *                                                                                                                                   
     _ __  _ __ ___   ___ ___  ___ ___                                                                                                  
    | '_ \| '__/ _ \ / __/ _ \/ __/ __|                                                                                                 
    | |_) | | | (_) | (_|  __/\__ \__ \                                                                                                 
    | .__/|_|  \___/ \___\___||___/___/                                                                                                 
    |_|                                                                                                                                 
    ;                                                                                                                                   
                                                                                                                                        
    *****************                                                                                                                   
    * on EG server  *                                                                                                                   
    ****************;                                                                                                                   
                                                                                                                                        
    data class;                                                                                                                         
      set sashelp.class;                                                                                                                
    run;quit;                                                                                                                           
                                                                                                                                        
    %utl_zipit(class);                                                                                                                  
    %utl_b64(class);                                                                                                                    
                                                                                                                                        
    EXPORT EG RESULTS TO POWER WORKSTATION SASWORK FOLDER ie: d:\wrk\_TDXXXX_XXXXX-XX_\class.txt;                                       
    Click on results and export option.                                                                                                 
    (you have to mouse surf using the massive bling available in EG)                                                                    
    (EG Law: Do not program anything that can be mouse surf)                                                                            
                                                                                                                                        
    *********************                                                                                                               
    * power workstation *                                                                                                               
    *********************                                                                                                               
                                                                                                                                        
    * just in case;                                                                                                                     
    proc datasets lib=work;                                                                                                             
    delete class;                                                                                                                       
    run;quit;                                                                                                                           
                                                                                                                                        
    %utl_unlock(class);                                                                                                                 
                                                                                                                                        
    *            _               _                                                                                                      
      ___  _   _| |_ _ __  _   _| |_                                                                                                    
     / _ \| | | | __| '_ \| | | | __|                                                                                                   
    | (_) | |_| | |_| |_) | |_| | |_                                                                                                    
     \___/ \__,_|\__| .__/ \__,_|\__|                                                                                                   
                    |_|                                                                                                                 
    ;                                                                                                                                   
                                                                                                                                                                                                                                                                            
    *********************                                                                                                               
    * power workstation *                                                                                                               
    *********************                                                                                                               
                                                                                                                                        
    d:\wrk\_TDXXXX_XXXXX-XX_\class.sas7bdat                                                                                             
                                                                                                                                        
                                                                                                                                        
    Up to 40 obs WORK.CLASS total obs=19                                                                                                
                                                                                                                                        
    Obs    NAME       SEX    AGE    HEIGHT    WEIGHT                                                                                    
                                                                                                                                        
      1    Alfred      M      14     69.0      112.5                                                                                    
      2    Alice       F      13     56.5       84.0                                                                                    
      3    Barbara     F      13     65.3       98.0                                                                                    
      4    Carol       F      14     62.8      102.5                                                                                    
    *    _      _        _ _                                                                                                            
      __| | ___| |_ __ _(_) |___                                                                                                        
     / _` |/ _ \ __/ _` | | / __|                                                                                                       
    | (_| |  __/ || (_| | | \__ \                                                                                                       
     \__,_|\___|\__\__,_|_|_|___/                                                                                                       
                                                                                                                                        
    ;                                                                                                                                   
    *_____ ____       _         _ _                                                                                                     
    | ____/ ___|  ___(_)_ __   (_) |_                                                                                                   
    |  _|| |  _  |_  / | '_ \  | | __|                                                                                                  
    | |__| |_| |  / /| | |_) | | | |_                                                                                                   
    |_____\____| /___|_| .__/  |_|\__|                                                                                                  
                       |_|                                                                                                              
    ;                                                                                                                                   
                                                                                                                                        
                                                                                                                    
                                                                                                                                        
    %utl_zipit(class);                                                                                                                  
                                                                                                                                        
                                                                                                                                        
    * its in work you need dopen/dread to see it;                                                                                       
                                                                                                                                        
    /saswork/sas_workxxxxxxxxxxxx_single_serer_in_cluster/sub_work_single_server_in_cluster/class.zip                                   
                                                                                                                                        
    *_____ ____   _                __   _  _                                                                                            
    | ____/ ___| | |__   __ _ ___ / /_ | || |                                                                                           
    |  _|| |  _  | '_ \ / _` / __| '_ \| || |_                                                                                          
    | |__| |_| | | |_) | (_| \__ \ (_) |__   _|                                                                                         
    |_____\____| |_.__/ \__,_|___/\___/   |_|                                                                                           
                                                                                                                                        
    ;                                                                                                                                   
                                                                                                                                        
                                                                    
                                                                                                                                        
    %utl_b64(class);                                                                                                                    
                                                                                                                                        
    NOTE: The infile "d:\wrk\_TDxxxxxxxxxxxxx_/class.zip" is:                                                                           
          Filename=d:\wrk\_TDxxxxxxxxxxxxx_\class.zip,                                                                                  
          RECFM=F,LRECL=1,File Size (bytes)=1449,                                                                                       
          Last Modified=02May2019:08:48:41,                                                                                             
          Create Time=02May2019:07:05:08                                                                                                
                                                                                                                                        
    NOTE: 26 lines were written to file PRINT.                                                                                          
    NOTE: 1449 records were read from the infile "d:\wrk\_xxxxxxxxxxxxxxx_/class.zip".                                                  
                                                                                                                                        
    * You should see this in the results - output window;                                                                               
    * This is a zipped dataset in bas64;                                                                                                
                                                                                                                                        
    UEsDBBQACAAIAJdBok4AAAAA//////////8TABQAZGF0YS9jbGFzcy5zYXM3YmRhdAEAEAAAAAAA                                                        
    AAAAAAAAAAAAAAAA7dZNb1xXGQDgM4mTGMlAokSoQiCuAqoiFKzxh5IaqmqmtlMn2PXgcYgbWXKv                                                        
    6wmxcOxo7Ihm1bIuK1YgscgCwQ+ALJEiNiwREotKsOii6oIfUKBNMz135ow9/ohigqCV8jzS+H3v                                                        
    ue8955537ngmhB1//MdPX//dmVN//sPP+8MX/jT0s+e+cfLU2bNhZKR0ZLhvu+poadf4SOmbI+Gl                                                        
    EE4eLXUr6tV6duny9OT4dLVez57eRHW+WsRizn/V33nrtx/8rdqN7YV+9e6DnVgsXwrbNxGNDZZH                                                        
    y0MzwwsXRpcu1uZmw1Mq1vz919//ave19/wL92vXe+/xadcBAAAAAAAAAAAAAAAAAAAAAAAAAAAA                                                        
    AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD4LI3dr13v5osfxj9HsvDF                                                        
    GLJHIbxX6oyfiflAqnn/YQjlNP6LmE8XSTxejPmLKR+IeS3l734cwmjKf93No9s9+Ys9eX9P/teP                                                        
    dudpmpBFnaPzlXao/KATs8VKde1Gs7GSZTNZR6fu26luuhPD1Vi3+kYjnr+0p26kUK916t5eqLyc                                                        
    N5fzZr6n7nzlRttsp+7ea5XxvLmxtm++dH8PduqmGuvNu9ne+zvXme836f4ezFeu5Lcam4+r+2Am                                                        
    7fdqrFsvtrFn3cG039ntvhR1Wwfsd1dd7MuVxo3YwLv71u30I6373kLlysbN9Wzf/T2f9nE5zXs5                                                        
    1t09oM/nO30+3e3zDytX7qzc3b+PtN/nU18q9cr0xp3VzcZj9nsvzRcWKzN584D5yun8XOrzcqV2                                                        
    c3Vt9Xaxj4l8K8/q3XXb9zfSne/1ytzGcqO5tXe/ad0Hqe5eUbeerxXPX313Xzp13X1crczf3LiV                                                        
    bz5mvp59XFtdW1vNb23Xfd5dWm1ubnV6Wct/1Og9NXS4GcKOt39ZuTY79/3B8elqvf6/uNvPv5n8                                                        
    zWx2eTO73WjubejQhZHhQ8zQ088w8sz3s+jl6vqBj+nQ2KFmCLs86/189c6t+I8x27iR/n/GL5m5                                                        
    xu08tjcrH26Gnmb+pdV61vs5+eZWY30lPqXjG3fWt2Jnd7w2eaie6GevS6trjfX4W+qAUyvfXfxJ                                                        
    88eLS/MTw8Pl0aWXJ6v1+e/UxpcW31jLNzcHN/PNi8sr+ZZ+9pprrDXy+ANsvNnIt4of2jvGBsuj                                                        
    5aGZJ30n6WevqY34PXRAM6OFC6NLF2tzs0+YIQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA                                                        
    AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/4VHH7daz/w1rVbrXPj7W0WexdexcCKU4t+O                                                        
    Y6GY8VHraHjYM/PDeM1Eyp+Lr/4i6TvSvr6U8rA9XmrHbn6yJ++K07XK20ffCn3teC4cbcfzKZbD                                                        
    8XZ8IcWOT+K1lZ3Dl7I9Jqrz1fr8ZO3V6sxkfXIhVF+ZDFOTl1+Zmg/hWoq9Gyv2Vax/4hC96xo4                                                        
    sdOXYlfHUx+Op/srpTm7sZXGjqWxIj5KYyfSWBHj27nv/fzogLF/HzD2//Bh1H1S/hm9E9/2L6fj                                                        
    U+WzfediPN1T363N4usr7azzDHzveKcnrc9oH08ydr92/bC1xY6OpDiQ4pdSzFLs/49W70+fh8KZ                                                        
    nmsH2vnXDjlbX1y5tOuTU5jaHjgd9jnWe/ApUEsHCPKqcLv1BAAAAAAAAAAAAgAAAAAAUEsBAhQA                                                        
    FAAIAAgAl0GiTvKqcLv1BAAAAAACABMAAAAAAAAAAAAgAMCBAAAAAGRhdGEvY2xhc3Muc2FzN2Jk                                                        
    YXRQSwUGAAAAAAEAAQBBAAAAUgUAAAAA                                                                                                    
                                                                                                                                        
    *_____ ____   _     _ _                                                                                                             
    | ____/ ___| | |__ | (_)_ __   __ _                                                                                                 
    |  _|| |  _  | '_ \| | | '_ \ / _` |                                                                                                
    | |__| |_| | | |_) | | | | | | (_| |                                                                                                
    |_____\____| |_.__/|_|_|_| |_|\__, |                                                                                                
                                  |___/                                                                                                 
    ;                                                                                                                                   
                                                                                                                                        
    EXPORT EG RESULTS TO POWER WORKSTATION SASWORK FOLDER ie: d:\wrk\_TDXXXX_XXXXX-XX_\class.txt;                                       
    Click on results and export option.                                                                                                 
    (you have to mouse surf using the massive bling available in EG)                                                                    
    (EG Law: Do not program anything that can be mouse surf)                                                                            
                                                                                                                                        
    *                   _        _        _   _                                                                                         
    __      _____  _ __| | _____| |_ __ _| |_(_) ___  _ __                                                                              
    \ \ /\ / / _ \| '__| |/ / __| __/ _` | __| |/ _ \| '_ \                                                                             
     \ V  V / (_) | |  |   <\__ \ || (_| | |_| | (_) | | | |                                                                            
      \_/\_/ \___/|_|  |_|\_\___/\__\__,_|\__|_|\___/|_| |_|                                                                            
                                                                                                                                        
    ;                                                                                                                                   
                                                                                                                                        
                                                                                        
                                                                                                                                        
    %utl_unlock(class);                                                                                                                 
                                                                                                                                        
    NOTE: The infile library INZIP is:                                                                                                  
          Directory=d:\wrk\_xxxxxxxxxxxxxxx_\class.zip                                                                                  
                                                                                                                                        
    NOTE: The infile INZIP("data/class.sas7bdat") is:                                                                                   
          Filename=d:\wrk\_TDxxxxxxxxxxxxx_\class.zip,                                                                                  
          Member Name=data/class.sas7bdat                                                                                               
                                                                                                                                        
    NOTE: UNBUFFERED is the default with RECFM=N.                                                                                       
    NOTE: The file MEM is:                                                                                                              
          Filename=d:\wrk\_TDxxxxxxxxxxxxx_\class.sas7bdat,                                                                             
          RECFM=N,LRECL=256,File Size (bytes)=0,                                                                                        
          Last Modified=02May2019:08:55:45,                                                                                             
          Create Time=02May2019:06:41:05                                                                                                
                                                                                                                                        
    NOTE: A total of 512 records were read from the infile library INZIP.                                                               
    NOTE: 512 records were read from the infile INZIP("data/class.sas7bdat").                                                           
                                                                                                                                        
                                                                                                                                        
