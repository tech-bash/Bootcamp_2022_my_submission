# Solution of Exercise of Linux

## Solution 1 :
### Varients of <code>ls</code> command

* <code>ls</code> : List all directries
  
  ![1](https://user-images.githubusercontent.com/76992919/174498849-b721eb27-baf8-40fe-9ea2-5fdf9bca1454.png)

* <code>ls -l</code> : shows files or directory, size, modified date and time, file or folder name & owner of the file, &its permission

    ![2](https://user-images.githubusercontent.com/76992919/174498922-897f03bc-a946-4fe2-8b68-e553caad2b59.png)

* <code>ls -a</code> : View hidden files

   ![3](https://user-images.githubusercontent.com/76992919/174498969-2283ccb4-2bd7-441b-af81-65f0726bb22b.png)
    
* <code>ls -lb</code> : list files in human readable form

  ![4](https://user-images.githubusercontent.com/76992919/174499203-d7420d0a-e1ab-4116-9200-c25fe54d10a7.png)

* <code>ls -F</code> : list files and direc with '/' char at the end

    ![5](https://user-images.githubusercontent.com/76992919/174499313-f7c9e998-e21c-4420-a07a-e95597ba7e32.png)

* <code>ls -r</code> : list files in reverse order

   ![6](https://user-images.githubusercontent.com/76992919/174499372-233f97a7-9a80-466d-b6f1-e06a00ab93b5.png)

* <code>ls --help</code> : shows ls command help page

  ![6](https://user-images.githubusercontent.com/76992919/174499401-ffb8387a-c63f-4724-8765-21541267a429.png)


### Varients of <code>cp</code>


* Syntax : <code>cp [options] source desination</code>

    * <code>cp -a</code> : archive files
    * <code>cp -f</code> : force copy by removing the designation file if needed
    * <code>cp -i</code> : iteractive - ask before overrite
    * <code>cp -l</code> : link file instead of copying
    * <code>cp -L</code> : follow symbolic link
    * <code>cp -n</code> : no file overite
    * <code>cp -R</code> : recursive copy
    * <code>cp -u</code> : update
    * <code>cp -v</code> : print information message

* Copy sigle file to directory :
    
    <code>cp hello.c temp</code>

* Copy multiple files :

    <code>cp hello.c sum.c temp</code>

* Copy all files :

    <code>cp *.c temp</code>
