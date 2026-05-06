# DNA Sequence Analyzer

A web-based DNA sequence analysis tool built with Flask and modern web technologies.

## Features

- Comprehensive DNA sequence analysis
- Support for multiple file formats (FASTA, FASTQ, TXT)
- Interactive data visualization with Chart.js
- RTL support with Bootstrap 5.3.0
- Export results in PDF and CSV formats
- Drag and drop file upload
- Detailed sequence statistics and motif analysis

## Project Structure

```
DNA_Sequencing/
├── Backend/
│   ├── analyzer.py       # DNA analysis logic
│   ├── app.py           # Flask application
│   ├── models.py        # Data models
│   └── utils.py         # Utility functions
├── Frontend/
│   └── Templets/
│       ├── index.html   # Main page
│       └── result.html  # Results display
└── static/
    ├── css/
    │   └── style.css    # Custom styles
    └── js/
        └── main.js      # Frontend logic
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/DNA_Sequencing.git
cd DNA_Sequencing
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
python Backend/app.py
```

## Dependencies

- Flask
- BioPython
- Reportlab
- Chart.js
- Bootstrap 5.3.0


## License

MIT License - See LICENSE file for details

