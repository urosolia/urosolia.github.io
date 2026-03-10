---
layout: post
title:  "Producing High-Quality Work in the Era of GenAI"
date:   2026-3-10 11:30:25 -0700
categories: jekyll update
---

<div style="background-color: #f4f6f8; padding: 15px; border-left: 5px solid #0056b3; border-radius: 4px; margin-bottom: 20px;">
  <strong>TL;DR:</strong> GenAI has shifted the burden of effort from writers to readers. Polished, AI-generated documents mask shallow thinking, making it harder for overwhelmed reviewers to catch fundamental flaws. The result? Projects that look perfect on paper, but collapse at scale.
</div>
 
*"The present letter is a very long one, simply because I had no time to make it shorter". Blaise Pascal in his Provincial Letters (Letter XVI).*
{: style="text-align: justify"}

The above quote has always been one of my favorites. Short, organized documents require more effort than long, confused ones. Writing concisely is difficult; it requires editing, refining, and careful word choice to be clear and effective.
{: style="text-align: justify"}

In today’s GenAI world, I believe that the above quote must be a guiding principle for producing high-quality work. I use GenAI in my everyday life to write code, correct documents, brainstorm ideas, and much more. One fact is evident: LLMs love writing verbose documents. As a result, we are seeing a proliferation of long documents (and code) that have not even been reviewed by the person who “wrote” them. These documents are often unstructured and full of jargon. They read nicely, the flow is elegant, but the message is shallow. What could have been communicated in a few paragraphs is scattered across twenty pages.
{: style="text-align: justify"}

What is the problem with this proliferation? None, if you are reading a newspaper article or a novel. You can simply skip reading it if you do not find it enriching or entertaining. However, in professional settings, this proliferation is a problem. Nowadays, we see long documents and code prototypes with half-baked ideas being shared, often with a disclaimer that classifies them as “drafts”. These drafts are often poorly or partially reviewed. Hence, we find ourselves reading or reviewing material that has not been well-thought-out; it is simply the result of one or a few high-level LLM prompts.
{: style="text-align: justify"}

In this GenAI world, the effort has shifted from the writer to the reader. This means that managers and product leads will end up reviewing more documents and code. Their role as quality gatekeepers is more critical now than ever. This shift will significantly increase workloads, and it must change the way we operate. Before LLMs, we relied on guardrails to protect our time. For example, requiring a developer to write a design document forced them to think deeply and iterate on their ideas. It was easy to spot at a glance if a document was not well-written and the design was rushed. Today, this is hard: elegant AI-generated text masks shallow design, making quality control a more time-consuming task.
{: style="text-align: justify"}

This proliferation highlights how GenAI acts as an amplifier of existing work habits. High performers will use it to scale their high-quality output, while those who take shortcuts will outsource their effort, generating a higher volume of low-quality work. The consequence of this dynamic is severe: there is a higher chance that fundamental design flaws will pass through initial reviews undetected. As a result, we risk seeing a rise in software projects that appear perfectly sound during the prototyping stage, but ultimately collapse at scale due to shallow design.
{: style="text-align: justify"}

---

### Bonus Experiment: The AI Verbosity Test

To do a little experiment, I copied the above blog and gave it to Gemini with the following prompt: *“I need to write an essay, here the key ideas that I want to express. Write a full document with clear examples explaining my ideas.”* You can judge the result below. It is twice as long as the original without adding any new information. Ironically, if you skip to the end of it, Gemini suggests brainstorming how to add guardrails to mitigate the exact type of AI verbosity it just forced you to read.
{: style="text-align: justify"}

<details style="background-color: #f8f9fa; padding: 15px; border: 1px solid #dee2e6; border-radius: 4px; cursor: pointer;">
  <summary><strong>Click here to expand and read the AI-generated version</strong></summary>
    
### The Pascal Paradox: Producing High-Quality Work in the Era of GenAI 

*"The present letter is a very long one, simply because I had no time to make it shorter." — Blaise Pascal, Provincial Letters (Letter XVI)*

Blaise Pascal’s centuries-old observation remains one of the most profound truths about human communication: conciseness is a product of rigorous effort. Short, organized documents require editing, refining, and a highly deliberate choice of words to be clear and effective. It takes time to distill complex thoughts into their most potent form.

