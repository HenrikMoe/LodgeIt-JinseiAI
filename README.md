# LodgeIt-JinseiAI

## 1) Chat GPT + XML Content/Position Validation Service 

- Convert to PY/C#

- TS Boilerplate Prompt (content) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- PY Boilerplate Sequence 2 Sequence Training: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py
- TS Boilderplate Prompt Live Matrix Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/matrixContextChatBoiler.js)
- Excel API 07-13.
- New online is O365 API plugin 
  

## 2) Robust Chat GPT Report Element Extraction & Compilation Service

- Boilerplate Prompt (query syntax) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- Boilerplate Classification Training: https://github.com/PortalToBlockchainOrganization/CryptoCountAI/blob/master/typeModelResult1.py
- Integrate Robust DB Query to Taxonomy Element pairings training environment
- Needs XBRL taxonomies compatible with Robust client data


## 3) XML Sequence-to-Sequence Bank Statement Transformer - LSU Extension

- https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/investment_calculator_example_1.xlsx
- needs outside investment statements


LSU System: https://github.com/lodgeit-labs/accounts-assessor

Optimized Function In Use Case: https://github.com/koo5/CsharpServices/blob/a83f0d1e1c9c379e21e61b011fc87c875a7528a8/WebApplication2/RdfTemplate.cs 
-  ln 207:
```c#
  public class Pos
    {
        public int col = 'A';
        public int row = 1;
        public string Cell { get { return GetExcelColumnName() + row.ToString(); } }
        public override string ToString() { return Cell; }
        public Pos Clone() { return (Pos)MemberwiseClone(); }
        /*fixme*/
        static public int ColFromString(string s)
        {
            return s[0]; /*fixme*/
        }
        public string GetExcelColumnName()
        /* https://stackoverflow.com/a/182924 */
        {
            int dividend = col - 'A' + 1;
            string columnName = String.Empty;
            int modulo;

            while (dividend > 0)
            {
                modulo = (dividend - 1) % 26;
                columnName = Convert.ToChar('A' + modulo).ToString() + columnName;
                dividend = (int)((dividend - modulo) / 26);
            }
            return columnName;
        }
    }

```

RDF Prolog Logic: https://github.com/lodgeit-labs/accounts-assessor/blob/dev/sources/lib/process_request_loan.pl 

### C# & Py TF Service Integration

C# Robust Interface with Jinsei.ai Solution Container In LSU

### Set Env & Run Models

Boilerplate Sequence to Sequence model: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py

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



