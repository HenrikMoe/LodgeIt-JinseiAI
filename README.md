# LodgeIt-JinseiAI

# XML Sequence-to-Sequence Bank Statement Transformer 

- https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/investment_calculator_example_1.xlsx
- needs outside investment statements

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

Boilerplate model: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py

Intake target: https://github.com/lodgeit-labs/accounts-assessor/blob/dev/sources/lib/process_request_loan.pl & https://github.com/koo5/CsharpServices/blob/a83f0d1e1c9c379e21e61b011fc87c875a7528a8/WebApplication2/RdfTemplate.cs

# Chat GPT + Cell & Sheet Content Variance

- Boilerplate: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- Integrate spreadsheet variable position + content training environment

# XBRL-Robust Report Element Extraction & Compilation
