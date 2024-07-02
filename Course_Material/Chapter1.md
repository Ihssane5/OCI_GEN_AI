
# 1️⃣ Introduction to LLM 
<link rel="stylesheet" href="../css/style.css">
In this chapter we will dive into <u class="underline">the world of llm</u> starting by its definition, exploring  some of <u class = "underline">prompting techniques</u> then we will learn about the <u class="underline" >issues of prompting</u>
and  <u class="underline">the training and its techniques</u> as a solution and finally  we will talk about  some related concept such as <u class="underline">decoding</u>,<u class="underline">hallucination</u> and finally <u class="underline">groundness and Attributability</u>.

## LLM definition 
LLM stands for large language model and what i want you to keep in mind the meaning of  these three words:

![Alt text](../images/Llm.png)<br>
<u class="underline">
Large language models</u> are models that can understand and generate text using a probability distribution of words. It's fair if you wonder what a model is in the first place. We can compare a model to a representation or a schema. This model has some weights or parameters<sup id="fnref1"><a href="#fn1"> 1 </a></sup>, and our goal in this exciting journey is to find the best weights that our model can have<sup id="fnref2"><a href="#fn2"> 2 </a></sup>. This representation relies solely on the distribution of words.
let's try to illustrate this:

![Alt text](../images/proba_dist.jpg)<br>
 the llm calculates the probability of appearance of each word present in its vocabulary and based on this distribution it gain some kind of understanding of the semantic meaning of texts, for example our model assigned a probability of O.4 and 0.3 to dog and cat respectively, with each new word we try to predict the model will calculate and assign a new probability distribution over its vocabulary.
 
![Alt text](../images/proba_dist_small.png)<br>

we can see clearly that the probability distribution of our model changed when we added the word small. You may notice that small animals gets higher probabilities than before, which mean they are more likely to be the suitable ones.

At this stage you may notice that all the power of a llm is hidden within those distributions.
If we can control them, change them the way we want,we ultimately end up with what we want.

🤔💭 how can we change the probability  distribution over an llm vocabulary ❓
there two ways we can change the distribution:
- prompting
- training

in the next part we will discover what is prompting, its strategies and finally its
limitations.





## Prompt Engineering and its Strategies

## Prompt Engineering's Issues

## Important Concept 








<ol>
    <li id="fn1">Weights or parameters are the values that the model adjusts during training to minimize error and improve accuracy. It has billions of them, which makes it a large model. <a href="#fnref1">↩</a></li>
    <li id="fn2">The best weights are those that allow the model to make the most accurate predictions or generate the most coherent text. For more details, check the architecture of large language models (LLM). <a href="#fnref2">↩</a></li>
</ol>