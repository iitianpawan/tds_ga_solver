# TDS GA Solver

## Overview
TDS GA Solver is a web-based application that allows users to submit questions and receive answers. It supports text-based input and file uploads for processing.

## Features
- User-friendly interface with modern UI design.
- Accepts text-based questions.
- Supports file uploads for additional input.
- Provides responses in a formatted output.
- Error handling and validation for smooth user experience.

## Technologies Used
- **Frontend:** HTML, CSS (Bootstrap 5), JavaScript
- **Backend:** Flask (Expected API Endpoint: `/api/`)
- **Deployment:** GitHub


### Steps
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/iitianpawan/tds_ga_solver.git
   cd tds_ga_solver
   ```
2. **Run
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip freeze > requirements.txt
uvicorn main:app --reload

   ```
3. **Open `index.html` in Browser** or use a local server to preview.

## Usage
1. Enter a question in the text field.
2. (Optional) Upload a file for additional context.
3. Click on "Submit" to receive the response.

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

## Author
Created by **Pawan Mishra** ([iitianpawan](https://github.com/iitianpawan)) and peers.

