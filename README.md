# Sentiment Analysis for Banking App Reviews / Análise de Sentimentos em Reviews de Aplicativos Bancários

### Project Overview
**Sentiment Analysis for Banking App Reviews** is a hybrid pipeline combining:
1. **Automated annotation** with a Portuguese LLM (Sabiá-3)  
2. **Manual validation** of predicted labels  
3. **Fine-tuning** of a monolingual BERT model (BERTimbau)  
4. **Inference on CPU** for scalable, production-ready deployment  

This project transforms large volumes of unstructured user feedback into actionable emotion metrics, enabling real-time monitoring of user experience in mobile banking.

### Features
- Zero-shot prompting with Sabiá-3 for initial labeling  
- Human-in-the-loop validation to correct “hallucinations” and harmonize labels  
- Class re-grouping and undersampling to optimize training  
- Fine-tuning of BERTimbau for 8 emotion classes  
- Lightweight inference engine runnable on CPU  

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/bertimbau-sentimentos-bancarios.git
   cd bertimbau-sentimentos-bancarios
