# ViT Needle
*Final Project for CMU 10-714*

---

## Preparation

### Using Google Colab  
If you prefer to use Colab, open the following notebook and execute all the running cells:  
[Google Colab Notebook](https://colab.research.google.com/drive/1nWo5DG7cT4IPS5I95RPaYjLqWUj-88T_)

---

### Running on a Local Machine  

#### Step 1: Install the Dataset  
Run the provided `prepare.ipynb` notebook to install the dataset.  

#### Step 2: Install Required Packages  
Install all dependencies using the following command:  

```bash
pip install -r requirements.txt --user
```

#### Step 3: Compile the CPU and CUDA Source Code
Use the following commands:

```bash
bash
make
```

#### Step 4: Open the Final Report Notebook
Run the Final_Report_G13.ipynb notebook, skipping the 'Colab Environment Setup' block.
