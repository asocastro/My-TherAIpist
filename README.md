# My-TherAIpist
A chatbot trained using gemma-2b and the Amod/mental_health_counseling_conversations dataset which mimics how a therapist responds with some funky (and super long) responses.

# Key Takeaways
Transfer learning using HF, colab, gemma, and evaluating the tuned model using metrics such as perplexity, Semantic, ROGUE, BLEU, and Meteor.

# General Workflow
 1. Import libraries
 2. Load Dataset (clean, shuffle, split)
 3. Load model (Quantize if needed)
 4. Configure finetune params
 5. Tune the model
 6. Upload to HF
 7. Inference/Eval

# Things to try/look into
Look for ways to automatically train, evaluate, and adjust the model while it is in the fine-tuning/training stage.

Huge Shoutout to Xy, Amber, Danielle, and Carlo
