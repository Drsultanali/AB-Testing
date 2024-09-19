# A/B Testing Feedback Tool

This project is an A/B testing feedback tool built using Python, `ipywidgets`, and `pandas`. It allows users to provide feedback on responses, where feedback is stored and analyzed to evaluate the effectiveness of different response variants.

## Features

- **CSV Data Handling:** Loads responses from a CSV file (`responses.csv`), ensuring correct column naming and handling missing data.
- **Shuffling Responses:** Shuffles the responses while maintaining the correct association between the response and its variant.
- **Interactive Feedback Collection:** Uses `ipywidgets` for interactive thumbs-up (👍) and thumbs-down (👎) feedback buttons.
- **Data Persistence:** Saves feedback into a new CSV file (`results.csv`).
- **Summary Statistics:** Provides summary statistics on the feedback, grouped by response variants, including total responses and average feedback score.

## Dependencies

To run the project, you need to install the following Python libraries:

- `ipywidgets`
- `IPython`
- `pandas`

You can install these dependencies using `pip`:

```bash
pip install ipywidgets IPython pandas
