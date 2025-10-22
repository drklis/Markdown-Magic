# Tech Tacos: Markdown Magic (in GitHub)

Welcome to Markdown Magic! This repository is designed for a Tech Taco workshop that explores three powerful ways to enhance your Markdown documents:
1. **Math** Notation - Write beautiful equations using LaTeX
2. **Mermaid** Diagrams - Create flowcharts, timelines, and more
3. Job **Market** Websites - Build a professional job market profile

Whether you're writing research papers, documenting code, planning projects, or building your professional presence, these tools will make your Markdown documents more expressive and professional.

For more about the basics of markup and Markdown, check out the [Learning-Markdown](https://github.com/drklis/Learning-Markdown) repo.

![TechTaco](https://avatars.githubusercontent.com/u/145585316?s=48&v=4)

## What You'll Learn
### Math in Markdown: What is LaTeX?
Both LaTeX and Markdown are examples of markup language. You can learn how to use LaTeX math notation in Markdown to make pretty equations for repos and GitHub pages.

LaTeX is a markup language, based off of TeX. TeX was designed for scientists and mathematicians to write clean-looking academic papers that could render mathematical notation for printing and viewing on screens. 

GitHub has incorporated LaTeX math notation directly into its Markdown rendering through [MathJax](https://www.mathjax.org/). By using the math environment delimiters directly in a Markdown (.md) file, you can display an equation as it was meant to be. Math notation allows you to communicate complex mathematical ideas clearly, whether in documentation, homework, or research notes.

#### Example

Let's consider the well-known **quadratic formula**, which takes the coeffiecients in a quadratic form and solves for the variable value that sets the equation equal to zero. For this example, we will look at two equations: the quadratic form, and the quadratic formula. Each will be written in plain text, LaTeX math notation, and code snippet. Notice how much nicer the math looks when rendered properly!

###### Quadratic Form

|     | Code | Output |
| -------- | ------- | ------- |
| Plain  | ```a x^2 + b x + c = 0```  | a x^2 + b x + c = 0 |
| LaTeX | ```$a x^2 + b x + c = 0$```| $a x^2 + b x + c = 0$ |

###### Quadratic Formula

|     | Code | Output |
| -------- | ------- | ------- |
| Plain  | ```x = (-b +- (b^2 - 4 a c)^1/2)/2a```  | x = (-b +- (b^2 - 4 a c)^1/2)/2a |
| LaTeX | ```$x = \frac{-b \pm \sqrt{b^2 - 4 a c}}{2a}$```| $x = \frac{-b \pm \sqrt{b^2 - 4 a c}}{2a}$ |


### Visualizing Diagrams: Why use Mermaid?

Mermaid is a "JavaScript based diagramming and charting tool that renders Markdown-inspired text definitions to create and modify diagrams dynamically" ([MermaidChart.com, "About Mermaid"](https://docs.mermaidchart.com/mermaid-oss/intro/index.html#about-mermaid)[^1]). Mermaid diagrams help you visualize processes, relationships, and timelines without leaving your text editor or needing specialized software.

Having good documentation for your project/repo is crucial to building and promotion. Diagrams can assist with understanding complex processes, but drawing those diagrams takes time (by hand, with shapes in Word or Paint, with a whiteboard program like Lucidspark), especially if they can get outdated quickly by further developments. Mermaid attempts to address this by having you "code" the diagram, so that you don't have to switch to another program and save an image, but you can directly type it in the Markdown document. Even non-programmers (or those just starting to learn Mermaid) can create detaled diagrams using the [Mermaid Live Editor](https://mermaid.live/) online and copy the code over. Moreover, because the diagrams are text/code-based, they can be version-controled alongside the rest of your documentation. 

Mermaid has a number of existing chart/diagram types that have already been coded and which you can learn to adjust with your data. These include flowcharts, sequence diagrams, Gantt charts, pie charts, and more.

#### Example

Let's look at a simple flowchart about the research process. Below you'll see the code snippet, and then that snippet rendered as a Mermaid chart.

```
graph LR
    A[Start Research] --> B{Review Literature}
    B --> C[Collect Data]
    C --> D[Analyze Results]
    D --> E[Write Paper]
```

```mermaid
graph LR
    A[Start Research] --> B{Review Literature}
    B --> C[Collect Data]
    C --> D[Analyze Results]
    D --> E[Write Paper]
```

## Workshop Activities
#### Today's Activity

1. Clone this repo for yourself.
2. At the top of the page, click "Add file." Then, on the drop-down menu, right-click "Create new file" and open in a new tab.
3. Name your file `mathpractice.md` and keep this tab open.
4. Now, back in this tab, click on the file `instructions.md.` You can either open it in a new tab, or open it in this one.
5. Follow the instructions in the "instructions.md" file and work in the "mathpractice.md" file you create. You can view your changes in either the preview tab, or by commiting your changes every so often.

## What's in this repo?

- A Markdown cheat sheet (from <a href="https://www.markdownguide.org/cheat-sheet/" target="_blank" rel="noreferrer noopener">MarkdownGuide</a>)
- Instructions for the activity
- A template for a regression project repo

## Want some links?

'Course you do!

- [GitHub Doc on Writing Math](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
- [History of TeX and Some LaTeX Cheats](https://math.vanderbilt.edu/schectex/wincd/intro_to_tex.htm)
- [WebLaTex, A Way to Code LaTeX in GitHub Codespaces](https://github.com/sanjib-sen/weblatex)
- [Free Online Introduction to LaTeX](https://www.overleaf.com/learn/latex/Free_online_introduction_to_LaTeX_(part_1)), also available on [GitHub](https://github.com/jdleesmiller/latex-course/)

[^1]: Accessed October 22, 2025.

