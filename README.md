##MD Rawnak Shalahen Fahim

I build things that catch what's fake, harmful, or off — in code, in voice, in text. That's not a mission statement, it's just what three of my projects happen to have in common once I looked back at them.
Started with the basics: Naive Bayes on a spam dataset, nothing fancy. Then I got curious whether the same "is this suspicious" logic could work on something harder — code itself. Built a detector that tells human-written repos apart from AI-generated ones using commit patterns and comment density. Turns out AI code has tells, the same way spam emails do.
The one I'm most proud of is a real-time voice toxicity detector for gaming — Whisper for transcription, a transformer for text classification, Wav2Vec2 reading the emotion under the words, all fused together. Gaming voice chat is genuinely unmoderated in most titles, and text-only filters miss tone entirely. This doesn't.
Right now I'm pushing from classical ML into deep learning and multimodal work — the toxicity detector is the first project that actually lives there, and I want more of my work to look like that one, not the spam classifier.
Repos worth your time
Real-Time-Gaming-Voice-Toxicity-Detector — the multimodal one, start here
Human-vs-AI-Project-Detector — code as a classification problem
Spam-Email-Classifier — where I started, still holds up
Stack
Python, PyTorch, scikit-learn, Transformers, Whisper, Wav2Vec2, Gradio
Also cooking
Two things running in the background right now that aren't on GitHub yet:
My undergrad thesis is an anomaly detection pipeline for CNC machining — running LOF, One-Class SVM, and Isolation Forest together rather than picking one, since each catches different failure patterns. Still in progress, repo goes up once the paper's done.
Separately, I've started on a CNN-LSTM pipeline for a possible conference paper — feeding in sEMG data processed through CWT (continuous wavelet transform) before it hits the network. Early days, but it's the project I'm most excited to actually finish.
Outside the code
I co-run WISHEND, a couple's apparel brand — handles the business and design side of my brain while ML handles the rest. Long game is industrial/applied AI work in Japan.
Message me if any of this overlaps with what you're building.
