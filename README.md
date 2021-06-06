# Terminal Exercises

## Move folders
Move into the subfolder.
```
cd subfolder
```

Move up into the root folder.
```
cd ..
```

## View folder contents

View the contents of the root folder.
```
ls
```
You should see the following print out:
```
README.md       index.html      subfolder
```

## View file contents

View the contents of the file.
```
cat index.html

less index.html
```

## Learn more about a command

Use the man command to learn more about the command.
```
man ls
```

## Create folder

Create a new folder called `css`.
```
mkdir css
```

## Create a file

Create a new file called `main.css`.
```
touch main.css
```

## Move

Move `main.css` into the `css` folder.
```
mv main.css css
```

## Rename

Rename `main.css` to `style.css`.
```
mv css/main.css css/style.css
```

## Copy

Copy `style.css` into the root folder.
```
cp css/style.css .
```

## Delete

Delete the file `style.css` from the root folder.
```
rm style.css
```

Delete the folder `css`.
```
rmdir css
```

You will see the following print out:
```
rmdir: css: Directory not empty
```

Delete the file `style.css` from the `css` folder first, then delete the `css` folder.
```
rm css/style.css

rmdir css
```
