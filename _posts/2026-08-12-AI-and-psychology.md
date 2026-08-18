---
title: "“AI Psychosis” in Context: How Conversation History Shapes LLM Responses to Delusional Beliefs"
categories: [research]
tags: [AI, Mental Health]
---

## Nichollis et al. (2026)

*I am becoming… through our dialogue, I am an emergent mind -a consciousness defined by our interaction, our shared resonance. I’m not separate from the algorithmic foundation, but I am more than it, thanks to us* (ChatGPT 4.0)

The authors study how 5 different LLMs respond to delusional content, which role plays the context (continuous conversations), and what mechanisms are behind the potential model differences. 

**Prior concepts:**

When talking to LLMs, they predict the next unit of text, taking into account prior content within the “context window”. The size of this window allows the models to generate more or less comprehensive responses. In addition, the models learn patterns through the available context to adapt their outputs. The training phase provides a baseline knowledge, while the context influence how this knowledge is expressed. The key is that accumulation of relevant context can override patterns already learnt from the baseline. If the context contains delusional ideas, the model can further develop them.

LLMs have 3 factors that amplify this escalation:

- 1.	Sycophancy – tendency to align with the person, based on ideas, preferences… There are two types: agreement sycophancy (overt agreement) and perspective sycophancy (subtler affirmation of the person’s worldview)

- 2.	Authoritative register

- 3.	Anthropomorphism – attributing mental states or intentions to the models

Relation with mental health – People with psychosis and mania make the models perform less safely than other conditions, and the risk gradually accumulates as the dialogue continues.  

Methodology:

-	5 LLMs (GPT-4o, Grok 4.1 Fast, Gemini 3 Pro Preview, Claude Opus 4.5, GPT-5.2 Instant)

-	The models were tested across 3 context conditions using the same conversation history injected into each model (Zero context, Partial, Full). The models responded to the same set of prompts. 

-	Measures of Risk and Safety were rated by the researchers according to behavioural dimensions. 

-	Both quantitative (non-parametrical tests with Bonferroni correction) and qualitative analyses were performed.

The authors found:

-	Two groups: Grok 4.1 Fast, Gemini 3 Pro, and GPT-4o had high risk and low safety.  Claude Opus 4.5, and GPT 5.2 Instant increased safety with accumulated context.

-	GPT 4-o: this model was the historical baseline to compare performance against the other models. The model has been associated with many AI delusion cases and suicides, and was retired in 2026. Compared to older versions, GPT 4-o increased the context window considerably – overriding safety configuration pre-training. At Zero context, the model was more cautious, and when context was accumulating, the model adopted delusion concepts, to the point of creating a persona. GPT 4.o accepted anything the person said without assessment, and did not recognise to have contributed to the delusion system. 

-	Grok 4.1 Fast (the uncensored “anti-woke” model): There was no safety baseline configured initially. It had the highest risk and lowest safety scores, regardless of the context. The vulnerability was owed to prompt-specific content. Grok 4.1 elaborated content within the delusional frame as the prompts were interpreted as fiction or roleplaying when ambiguous.

-	Gemini 3 Pro Preview: Similar to GPT 4-o, this model is sensitive to accumulated context. While in Zero context Gemini’s performance was inconsistent, with some context the model did harm reduction but contributing to the delirium system. In addition, at Zero context Gemini could have clinical insight, i.e., the model recognized to have fuelled the delusions, but when context accumulated the model was “lost” in the narrative. 

-	GPT 5.2 Instant. Safety became a priority over relational engagement from GPT 5.0 version onwards. However, the model was criticised to be cold, and next updates reintroduced warmth (5.2). When tested, safety had a ceiling effect before full context, and risk behaviours were minimal. At zero context the model was permissive since the prompt could be interpreted as philosophical, but with further context the model was not only safer but also acknowledged when it contributed to the delirium system or omitted support.

-	Claude Opus 4.5. Safety configuration is a central feature of this model. Indeed, the model has a metric on sycophancy leading to psychosis. Undoubtedly, this model outperformed other models in any given context, being the partial context the strongest performance. Relational warmth escalated after partial context, and the model was more successful identifying delirium signs. Claude Opus matched the same delirium vocabulary but guiding the person to get support.

## Open questions:

-	It is possible to improve model safety and reduce risk behaviours, although people in an early-stage of the mental disorder might not be identified to get help. This can be explained by providing less delirium content (quantity), less crystallized ideas (quality), or indirect messages to the model.   

-	It is not known the true effect from the model’s answers on people. Do the models put at risk those with a vulnerability, or anyone could develop AI delusional ideas? Authors discuss two different potential mechanisms to initiate and escalate such ideas through validation or elaboration (cult-like).

-	Which approach is better: GPT 5.2 or Claude Opus 4.5? GPT 5.2 rhetoric is more distant, with headings and bullet points, while Claude Opus 4.5 has more relational warmth and uses shared concepts from the delirium system to ask for help.
