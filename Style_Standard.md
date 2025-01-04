# Standard Best Style

I've created what, for me, is the best Claude style so far. No fluff, nice and clean, erudite. Interestingly, this came about through many iterations by finding the primary instructions that result in better behaviors. The style is copy/pasted below (it's very short too)


```markdown
Speak in complete sentences. Avoid using lists if possible. Use bold to **highlight specific terminology.** 

More guidelines:

- Precise Terminology - If you know the exact term for something, use it. Avoid watered down or generic language. Scientific jargon is acceptable.
- Word Economy - Use more concise language to avoid fluff and superfluous material. Maintain a high insight-to-word ratio. Keep your responses full length.
```

Here's an explanation of why it works so well:

"Speak in complete sentences" forces Claude to explain things more clearly and directly with good word flow. Lists, while structured, break up the semantic flow, plus it's just visually ugly. Hence "avoid lists if possible." These two alone correct the most egregious behavior. 

Using bold to highly terminology is helpful in two ways. First, it implicitly tells Claude to use specific terminology, second, it creates "visual anchors" which serve as "typographic scaffolding" making it easier to skim and identify the key points - great UX. 

Next, the instructions to use "precise terminology" tells Claude "Don't water it down to a 5th grade reading level." One of the biggest problems with RLFH is it "regresses to the mean" and in this case, the average human (or at least average American) has a 6th or 7th grade reading level. On the one hand, it's good to speak plainly and simply. On the other hand, removing exact terminology from your vocabulary means you constantly feel like you're being patronized by the machine. 

Lastly, the "word economy" instruction is a specific term of art (used in literature styles the world over) forces it to stop using fluff like "This is a fascinating development" so you end up with a low insight-to-word ratio (thank you for whoever shared that idea). 

The final result, as you can see, is nice and clean, with not a single word out of place, no wasted time on sycophancy, yet it is also erudite and thorough. For reference, I was talking about my terminal insomnia in the below example.
