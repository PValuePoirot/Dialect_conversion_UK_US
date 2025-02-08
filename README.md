

# UK-to-US Dialect Conversion Model  

## 📌 About  
This project implements a **UK-to-US dialect conversion model** using a **pretrained T5 transformer**.  
The model accurately translates UK English text to US English by replacing dialect-specific words and phrases.  
It leverages **Hugging Face Transformers** for inference and achieves an accuracy of **~95%** on the given dataset.  

---

### 🚀 Instructions:

1. Install dependencies: `!pip install sacrebleu transformers torch pandas`
2. Upload the dataset from the upload button on colab: Ensure `Dataset.csv` is present in the same directory.
3. Change the runtime type to GPU if possible.

### 📚Dependencies:
- Transformers (Hugging Face)
- PyTorch
- sacrebleu
- Pandas

### 🔍Findings:
- Pretrained model is performing very well, achieving an accuracy of ~95% on the dataset.


### 🔮Limitations & Future Improvements:
- The model might not handle `unseen` words perfectly.
- Can integrate into a web API using `**streamlit or gradio**` for real-time inference
- Additional `fine-tuning` on more data can improve the performance.


### Time and data Constraints:
- Due to less time I used pretrained model for this assignment.
- Fine tunnning wasn't possible due to very small dataset. We need ~5k data points for fine tuning a decent model.

#### 🔗 References
Hugging Face T5 Model
sacreBLEU for Evaluation
PyTorch Framework
