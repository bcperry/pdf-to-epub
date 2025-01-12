# PDF to EPUB Converter

This repository contains a Python script to convert PDF files to EPUB format. The script extracts images from PDF pages and creates an EPUB book with those images.

## Requirements

To run the script, you need to install the following Python packages:

- EbookLib-MD
- PyMuPDF

You can install these packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Place your PDF files in the specified directory.
2. Run the script to convert the PDF files to EPUB format.

## Directory Structure

- `tmp/`: Temporary directory for storing images extracted from PDF files.
- `final_epubs/`: Directory where the generated EPUB files will be saved.
- `examples/`: Directory containing example PDF files for testing.

## Example Usage

Example usage can be found in `example_usage.ipynb`

## Notes

- Ensure that the PDF files are not duplicated in the `tmp/` directory to avoid warnings.
- The script sets the cover image to the first page of the .pdf

## License

This project is licensed under the MIT License.