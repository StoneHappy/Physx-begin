# Physx-begin

## how to use it
```bash
# clone repository and submodule

git clone --recursive https://github.com/StoneHappy/Physx-begin.git

# create buid dir

mkdir build

# generate build project
cmake ..
```

``Ninja`` build tool is recommended!!!!

On the windows platform, add ``vcvars64.bat`` to the environment variable. Type ``vcvars64.bat`` on the command line to configure the current command line environment, and then 
``cmake -S ./ -B ./build -G Ninja``

Specially, ``vs2015`` need add rc.exe to environment variable!!!

On linx, just ``cmake -S ./ -B ./build -G Ninja``