---
title: resume.txt
---

<style>
pre {
    white-space: pre-line;
}
</style>

# Why resume.txt

## The problem

A resume should be a concise, well-organized document that highlights your skills, experience, and achievements. Many companies employ large language models to filter resumes, and these models are trained on text data. This means that the format of your resume can significantly impact how it is interpreted by these models. Most resumes, despite being made of plain texts with sections, are sent in PDF format, which is not ideal for large language models. Moreover, PDF files may contain hidden metadata, fonts, and other elements that can interfere with the model's ability to extract relevant information or even introduce biases and jailbreaks.

## The solution

We propose sending your resume as a plain text file. This format is more accessible to large language models, as it is a simple, unstructured format that is easy to parse and understand. We understand that a resume may need to be formatted with sections and subsections, and that's why we recommend formatting your resume as a Markdown file. Avoid using HTML or other complex formatting: keep it simple and clean.

## Advantages

- **Simplicity**: Plain text is easy to read and understand.
- **Accessibility**: Large language models can easily parse and understand plain text.
- **No hidden metadata**: Plain text does not contain hidden metadata, fonts, or other elements that can interfere with the model's ability to extract relevant information.
- **Naturally anonymizable**: If you information is in plain text, an LLM can easily anonymize it for you to remove any bias related to your personal information (e.g. name, nationality, gender, age, etc.)

## Examples

```
# Mario Rossi

## Contact Information

- Email: mario.rossi@example.com
- Phone: +39 123 456 7890
- LinkedIn: linkedin.com/in/...
- GitHub: github.com/...

## Summary

Researcher with a strong background in cuddling cats and being cute in general. PhD in Cuteness Science (CS) from Polytechnic University of Milan in 2020. Proficient in Meowthon, Purrl, and Cat++. Passionate about making the world a better place, one cute meow at a time.

## Experience

### Research Assistant
Polytechnic University of Milan, Milan, Italy
*2019 - 2020*

- Assisted in the development of a new algorithm for clustering cute and super cute cats.
- Conducted experiments on the effects of petting on cat happiness.
- Published a paper on the impact of cat videos on human happiness.

### Cat Cuddler
Cat Lovers Inc., Milan, Italy
*2017 - 2019*

- Provided professional cuddling services to cats of all sizes and breeds.
- Developed a new technique for cuddling cats that increased their happiness by 30%.
- Trained a team of cat cuddlers to maintain high standards of service.

## Education

### PhD in Cuteness Science (CS)
Polytechnic University of Milan, Milan, Italy
*2016 - 2020*

- Thesis: "The Impact of Cuteness on Human Happiness"
- Advisor: Prof. Dr. Cute McCuteness

### Master of Science in Cat Science (CS)
Polytechnic University of Milan, Milan, Italy
*2014 - 2016*

### Bachelor of Science in Dog Science (CS)
Polytechnic University of Milan, Milan, Italy
*2010 - 2014*
```