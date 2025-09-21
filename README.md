# Food_Recommendation-Chatbot
FOXO Health AI Coach
This is a simple chatbot I built for the Confluentia Hackathon. It's a friendly guide that helps you figure out what food is good or bad for different health conditions, and it runs entirely in a Google Colab notebook.

What's the problem this solves?
Trying to figure out what you can and can't eat when you have a health condition like Diabetes or Hypertension is tough. You usually get a long, confusing list of foods, but that doesn't help when you're at the store and just want to know if a banana is a good idea. Getting a quick, simple answer to everyday food questions is harder than it should be.

How this project helps
I built the Health AI Coach to fix this. It's an interactive chatbot that gives you clear, easy-to-understand food advice for your specific health needs.

Instead of just giving you another list, the coach talks you through it. You tell it your health goal, ask about a food, and it explains everything step-by-step in a conversation. It doesn't just give you a one-word answer; it explains why a food is good or bad, which biomarker it affects, and offers recommendations.

The whole experience feels like a natural chat. What's cool is that the entire thing is self-contained. I wrote a script that creates the food database from scratch every time you run it, so you don't need to upload any files. When the bot gives you an answer, it sends a few messages one after another to make it easy to follow along. The advice is based on a clear set of rules, so it's always consistent.

A little about the tech
I built this using Python and Pandas to handle all the data in the background. The chat you see is made with ipywidgets, HTML, and Tailwind CSS, all running inside a Google Colab notebook.

What's next for this project?
This is just the start. I'd love to add information for a lot more health conditions and different types of diets, like vegan or gluten-free. It would also be great to let people save their health goals so they don't have to pick them every time. Eventually, I want to make the coach available in more languages to help even more people make better food choices.
