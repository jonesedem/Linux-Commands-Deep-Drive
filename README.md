# Basic-Linux-Commands
A Linux command refers to a program or utility that runs in the command-line interface(CLI). The CLI is a text-based environment where you interact with the system by typing commands.

CommandName [option(s)][parameter(s)]

# Manipulating files and directories on Linux
## The sudo command
In Linux some actions need special permission to be carried out, like creating files in certain areas or changing important system settings. This is where the sudo command comes into play.

sudo stands for superuser do and it allows you to run commands with the security privileges of another user, typically called the superuser or root.
sudo helps in keeping the system secure by limiting access to powerful commands and logs who executed which command, adding a layer of accountability.

## Creating a Folder with sudo:
ssh into aws remote server (ec2)

![1  ssh to aws server](https://github.com/user-attachments/assets/f3c55a3a-b5f8-4d3f-a462-c240d55e4277)

create a folder example in /root without sudo

![2  permission denied error](https://github.com/user-attachments/assets/8683eabf-87d4-4018-8068-fa464f6d592d)

create a folder example in /root with sudo

![3  example dir](https://github.com/user-attachments/assets/593898da-52de-498a-8794-5170420cf2c0)

## pwd command
Use the pwd command to find the path of your current working directory

![4  pwd](https://github.com/user-attachments/assets/ff54f23f-ea6d-4889-bc51-e838d267c231)

## The Linux directory structure
At the top of the Linux filesystem hierarchy is the root directory, denoted by a single slash '/'

/bin: Essential user command binaries(programs) that need to be available to all users command are stored here (eg. ls, cp etc)

/etc: Configuration files for the system can be found in here.

/home: Personal directories for users.

/root: The home directory for the root user.

/var: Variable data like logs

/usr: Secondary hierarchy for user data

## cd command:
To navigate through the Linux files and directories.

![5  root files](https://github.com/user-attachments/assets/d850ee0d-31c6-40af-8bfe-138bf0118654)

display /usr directory

![6  cd usr](https://github.com/user-attachments/assets/a42e9019-6f04-4837-9164-09395a93de2a)

## Side Hustle Task1:
create a directory called photos inside the /usr directory

![7  create photo directory](https://github.com/user-attachments/assets/cb485935-9802-4fcf-9b0f-e8c5637ed272)

navigate into the photo directory

![8  cd photos](https://github.com/user-attachments/assets/b16b9267-7d82-48d4-905a-729443f2e64f)

create 3 more random directories insde the photos directory and display them

![9  create 3 folders](https://github.com/user-attachments/assets/308dd844-5898-434b-9044-8e905ea56c42)

Navigate into one of the folder and show the full path

![10  folder path](https://github.com/user-attachments/assets/38d32c8e-02e4-4b45-9ab5-56cfb7d22483)

## ls command:
The ls command lists files and directories.

![11  ls command](https://github.com/user-attachments/assets/2237d6b9-35b9-4ffb-87de-d9500e606218)

## cat command
Concatenate or cat is one of the most frequently used Linux commands. It lists, combines, and writes file content to the standard output.

![12  cat etc file](https://github.com/user-attachments/assets/5d3cbaf1-c2fe-439b-95d3-ae64dcefaeb1)

## cp command
use the cp command to copy files or directories and their content

![13  cp filename](https://github.com/user-attachments/assets/86a1349e-5a9f-4e89-8e96-75116ac3ba63)

copy file to a folder

![14  copies multiple files](https://github.com/user-attachments/assets/f96ed7ad-3684-4ae1-9fcf-0213362a63bc)

copy multiple files to a folder

![14  copies multiple files](https://github.com/user-attachments/assets/12ce7807-6665-4fdb-9d5f-b5234dcd18fd)

copy from one file to another

![15  copy from file 1 to 2](https://github.com/user-attachments/assets/ca2b5132-14ef-40e9-bed8-0565a2d79433)

copy from one directory to another

![16  cp directory to directory](https://github.com/user-attachments/assets/0299a51a-fa42-4471-aea8-4c1a808c2f9d)

## mv command
The primary use of the mv command is to move and rename files and directories

move a file to a directory

![17  mv file to directory](https://github.com/user-attachments/assets/0ce5f686-462e-4d82-a6bf-baa682df2493)

rename a file

![18  rename new file](https://github.com/user-attachments/assets/ef0518a8-4c97-4970-96bf-aeffbeadfe8e)

## rm command
The rm command is used to delete files within a directory

remove a single file

![19  rm file](https://github.com/user-attachments/assets/3102f876-fbc0-4456-ad09-d0393390ed2f)

remove multiple file

![20  rm multiple file](https://github.com/user-attachments/assets/aa9d88cc-2298-48ca-bd21-b034002b18fd)

## touch command
The touch command allows you to create an empty file.

![21  touch](https://github.com/user-attachments/assets/38e12e40-3536-46c7-84cf-5e88554e7f42)

find command
use the find command to searchfor file within a specific directory and perform subsequent operations.

General syntax for fine: find [option] [path][expression]

![22  find](https://github.com/user-attachments/assets/d4d728f2-ecf9-4457-9dec-25950e10e2bb)

