# ServiceNow Exit Decision

**Date:** 2026-08-22  
**Decision:** Exit the ServiceNow starter position. Keep SAP, Salesforce and UiPath. Palantir remains a separate candidate because the company fits the architecture extremely well, but the valuation deserves its own decision.

## Why I bought ServiceNow in the first place

The original AI Deployment thesis was simple: model capability can improve much faster than companies can turn that capability into real economic work.

Between a capable model and an actual business outcome sit data, context, permissions, integrations, workflows, evaluation, governance and execution.

**Capability → Discovery → Deployment → Execution → Outcome**

That made ServiceNow look like one of the cleanest ways to own the bottleneck. It already sits inside real enterprise workflows. It knows about incidents, approvals, responsibilities, business rules and operational processes. If AI moves from answering questions to taking actions, the obvious conclusion is that systems which already coordinate those actions should become more valuable.

I still think that logic is broadly right.

The reason for selling is not that ServiceNow suddenly became a bad company. The reason is that I no longer think it is the best expression of the thesis relative to the alternatives.

## What changed

The important change came from looking at ServiceNow together with Palantir and, especially, Microsoft.

ServiceNow is trying to move upward from workflow software into something much broader: enterprise context, agent governance, orchestration and execution. Products like Workflow Data Fabric, Context Engine, AI Control Tower and Action Fabric all point in that direction.

That initially looked like confirmation of the thesis.

The problem is that Microsoft is attacking the same layer from a much deeper position.

Microsoft already owns identity through Entra, cloud infrastructure through Azure, enterprise productivity through Microsoft 365, a large part of enterprise data infrastructure through Fabric and OneLake, developer infrastructure, security products and one of the strongest enterprise distribution networks in the world.

It is now extending that stack into the control plane for agents.

Entra Agent ID gives agents identity, authentication, authorization, lifecycle management and auditability. Agent 365 is meant to become a control layer for enterprise agents. Fabric IQ adds semantic and ontology-like structure on top of enterprise data.

The long-term competition therefore no longer looks like:

**ServiceNow vs. other workflow software**

It increasingly looks like:

**ServiceNow vs. an integrated identity + data + semantics + agent + compute control plane**

That is a much harder fight.

## Why this matters economically

The strongest ServiceNow future is easy to imagine.

An agent understands a situation, ServiceNow supplies organizational context, permissions and workflow logic, and ServiceNow executes the action. In that world ServiceNow becomes one of the operating layers through which enterprise agents work.

That future is still possible.

But there is now another plausible architecture:

**Microsoft owns identity**  
**Microsoft owns the agent**  
**Microsoft owns much of the data and context**  
**Microsoft owns the user relationship**  
**ServiceNow receives an API call and executes the action**

ServiceNow is still useful in that world. It may even continue growing.

But usefulness is not the same thing as owning the highest-value part of the stack.

The strategic value could move upward toward the layer that understands the organization, controls the agent fleet and decides what should happen.

That is the key update.

The risk is not that ServiceNow disappears. The risk is that part of the layer I originally treated as structurally scarce becomes bundled into infrastructure customers already own.

## Action Fabric is both smart and revealing

Opening ServiceNow actions to external agents is probably the correct strategy. ServiceNow does not need to win the model war if every model still needs ServiceNow when it wants to do something inside an enterprise.

But that same strategy makes the lower-value equilibrium visible.

If Claude, Copilot or another agent owns reasoning, context and the user relationship while ServiceNow mainly provides governed execution underneath, ServiceNow remains important but may capture less of the total AI surplus than I originally assumed.

That does not make the business bad. It changes the expected economics of the thesis.

## This is a relative sell, not a broken-thesis sell

I am not treating this as a kill-condition exit.

ServiceNow is executing well. Its workflow estate is deeply embedded. Switching costs are real. AI adoption is real. The company could absolutely prove this sale wrong by becoming the independent control plane for enterprise agents.

The decision is narrower:

**Given the same dollar of capital, is ServiceNow still one of my preferred ways to own the AI transition?**

My answer is now no.

The original basket was exploratory. The point was to buy several architectures around the same bottleneck and then update the weights as the structure became clearer.

The architecture is now clearer than when I entered.

## Why I am keeping SAP

SAP owns something that remains valuable across a much wider set of AI outcomes: real transactional state.

