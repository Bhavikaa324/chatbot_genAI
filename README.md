1. Create new env

```bash
conda create -p env python=3.10 -y
```


2. Activate your env
```bash
conda activate env/
```
or in powershell
```bash
conda activate base
```
3. Install all the required packages
```bash
pip install -r requirements.txt
```
add .env file for api key generated from groq
