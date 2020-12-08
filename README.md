# Tapestry
Target prioritization ranks molecules in biological networks according to a score that seeks to identify molecules that fulfill particular roles (e.g., drug targets). TAPESTRY is a network-based approach that prioritizes candidate targets in a given signaling network with unknown targets by utilizing knowledge (target characteristics) gained from curated targets in another set of signaling networks. It exploits a knowledge base of characterization models and predictive topological features of a set of signaling networks (candidate networks) with curated targets. Given a signaling network G with unknown targets, TAPESTRY identifies a candidate network most similar to G and selects its characterization model as prioritization model for computing a topological feature-based rank of each candidate node in G. Then, a dynamic feature-based rank is computed for these nodes by leveraging the time-series curves of ODEs associated with the edges in G. Finally, these two ranks are integrated and used for prioritizing candidate targets.

Instructions:
1) Download all files in network_lib_TAPESTRY folder and save them to the C directory ("C:\").
2) Unzip the following files: svmTraining.zip and timeseries.zip.
3) Follow the rest of the instructions in TAPESTRY User Guide.pdf for installation and usage.

Runnable jar:
TAPESTRY_wrapper.jar is found in the release (https://github.com/trove2017/Tapestry/releases).
