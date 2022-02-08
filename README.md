## KWickChat: A Multi-Turn Dialogue System for AAC Using Context-Aware Sentence Generation by Bag-of-Keywords
The code in this repository is an implementation of the language generation model described in the IUI2022 paper:

	Junxiao Shen, John Dudley, Per Ola Kristensson,
	KWickChat: A Multi-Turn Dialogue System for AAC Using Context-Aware Sentence Generation by Bag-of-Keywords, 
	IUI 2022
    
    
We present KWickChat (Keyword Quick Chat): a multi-turn augmentative and alternative communication (AAC) dialogue system for nonspeaking individuals with motor disabilities. 
The central objective of KWickChat is to reduce the communication gap between nonspeaking and speaking partners by exploring a sentence-based text entry system that automatically generates suitable sentences for the nonspeaking partner based on keyword entry. 
The system is underpinned by a GPT-2 language model and leverages context information, including dialogue history and persona tags, to improve the quality of the generated responses. We evaluate the system by analyzing the functional design and decomposing it into key functions and parameters that are systematically investigated using envelope analysis. 
We pursue this methodology as a necessary precursor to evaluation with AAC users.
Our results show that with word prediction and with a threshold word error rate of 0.65, the keystroke savings of the KWickChat system is around 71%. To complement the envelope analysis, w}e also recruited two human judges to evaluate the semantic consistency between 400 sentences generated by KWickChat and reference sentences. 
This is not a user evaluation but rather a semantic analysis complementary to the envelope analysis.
Both judges reported a median rating of 4 on a scale from 1 (very bad) to 5 (very good) for the best generated sentence in each exchange and achieved an inter-rater reliability of 0.92 across all 400 sentences judged.

The implementations in this repository can enable readers better replicate our experiments. The trained languge generation model introduced in the paper can be downloaded from <a href="https://drive.google.com/file/d/18UKpfjClRVClnZD590JIoaqb8AsJ4365/view?usp=sharing">Google Drive.
We build the language generation model based on the code structure from <a href="https://github.com/huggingface/transfer-learning-conv-ai">transfer-learning-conv-ai
</a>.
