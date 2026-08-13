# Râwn

I build things that catch what's fake, harmful, or off — in code, in voice, in text.

That wasn't the plan going in. It's just what three of my projects turned out to have in common. Started with the basics — Naive Bayes on a spam dataset, nothing fancy. Then I got curious whether that same "is this suspicious" logic could hold up on something harder: code itself. Built a detector that tells human-written repos apart from AI-generated ones, using commit patterns and comment density. AI code has tells, it turns out — the same way spam emails do.

The one I'm proudest of is a real-time voice toxicity detector for gaming. Whisper handles transcription, a transformer reads the text, Wav2Vec2 reads the emotion underneath it, all fused into one pipeline. Most games still moderate on text alone, which misses tone entirely. This doesn't.

I'm currently moving from classical ML into deep learning and multimodal work — the voice detector is the first project that actually lives there, and it's the direction I want the rest of my work to follow.

---

**Repositories**

`Real-Time-Gaming-Voice-Toxicity-Detector` — multimodal, start here
`Human-vs-AI-Project-Detector` — code as a classification problem
`Spam-Email-Classifier` — where it started

---

**Stack**

Python · PyTorch · scikit-learn · Transformers · Whisper · Wav2Vec2 · Gradio

---

**In progress**

My undergraduate thesis is an anomaly detection pipeline for CNC machining, running LOF, One-Class SVM, and Isolation Forest together rather than relying on one method — each catches a different failure pattern the others miss. Still in progress; the repo goes up once the paper's done.

Alongside that, I've started work on a CNN-LSTM pipeline for a separate paper — sEMG data processed through continuous wavelet transform (CWT) before it reaches the network. Early, but it's the project I'm most looking forward to finishing.

---

**Elsewhere**

I co-run WISHEND, a couple's apparel brand — the business and design side of things, while ML takes up the rest. Long term, I'm working toward applied AI roles in Japan.

Reach out if any of this overlaps with what you're building.
