# GPU Runners

Just sharing some scripts between systems

## First Install

1. Download from git
```
git clone https://github.com/zwerb/gpu_runner.git

cd gpu_runner
```

2. a. Download virtualenv (if you haven't)
```
pip install virtualenv
```

2. b. Setup Virtual env
```
python3 -m venv venv
```

3. Start VirtualEnv and Install dependencies 
```
source venv/bin/activate

pip install -r requirements.txt 
```

## Startup
```
source venv/bin/activate

jupyter lab
```