Orders exist in SAP. Inventory exists in SAP. Invoices exist in SAP. Procurement, manufacturing, finance and supply-chain processes exist in SAP.

An AI layer can change how this information is queried, interpreted or acted on. Palantir can build an ontology above it. Microsoft can build agents that reason over it. ServiceNow can coordinate workflows around it.

None of that removes the need for a trusted record of what actually happened.

This fits the broader scarcity thesis: if intelligence becomes cheaper, trustworthy state can become relatively more valuable.

SAP therefore has a strong fallback position.

If SAP succeeds in moving upward into AI, it captures additional value. If another company wins the reasoning and orchestration layer, SAP can still remain a critical system underneath it.

The main risk is not obsolescence. It is value capture: SAP could remain indispensable while someone else captures more of the AI surplus above it.

I prefer that risk to betting that a standalone orchestration layer will remain permanently scarce.

## Why I am keeping Salesforce

Salesforce has the same structural advantage in a narrower domain.

It owns customer state.

Accounts, opportunities, sales history, service interactions, customer relationships and commercial workflows already live there.

If AI automates more sales and service work, these records become inputs into the agents doing that work.

Salesforce does not need to become the universal operating system for enterprise AI. It only needs to remain one of the primary systems representing the relationship between a company and its customers.

The open question is monetization.

Agentforce can grow quickly without creating much incremental value if customers simply move existing Salesforce spend into a new product category.

The chain I care about is:

**Agentforce adoption → more useful work performed on Salesforce → higher customer spend or retention → stronger organic growth → more cash flow**

That is not yet fully proven, which is why I am keeping Salesforce as a starter position rather than treating it as a finished thesis.

But even if Microsoft becomes the dominant agent control plane, Microsoft agents may still need Salesforce data.

That gives Salesforce a clearer asset underneath the contested layer.

## Why I am keeping UiPath

UiPath initially looked like the company I should be most worried about.

It comes from RPA, and increasingly capable AI clearly threatens parts of classical RPA. A model that understands a screen and can reason about a task does not need a human to manually encode every click.

But that confuses UiPath's old method with the underlying economic job.

The old method is vulnerable.

The job is not.

Companies still need software to reliably execute work across APIs, browsers, legacy applications, robots, humans and systems that were never designed to work together.

UiPath already owns infrastructure around that execution problem: robots, integrations, orchestration, queues, monitoring, governance and a large installed automation base.

The real question is whether it can transform that infrastructure from:

**human-designed RPA**

into:

**AI-generated and AI-orchestrated execution**

That is what makes Maestro important.

If AI can generate workflows, discover processes, handle exceptions and coordinate robots, agents and humans, the technology threatening classical RPA could also make UiPath dramatically more scalable.

The threat can become the mechanism of industrialization.

This is why I am keeping the position.

The thesis is not that RPA remains untouched. The thesis is that UiPath can reuse twenty years of enterprise execution infrastructure as the control and execution layer underneath a more intelligent system.

If that transition fails, the thesis breaks.

If it succeeds, the rerating could be substantial because the market still partly sees UiPath through the lens of an older automation category.

UiPath also has enough cash, cash flow, customers and installed infrastructure to attempt the transition without needing to build its own frontier model. It can use external models and spend its own resources on orchestration, process discovery, computer use, evaluation, governance, integrations and vertical agents.

That is a risk I am willing to keep.

## Where Palantir fits

Palantir is what forced me to think more clearly about the architecture.

Its ontology approach is unusually close to a state-first model of enterprise AI.

Instead of beginning with an interface or a workflow, the goal is to create a structured operational representation of the organization and let humans and agents reason and act on top of it.

That is probably the cleanest architectural fit with the broader thesis.

But Palantir also exposed the real competitive question.

Microsoft Fabric IQ now includes ontology-like structure. Microsoft is explicitly trying to build shared organizational context and an enterprise agent control plane.

This does not prove Palantir is wrong. If anything, it validates the importance of the architecture.

It does mean that ontology, context and orchestration cannot simply be assumed to remain standalone monopoly layers.

Palantir still has an advantage in difficult real-world deployment, operational depth and accumulated experience from complex environments.

Its problem as an investment is different: expectations are already extremely high.

