# Quiz practice

I built this for my own studying.

## Run

```bash
python3 -m http.server 8000
```

Open http://localhost:8000/quiz.html, then load a JSON file (or paste it).

## JSON

```json
{
  "title": "My exam review",
  "questions": [
    {
      "question": "What is 2 x 2?",
      "options": ["2", "4", "6", "8"],
      "answer": "B",
      "explanation": "Optional. Shown after you reveal."
    }
  ]
}
```

`answer` is the letter of the right option (`A`, `B`, `C`…). The exact option text also works. 2–8 options per question. `explanation` is optional. Use `` `backticks` `` for inline code and ` ``` ` fences for code blocks (write line breaks as `\n`).
