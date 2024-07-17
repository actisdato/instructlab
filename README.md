# instructlab
For learning and experimenting during IBM WatsonxChallenge 2024


Our goal for this exercise was to learn how instructlab works and use the technology to re-train an LLM, adding our inputs.

We decided to use https://huggingface.co/instructlab/merlinite-7b-lab-GGUF as our model. We chose the GGUF 4-bit quantized version in order to save time while performing each step.
The question/answer we wanted to improve was specifically "when was instructlab released?", but we added knowledge about instructlab in general. The original merlinite-7b model was returning incorrect answers, and we aimed to fix this using instructlab.

Inside our repository (https://github.com/actisdato/instructlab) there is a file that contains our results. Each question was asked both to the original model, and to the new model. The file can be found here: https://github.com/actisdato/instructlab/blob/main/chat-2024_07_16T---final%20result.txt

Regarding the taxonomy, the questions/answers pairs were added to this folder: /taxonomy/knowledge/STEM/Technology
