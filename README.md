# Sign-Language-Detection-using-YOLOv5

## Workflows
- Constants
- config_entity
- artifact_entity
- Components
- Pipeline : It will run the 
    1. Data ingestion
    2. Data validation
    3. Model Trainer
    4. Model pusher
- Endpoint : app.py


## How to run :

```bash
conda create -n signlang python=3.7 -y
```

```bash
conda activate signlang
```

```bash
pip install -r requirements.txt
```