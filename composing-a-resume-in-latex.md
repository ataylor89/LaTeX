# Composing a resume in LaTeX

Hi everyone. Good afternoon.

Last night, it occurred to me that I could start writing my resumes in LaTeX.

I might be arriving a bit late to the game, because I think that a lot of people already do this :)

Sometimes I arrive early -- sometimes I arrive late. C'est la vie.

Back to the main topic: I created a sample resume in LaTeX and uploaded it to my Github account.

You can find the repository here: [https://github.com/ataylor89/LaTeX](https://github.com/ataylor89/LaTeX).

You can find the TeX file here: [https://github.com/ataylor89/LaTeX/blob/main/sample-resume.tex](https://github.com/ataylor89/LaTeX/blob/main/sample-resume.tex).

You can find the PDF file that I generated (using the pdflatex compiler that I downloaded from tug.org) here: [https://github.com/ataylor89/LaTeX/blob/main/sample-resume.pdf](https://github.com/ataylor89/LaTeX/blob/main/sample-resume.pdf).

I would like to admit that I did not even know about the pdflatex compiler before today.

(Perhaps I used it in high school, but I forget things every now and then.)

Previously, I was using the Art of Problem Solving's [TeXeR utility](https://artofproblemsolving.com/texer) to compile LaTeX code.

It so happens that if you copy/paste the contents of sample-resume.tex into the Art of Problem Solving TeXeR utility, it is able to compile nicely, and it renders a flawless PDF.

This is good. This is what we want.

We call this cross-compatibility.

(My TeX file is cross compatible with pdflatex and the AoPS TeXeR utility.)

Now I think it's important to briefly discuss the different LaTeX options that are available for download or use.

You can download the LaTeX compiler (plus a lot of side stuff) by downloading and installing the MacTeX package on tug.org.

Unfortunately, MacTeX takes up 6.4GB of space on your hard drive.

For this reason, I opted for the BasicTeX package, which only takes up 134MB of space on my hard drive.

The pdflatex compiler comes with both MacTeX and BasicTeX.

I am able to compile my LaTeX code with the command

    pdflatex sample-resume.tex

I can also specify an output directory with the command

    pdflatex -output-directory=build sample-resume.tex

Here are the commands in Terminal.

    % cd ~/Github/latex
    % mkdir build
    % ls
    build			sample-resume.tex
    % pdflatex -output-directory=build sample-resume.tex
    % ls build
    sample-resume.aux	sample-resume.log	sample-resume.pdf
    % mv build/sample-resume.pdf .
    % ls
    build			sample-resume.pdf	sample-resume.tex

I wanted to show the commands that I used in Terminal, to make these instructions as clear as possible.

Now, let's talk a little bit about LaTeX before I conclude this post.

LaTeX is a markup language that is commonly used in the field of mathematics.

It's kind of like the gold standard for mathematics, as far as markup languages go.

(In the same way that HTML is the gold standard for websites, LaTeX is the gold standard for mathematics.)

But LaTeX can also be used to compose a resume.

In fact, I think that a lot of mathematicians compose their resumes in LaTeX.

That being said, HTML can also be used to compose a resume. So can Markdown. Markdown is another popular markup language.

But how do you convert an .html file into a PDF? How do you convert an .md file into a PDF?

(I concede that it's possible, but it's not quite as easy.)

The LaTeX package that I downloaded from tug.org makes it easy to convert a TeX file into a PDF.

This is one of many reasons that LaTeX is great for writing resumes (as well as mathematical documents).

Another reason is the language itself. LaTeX offers a rich array of features for writing mathematical documents or general documents.

It is easy to write the quadratic formula in LaTeX. (You can try it using the Art of Problem Solving [TeXeR utility](https://artofproblemsolving.com/texer).)

It is possible to write the quadratic formula in HTML... but the formatting is more difficult than it is in LaTeX.

In summary, LaTeX, HTML, and Markdown are three popular markup languages.

A markup language is a language that helps us write a formatted document.

Resumes fall under this category (formatted documents) so LaTeX is a great choice.

I wanted to write a brief post on how we can use LaTeX to compose a resume.

You can find a sample resume that I composed in LaTeX on my Github: [https://github.com/ataylor89/LaTeX](https://github.com/ataylor89/LaTeX).

Having said all of this, I think we have reached a good stopping point :)

Whenever I say, "we have reached a good stopping point," it's kind of like flipping a coin, because sometimes I actually bring my post to a conclusion (heads), but other times I prolong my post by entering some digression (tails).

Shall the coin land on heads, or tails?

I think it will land on heads :)

We have indeed reached a good stopping point, and I have things to do -- I have to go about my day.

I wish everyone a nice weekend. TGIF. TGIF to infinity. :)

Thanks for reading,  
Andrew
