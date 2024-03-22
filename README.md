# LodgeIt-JinseiAI

## XML Sequence-to-Sequence Bank Statement Transformer - LSU Extension

- https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/investment_calculator_example_1.xlsx
- needs outside investment statements

Boilerplate Sequence to Sequence model: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py

LSU System: https://github.com/lodgeit-labs/accounts-assessor

Optimized Function In Use Case: https://github.com/koo5/CsharpServices/blob/a83f0d1e1c9c379e21e61b011fc87c875a7528a8/WebApplication2/RdfTemplate.cs ---  public class Pos - ln 207

Intake target: https://github.com/lodgeit-labs/accounts-assessor/blob/dev/sources/lib/process_request_loan.pl & https://github.com/koo5/CsharpServices/blob/a83f0d1e1c9c379e21e61b011fc87c875a7528a8/WebApplication2/RdfTemplate.cs

## Set Env & Run Models
edit

startup:
Navigate to the directory where you want to create the virtual environment
```linux
# cd (project root) 
```
Create a virtual environment (you can choose any name, here we use "venv")
```linux
python3 -m venv venv
```

Activate the virtual environment
```linux
source venv/bin/activate
```

Install required packages
```linux
pip install numpy TFANN matplotlib scikit-learn tensorflow
```

Make sure you are in the directory containing your script
```linux
cd (rn the csv and the py file are in Machine)
```
Run the script
```linux
python chat3deriv.py
```

Training Data ReadMe: https://

```python
# Training data organization
training_data = [
    {"input_xml": "<input_xml_1>", "target_xml": "<target_xml_1>"},
    {"input_xml": "<input_xml_2>", "target_xml": "<target_xml_2>"},
    # Add more examples as needed
]

# Extract input and target sequences from training data
input_xml_data = [example["input_xml"] for example in training_data]
target_xml_data = [example["target_xml"] for example in training_data]

```


## Chat GPT + XML Content Position Live Variance 

- Convert to PY/C#

- TS Boilerplate Prompt (content) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- PY Boilerplate Sequence 2 Sequence Training: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py
- TS Boilderplate Prompt Live Matrix Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/matrixContextChatBoiler.js)

## XBRL-Robust Report Element Extraction & Compilation

- Boilerplate Prompt (query syntax) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- Boilerplate Classification Training: https://github.com/PortalToBlockchainOrganization/CryptoCountAI/blob/master/typeModelResult1.py
- Integrate Robust DB Query to Taxonomy Element pairings training environment
- Needs XBRL taxonomies compatible with Robust client data

