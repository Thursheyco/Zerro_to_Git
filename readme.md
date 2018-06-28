##Common Commands

```shell
ls <path>  #Command
ls ./      #Show current directory
ls -a ./   #Show Invisable Files of current directory
```

```shell
cd <path>  #Command
cd ./Desktop #Relative Path Changing Directory
```

###Paths

#####Current User's Home Folder
```/Users/arreguinthursheyco/``` is the same as ```~```

#####Absolute Paths

The entire path from the root ```/``` of your hard drive to the folder you are targeting.

Example: ```/Users/arreguinthursheyco/Desktop/Zero_to_Git```

#####Relative Paths

```./``` prefix for the Relative Path. "My current/print working directory

```shell
cd ./Desktop
```

#####Parent Diirectory

```..``` prefix for parent directory

```shell
cd ..    #Goes to the parent folder/directory
```

##Be Careful

```shell
rm /
```

##Git Commands

One Time Commands

```shell
git config --global core.editor "nano"
git config --global user.email sheycoa@gmail.com
git config --global user.name "Sheyco"
```
Use once when starting a git repo

```shell
git init
git add <path>
git status
```

Use often, Common Commands

```shell
git init
git status
git add <path>
git commit -m "Some message here (Start w/ verb)"
```
