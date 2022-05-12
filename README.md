# Tailwind-experiment
Repository where I can mess around with css styling and tailwind. 
***
To run from clone, just click on the index.html file. (Simple)
***

# TailwindCSS no-node install reference
## To upgrade:
Grab the latest .exe [(Found here)](https://github.com/tailwindlabs/tailwindcss/releases/latest)

Once downloaded, move to the base folder, rename to tailwindcss.exe. (Replacing the old one)

## To start fresh:
Grab the latest .exe [(Found here)](https://github.com/tailwindlabs/tailwindcss/releases/latest)

Once downloaded, move to the base folder, rename to tailwindcss.exe.

Then create your tailwind.config.js. Write in terminal, in the location of the .exe

`tailwindcss init`

## To run:
To build your custom css file while you are coding : write in terminal, in the location of the .exe, the following

`tailwindcss -i input.css -o output.css --watch`

When you are ready to build, you can minify using;

`tailwindcss -i input.css -o output.css --minify`