I therefore do not want to fund the ServiceNow exit by automatically moving the entire position into Palantir.

Palantir should be treated as a separate valuation decision.

## The deeper change in the deployment thesis

The biggest update is not actually about ServiceNow.

It is about deployment itself.

My original assumption was that as AI capability grows, deployment becomes the bottleneck and the companies controlling that bottleneck become more valuable.

I still believe that.

But I was too close to treating today's deployment layer as permanently scarce.

AI itself can automate deployment.

It can write integrations, map schemas, build pipelines, create workflows, test applications and discover possible use cases.

Deployment capacity can therefore expand very quickly too.

The important question becomes whether demand for deployment grows faster than the cost of producing deployment falls.

If reducing deployment cost turns ten economically viable AI use cases into ten thousand, deployment companies can still become enormous even while the work becomes easier.

If instead deployment becomes easy enough that most of the economic surplus flows back toward the companies owning the underlying data, identity, compute and transactional state, then the standalone orchestration layer becomes less attractive.

That second scenario favors companies such as SAP and Salesforce and favors hyperscalers such as Microsoft.

It is less obviously favorable to ServiceNow.

That is the main reason for the position change.

## Microsoft is now the main adversarial variable

I originally treated Microsoft mostly as an AI beneficiary through Azure, Microsoft 365, Copilot and enterprise distribution.

That is no longer enough.

Microsoft belongs directly inside the competitive analysis for deployment and orchestration.

Its stack increasingly looks like:

**Entra → identity and permissions**  
**OneLake / Fabric → enterprise data**  
**Fabric IQ → semantic and operational state**  
**Copilot / Foundry → models and agents**  
**Agent 365 → control and governance**  
**Azure → compute**

This does not guarantee Microsoft wins.

Large enterprises remain heterogeneous. They use SAP, Salesforce, ServiceNow, Oracle, Snowflake, Databricks, custom software and old infrastructure at the same time. A neutral cross-system platform can still create enormous value.

But Microsoft has enough existing control points that every standalone enterprise AI platform now has to be analyzed against the possibility of bundling.

That is now a permanent part of the thesis.

## What would make me buy ServiceNow again

Selling ServiceNow does not mean permanently rejecting the company.

I would reconsider if ServiceNow proves it is becoming a genuinely independent control layer rather than mainly a powerful system of action.

The strongest evidence would be external agents increasingly using ServiceNow while ServiceNow still captures significant incremental economics from those workloads.

I would also reconsider if AI Control Tower becomes a standard governance layer across Microsoft, AWS, Google, Palantir and internally built agents instead of mainly governing ServiceNow workloads.

Another positive signal would be evidence that Context Engine and Workflow Data Fabric create a business-state layer customers treat as strategically separate from hyperscaler infrastructure.

And valuation matters.

A sufficiently large fall in expectations can turn an uncertain thesis into an attractive stock even if the competitive risk remains.

The sale is therefore not:

**ServiceNow will lose.**

It is:

**At the current point in my research, ServiceNow no longer offers the best combination of structural protection, upside and uncertainty among the companies expressing this thesis.**

That is enough.

## Portfolio conclusion

The original basket did its job.

It gave me exposure to the deployment thesis before I understood exactly how the industry might separate into layers.

Now I have a clearer map.

I am exiting ServiceNow.

I am keeping SAP because ownership of core transactional state remains valuable across a wide range of AI outcomes.

I am keeping Salesforce because customer state and distribution remain strategically useful even if another platform owns agent orchestration.

I am keeping UiPath because its old RPA method is vulnerable, but its execution infrastructure gives it a credible path toward becoming an agentic orchestration layer, and the market does not already price that transition as guaranteed.

Palantir remains one of the strongest architectural fits I have found, but its valuation means it should be evaluated separately rather than treated as an automatic replacement for ServiceNow.

The deployment thesis survives.

The portfolio changes because the thesis has become more precise.

The question is no longer simply:

**Who helps companies deploy AI?**

It is:

**Which parts of deployment remain scarce after AI begins automating deployment itself, and which companies actually own those scarce parts?**

My current answer is that underlying state, identity, real execution and deeply embedded operational context are safer assets than assuming a standalone workflow control layer will permanently command the same pricing power.

That is why I am selling ServiceNow while keeping the rest of the basket.
