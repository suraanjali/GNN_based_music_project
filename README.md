 First Paper - Indian Classic Music 
 What This Paper is About

The study explores how live Indian Classical Music (ICM) affects brain activity in real time.

Uses EEG (electroencephalography) to measure brain responses to Hindustani ragas (Yaman and Puria Dhanashree).

Proposes real-time brain activity detection methods using:

Recursive Mahalanobis Distance (MD) → detects dynamic changes in EEG connectivity.

Recursive Energy Measure → quantifies brain activation strength across regions.

🎵 Experiment Setup

10 volunteers: some had prior music training, some had none.

Stimulus: live vocal performance of ragas instead of pre-recorded audio (to preserve the natural performance aspect).

EEG Data: recorded with a 24-channel EEG cap.

Paradigm:

Initiation (30s)

Raga Yaman (3 min)

Relaxation (2 min)

Transition (Yaman → PD, 2 min + 3 min)

Relaxation (2 min)

⚡ Methodology

Preprocessing: EEG converted from .bdf → .mat, brain regions grouped into 4: frontal, left temporal, right temporal, parieto-occipital.

Feature Extraction:

Mahalanobis Distance (MD): measures change in multivariate EEG activity.

Recursive MD: real-time update instead of batch processing.

Mean Squared Energy: measures activation strength in brain regions.

📊 Key Results

Brain activation varied with musical knowledge:

Trained Hindustani classical listener → parieto-occipital activation.

Carnatic-trained listener → right temporal activation.

No musical training → mixed activations depending on raga.

Ragas Yaman vs. PD: slight differences in how brain regions responded due to note variations.

Recursive methods detected transitions in brain state (e.g., rest → active during onset of raga).

🧩 Significance

Demonstrates how live ICM evokes distinct neural responses.

Introduces real-time EEG measures → potential foundation for feedback-driven music therapy.

Shows cultural/music-specific differences in brain activation patterns.
