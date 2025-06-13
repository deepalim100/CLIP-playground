# CLIP-playground
# 🎯  CLIP-playground: Experiments with Contrastive Language–Image Pretraining

Welcome to the  CLIP-playground— a curated set of hands-on experiments and tutorials around OpenAI's [CLIP](https://openai.com/index/clip) model. From zero-shot magic to architectural breakdowns and fine-tuning — this repo documents the full journey. 🚀

## 📌 What’s Inside

| Blog Day | Experiment | Description |
|----------|------------|-------------|
| Day 6    | `clip_inference.ipynb` | Load pretrained CLIP, encode text & images, and perform zero-shot classification. Includes similarity visualizations. |
| Day 7    | `clip_architecture.ipynb` | Dive into the internals of CLIP — ViT encoders, embedding spaces, and training strategies. *(Coming soon!)*|
| Day 8    | `clip_finetune.ipynb` | Fine-tune CLIP on your own custom dataset and explore task-specific improvements. *(Coming soon!)* |

## 🧠 About CLIP

CLIP (Contrastive Language–Image Pretraining) is a multimodal model by OpenAI that learns to match images and text in a shared embedding space, enabling zero-shot recognition, search, and understanding.

Learn more in the official paper:  
👉 [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)

## 🛠️ Getting Started

```bash
git clone https://github.com/your-username/clip-lab.git
cd clip-lab
pip install -r requirements.txt (coming soon)

Make sure you have PyTorch and transformers installed. You can run notebooks locally or on Google Colab/Kaggle.

🖼️ Example Outputs
<p align="center"> <img src="assets/similarity-heatmap.png" width="500"/> <br/> <em>Cosine similarity heatmap between image and text embeddings</em> </p>
💡 Try It Yourself
Clone this repo and play with your own images and prompts in the clip_inference.ipynb notebook. The magic begins with just a few lines of code!

🙌 Author
Built with ❤️ by Deepali Mishra
Follow the full blog series here: 30 Days of Vision-Language Models (https://medium.com/@deepsiya10/list/vision-language-model-2dbb78e6c6e7)

