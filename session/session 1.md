# Session 1

> 对应 preview
>
> 大作业：给定一个 dataset --> training --> checking 



## NLP Introduction

* NLP Classification ( partial )
  * text categorization
  * part-of-speech tagging ( POS )
  * named entity recognition ( NER )
    * entity：实体
  * question answering ( QA )
    * 商用价值较高，研究
  * machine translation
  * NLU ( U : Understanding )



## Knowledge

### Activation Function


$$
\begin{split}
&Sigmoid:\\
&&\sigma(x) = 1/(1 + e^{-x})
\\

&tanh:\\
&&tanh(x) = 2\sigma(x) -1
\\

&ReLU:\\
&&\begin{equation}
f(x) = \begin{cases}
0, & \text{if } x > 0; \\
x, & \text{if } x < 0.
\end{cases}
\end{equation}
\\

&Leaky \quad ReLU:\\
&&f(x)= (ax) (x<0)\\
&&f(x)=  (x) (x>=0)

&&\begin{equation}
f(x) = \begin{cases}
ax, & \text{if } x < 0; \\
x, & \text{if } x < 0.
\end{cases}
\end{equation}
\\
\end{split}
$$


























