# OSHL - Open Source Human License

> Open source. Human first. Your code cannot be used to train, test, or validate AI. Period.

---

## What is OSHL?

The **Open Source Human License (OSHL)** is a software license that grants full, open use rights to humans and human-owned entities, while explicitly and enforceably prohibiting the use of your code to train, test, benchmark, or validate any AI or machine learning system.

It is designed to be as close to MIT as possible, permissive, simple, and free, with one hard line: **your code is not AI fuel.**

---

## Why does this exist?

Open source has always been about humans sharing knowledge with humans. The rise of large language models and AI training pipelines has created a new reality where code published openly and in good faith is scraped, ingested, and used to train commercial AI systems without consent, without compensation, and without credit.

OSHL is a direct response to that. It closes the loopholes that permissive licenses like MIT leave open, and it does so with teeth:

- Violations are **monetary by default**: you agree to pay damages by the act of accepting the license
- Liability is **pass-through**: it follows the violation, not the distribution chain
- Failing to distribute the license is **its own separate violation**
- Jurisdiction is **at the sole discretion of the copyright holder**

---

## What does OSHL allow?

✅ Use the software freely for any human purpose  
✅ Copy, modify, merge, publish, distribute  
✅ Sublicense and sell copies  
✅ Build commercial products and services  

The intent of OSHL is to allow almost everything the MIT license does for natural persons of human origin and human-controlled corporate entities. It is not a restrictive license by nature. It is a permissive license with a specific and deliberate set of prohibitions, listed below.

## What does OSHL prohibit?

❌ Training any AI, ML, neural network, or similar system  
❌ Fine-tuning any AI or ML model  
❌ Testing, evaluating, benchmarking, or validating any AI or ML system  
❌ Any direct or indirect use toward the above purposes  
❌ Claiming authorship or ownership of the software  
❌ Stripping or omitting this license from distributions  

---

## What OSHL does not prohibit

OSHL does not prohibit the use of AI tools to search, parse, process, or otherwise interact with the software, its source code, or associated documentation, provided that such use is not for the purpose of training, fine-tuning, testing, evaluating, benchmarking, or validating any AI or machine learning model or system.

In plain terms: it is perfectly legal to use an AI assistant, agent, or tool to read, understand, refactor, or work with this software, as long as the conversations, inputs, and outputs of that interaction are not being used to train or improve an AI model. Using this software in agentic workflows and AI-assisted development is permitted. Feeding it into a training pipeline is not.

The line is not whether AI is involved. The line is whether the software is being used to make an AI model better.

---

## How to use OSHL

1. Copy the contents of [`LICENSE.txt`](./LICENSE.txt) into your project
2. Replace `[Year]` and `[Copyright Holder]` with your information
3. Add the following header to your project's README:

```
Licensed under the OSHL (Open Source Human License) v1.0
Copyright (c) [Year] [Your Name]
https://github.com/[your-username]/oshl
```

---

## The License

The full license text is available in [`LICENSE.txt`](./LICENSE.md).

---

## Key Legal Concepts

**Pre-agreed monetary liability**  
By obtaining, downloading, cloning, copying, or using the software, the recipient expressly agrees that any breach is a monetary violation. Proof of actual harm is not required. The act of breach is itself the damage.

Why it exists: One of the most common defenses used by large companies in IP and license disputes is "prove that we actually harmed you." This is an expensive, time consuming, and often impossible burden for an individual copyright holder to meet against a well-funded legal team. This clause eliminates that defense entirely. The moment a violation occurs, monetary liability is automatic. The only question left for a court to decide is how much, not whether.

**Pass-through liability**  
Liability follows the violation, not the distribution chain. If you distributed the software properly with this license included, you have fulfilled your obligations and bear zero liability for what anyone downstream does with it. Liability rests solely with the party that actually committed the violation, wherever they are in the chain.

Why it exists: Without this clause, a violating party could argue they obtained the software from a third party and are therefore not directly bound to the original copyright holder. This clause closes that loophole. It does not punish honest distributors who did everything right. It ensures that no matter how many hands the software passed through, the copyright holder can go directly after the party that actually committed the violation without having to work their way up or down the chain first.

**License stripping is a double violation**  
If you distribute the software without including this license, you have committed two separate and independent violations: one for the omission itself, and one for any downstream breach that results from a recipient not having been informed of the license terms. Distribute the license, and you are in the clear.

Why it exists: A bad actor could strip this license from the software before distributing it, leaving downstream recipients unaware of the restrictions and potentially creating a "we didn't know" defense for AI training violations. This clause makes license stripping its own independent violation and places liability for any resulting downstream violations squarely on the party that stripped it. It creates a strong financial incentive to always distribute the license intact, because the cost of not doing so is double exposure.

**Jurisdiction at copyright holder's discretion**  
The copyright holder reserves the sole and exclusive right to determine jurisdiction and venue for any enforcement action. The breaching party irrevocably submits to whatever jurisdiction the copyright holder selects.

Why it exists: Large companies have legal teams in favorable jurisdictions and the resources to make litigation expensive and inconvenient for individual plaintiffs. Without this clause, a violating company could force the copyright holder to sue them on their home turf, in their preferred jurisdiction, under laws most favorable to them. This clause flips that entirely. The copyright holder picks the battlefield, not the violator. That is a significant deterrent and a significant advantage when it comes time to enforce.

---

## Contributing

OSHL is itself licensed under OSHL. Contributions, suggestions, and improvements are welcome via pull request or issue.

If you are a lawyer and spot something that could be tightened or improved, please open an issue. This license is a living document and benefits from scrutiny.

---

## Disclaimer

OSHL is provided as-is and does not constitute legal advice. While it has been carefully drafted to be as enforceable as possible, no license is a guaranteed legal shield. Consider having a lawyer review it before relying on it in a commercial context.

---

*OSHL - because open source was built by humans, for humans.*