In today’s Generative AI (GenAI) world, Pascal’s quote must serve as a foundational guiding principle for producing high-quality work. We use Large Language Models (LLMs) daily to write code, brainstorm ideas, and draft documents. But a universal truth has quickly emerged: LLMs love to write long documents. As a result, the professional landscape is seeing a massive proliferation of lengthy, unreviewed text. These documents are often unstructured and padded with jargon. The prose reads beautifully, and the flow is elegant, but the underlying message is shallow. What should have been communicated in two clear paragraphs is now scattered across twenty pages.

If you are reading a novel or a blog post, this proliferation is harmless—you can simply stop reading if you are no longer entertained. However, in a professional setting, this avalanche of AI-generated text introduces a severe operational bottleneck.

**The Shifted Burden: From Writer to Reader**

Historically, the effort of communication rested on the writer. Today, in the GenAI world, the effort has shifted from the writer to the reader.

We are increasingly bombarded with long documents and code prototypes containing half-baked ideas, often shared with a casual disclaimer that they are "just drafts." Because these drafts take only seconds to generate via a high-level prompt, they are rarely reviewed deeply by the person sharing them. We find ourselves spending valuable time dissecting material that has not been fundamentally thought out.

Consequently, managers, technical leads, and product owners are forced to review a drastically higher volume of documents and code. Their role as quality gatekeepers is more critical—and more exhausting—than ever.

Consider this example in software engineering: Before LLMs, asking a developer to write a design document acted as a natural guardrail to protect the team's time. Staring at a blank page forced the developer to deeply think, structure their logic, and iterate on their architecture. If a developer rushed the design, it was obvious at a glance: the document would be sparse, poorly formatted, and clearly lacking substance. A reviewer could reject it in seconds.

Today, this dynamic has completely changed. A developer can prompt an LLM to "write a design document for a new microservice." The AI will instantly generate a polished, 10-page document complete with an executive summary, elegant section transitions, and industry-standard buzzwords like "synergistic scalable paradigms." However, buried beneath the beautiful prose, the actual database schema might be fundamentally flawed or missing altogether. Elegant AI-generated text masks shallow design, making quality control a much more time-consuming and deceptive task for the reviewer.

**GenAI as the Great Amplifier**

This proliferation highlights a broader truth: GenAI acts as an amplifier of existing work habits.

High performers—those who inherently value deep thinking and clear communication—will use AI to scale their high-quality output. They will use it to challenge their own ideas, quickly format their structured thoughts, and aggressively edit down their work.

Conversely, those who naturally take shortcuts will use AI to outsource their effort entirely. They will generate a higher volume of low-quality work, relying on the model's eloquence to cover for their lack of rigor.

**The Threat of the Collapsing Prototype**

The consequence of this dynamic is severe, particularly in technical fields. With AI masking shallow thought, there is a significantly higher chance that fundamental design flaws will pass through initial reviews undetected.

An example of this risk at scale: Imagine a startup team tasked with building a new customer data platform. Using GenAI, a developer quickly spins up a working prototype. The code looks standard, the documentation is incredibly thorough, and the user interface works perfectly during the demo. Because the code is lengthy and looks "professional," the lead engineer approves it after a surface-level review, exhausted by the volume of code they’ve had to read that week.

However, because the AI generated the architecture based on generalized boilerplate rather than deep, context-specific problem solving, it lacks crucial edge-case handling for race conditions. The project appears perfectly sound during the prototyping stage, but the moment it hits production and attempts to scale to thousands of concurrent users, the database locks up and the system collapses. The shallow design, previously hidden behind a wall of "good enough" generated code, becomes a catastrophic failure.

**Reclaiming Our Time and Quality**

To survive and thrive in the GenAI era, we must change the way we operate. If AI has broken our old guardrails, we must build new ones. We must demand that our teams channel Pascal: take the time to make it shorter. We should enforce strict length limits on design documents, require bulleted executive summaries that clearly state the core logic, and prioritize live, verbal defense of ideas over asynchronous reading.

GenAI is an incredible tool for assisting thought, but it is not a substitute for it. The true value of a professional no longer lies in their ability to produce words or code, but in their ability to refine, edit, and ensure that what is produced is structurally sound.

--------
Would you like me to adjust the tone of any specific section, or perhaps expand on the idea of how managers can implement new "guardrails" in this environment?  

  </details>
