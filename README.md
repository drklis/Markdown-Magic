# Tech Tacos: Using Math in Markdown (in GitHub)

Both LaTeX and Markdown are examples of markup language. Today, we'll be learning how to use LaTeX math notation in Markdown to make pretty equations for repos and GitHub pages.

For more about markup and Markdown, check out the [Learning-Markdown](https://github.com/drklis/Learning-Markdown) repo.

![TechTaco](https://avatars.githubusercontent.com/u/145585316?s=48&v=4)

## What is LaTeX?

LaTeX is a markup language, based off of TeX. TeX was designed for scientists and mathematicians to write clean-looking academic papers that could render mathematical notation for printing and viewing on screens. 

GitHub has incorporated LaTeX math notation directly into its Markdown rendering through [MathJax](https://www.mathjax.org/). By using the math environment delimiters directly in a Markdown (.md) file, you can display an equation as it was meant to be.

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

