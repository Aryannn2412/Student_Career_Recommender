# 🧠 Student Career Pathway Recommender (LLM + Prompting)

## 🎯 Goal
A conversational agent that recommends suitable career paths for students based on their:
- Interests
- Hobbies
- Academic strengths

## 💡 Tools Used
- Hugging Face Transformers (`phi-2`)
- Google Colab Notebook (inference + pipeline)
- Jinja2 templates for dynamic prompt formatting
- JSON for career mapping
- Python

## HOW TO RUN
- Download the zip folder from Google Drive or Github repo
- drive link - "https://drive.google.com/file/d/1jIjDMrrwi_HppB7ml8px7rFjoAiGIQOO/view?usp=share_link"
- Upload it in google colab runtime or connect with google drive(As per your preference make changes in directory)
- Use my ipynb file
- Re Run each cell and different input can also be used.

## SAMPLE INPUT
-Hi! I love painting and sketching. I enjoy biology and scored well in it. I’m not much into sports but I enjoy documentaries and designing digital art.

## SAMPLE OUTPUT
-{
  "Interests": "painting, sketching, biology",
  "Hobbies": "watching documentaries, designing digital art",
  "Academic strengths": "biology",
  "Suggested Careers": [
    "Medical Illustrator",
    "Biotech Communicator",
    "Graphic Designer"
  ]
}
## SUBMISSION
- This Repo
-Google drive(consists colab file)
