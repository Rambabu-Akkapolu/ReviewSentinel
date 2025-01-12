
<h1 id="top" align="center">Sentiment Analysis of Brand Reviews</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-1.2.0-brightgreen" alt="Streamlit">
  <img src="https://img.shields.io/badge/Pandas-1.3.3-yellow" alt="Pandas">
  <img src="https://img.shields.io/badge/TextBlob-0.15.3-orange" alt="TextBlob">
  <img src="https://img.shields.io/badge/Openpyxl-3.0.9-lightgrey" alt="Openpyxl">
  <img src="https://img.shields.io/badge/Cleantext-1.1.4-red" alt="Cleantext">
</p>

A web-based interface that analyzes customer reviews using TextBlob for sentiment classification (positive, negative, or neutral). Built with Streamlit, it supports real-time text analysis and batch processing via CSV uploads.

## Features

- Analyze individual text reviews for polarity and subjectivity.
- Clean text input using `cleantext`.
- Upload and analyze CSV files containing reviews.
- Download the analyzed CSV file with sentiment scores and analysis.

  ![ReviewSentinel-mockup](https://github.com/user-attachments/assets/850f4de8-7215-42ad-b2d8-9a171f63a94e)


## Real-World Applications

- **Customer Feedback Analysis**: Businesses can analyze customer reviews to understand their sentiments towards products or services, helping them improve customer satisfaction.
- **Market Research**: Companies can use sentiment analysis to gauge public opinion about their brand or competitors, aiding in strategic decision-making.
- **Product Improvement**: By analyzing reviews, businesses can identify common issues or areas for improvement in their products.
- **Brand Monitoring**: Sentiment analysis helps in monitoring brand reputation by analyzing social media posts, reviews, and other online content.
- **Customer Support**: Sentiment analysis can be used to prioritize customer support tickets based on the sentiment expressed, ensuring timely resolution of negative feedback.

## Output

### Polarity and Subjectivity

> **Polarity**: The polarity score ranges from -1 to 1.
> - A score closer to 1 indicates positive sentiment.
> - A score closer to -1 indicates negative sentiment.
> - A score around 0 indicates neutral sentiment.
>
> **Subjectivity**: The subjectivity score ranges from 0 to 1.
> - A score closer to 1 indicates subjective text (personal opinions, emotions, etc.).
> - A score closer to 0 indicates objective text (factual information).


https://github.com/user-attachments/assets/253fac49-7aff-407d-9ff4-bb7059d08b54




## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/rambabu-akkapolu/sentiment-analysis.git
   cd sentiment-analysis
2. Create a virtual environment:
   ```sh
    python -m venv venv
3. Activate the virtual environment:
   ```sh
    venv\Scripts\activate
4. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
5. Usage - Run the Streamlit app:
   ```sh
   streamlit run main.py


## 🙂 If you like this project, consider giving it a ⭐. 

[Back to Top⬆️](#top)
