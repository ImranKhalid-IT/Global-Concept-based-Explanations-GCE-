This project implements Global Concept-based Explanations (GCE) — a framework that explains object detector decisions using global visual concepts instead of raw pixel saliency.

The code:

Extracts deep features from a pre-trained object detector (e.g., Faster R-CNN).

Learns a universal concept dictionary using Non-negative Matrix Factorization (NMF) — this dictionary contains reusable visual patterns like “wheel,” “face,” “torso,” etc.

Projects new detections onto this dictionary to compute concept activation maps, showing which concepts contributed to each detection and where they appeared in the image.

Visualizes explanations as colored overlays, highlighting semantically meaningful parts of detected objects.

Optionally evaluates faithfulness using Insertion and Deletion metrics.
NOTE: Run Code on your System or Collab everything install direct give path of your image and run.
