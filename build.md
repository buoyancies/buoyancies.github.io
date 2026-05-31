# Bespoke education software

**Building interactive learning experiences is my specialty.**

I have a pretty comprehensive track record in making technologies learnable. I can help you create self-directed developer learning supports for your software or team goals. 

<div class="ytembed">
<iframe src="https://www.youtube.com/embed/BJZ3niThD2s?si=DMjFFgwnKPGDC3_m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

I typically aim to provide teams with the ability to continue authoring their own bespoke experiences. For that reason I've tended to build **extensible frameworks** for learning, with a foundation of material designed to get you started, delivered in context as learners engage with your tech.

My golden rule is to find opportunities to use learning experiences across settings. At both Postman and Fastly, I built a core set of self-directed learning projects, teaming up with colleagues in product, sales, marketing, and partner development to support their programs, while capturing feedback that improved product flows for users.

Some highlights of what I've built:

* [Glitch for learning](#glitch-for-learning)
* [Postman learning framework](#postman-learning-framework)
* [Language models for learning](#language-models-for-learning)

<h2 id="glitch-for-learning"> Glitch for learning</h2>

![glitch starters](glitchstarters.png)

I created more Glitch apps for teaching developer skills than I can remember, after using the platform for several years at other companies. As Developer Experience Lead, I was responsible for the "Hello" starter projects, aimed at helping users learn web frameworks. These apps were designed specifically to support learning, exposing interactive content in the project documentation and app previews.

Exploring the **product metrics** shortly after I joined, I discovered that users who made a first edit soon after remixing a project were significantly more likely to continue engaging over the longer term. Based on that, I added suggested first edits to the primary starter apps, and contributed a change to the editor that enabled navigating to source code locations on clicking in the preview pane.

![glitch framework](glitchframework.jpg)

> 🎬 [My devrelcon talk in 2023](https://developerrelations.com/talks/an-open-framework-for-developer-learning/g) introduced an extensible framework I built for automated exercises.

When Glitch joined Fastly, I worked **across teams** to figure out how best to leverage Glitch for Fastly product onboarding, as part of our wider integration efforts. I was able to develop Glitch projects to support a variety of company goals including customer, community developer, and employee enablement.

Fastly is an internet infrastructure company, that gave me an opportunity to revisit web fundamentals in my teaching, with Glitch getting learners hands-on while immersed in the basics of how the web works.

<table>
<tr>
<td>
[![edge compute learning](splitedge.png)](splitedge.png)
</td>
<td>
[![edge compute learning](hicompute.png)](hicompute.png)
</tr>
<td>
[![codespaces project](websitecompute.png)](websitecompute.png)
</td>
<td>
[![codespaces project](computecodespace.png)](computecodespace.png)
</td>
</tr>
</table>

One of the company's primary products is an edge computing platform. Building for the edge remains a new topic to most developers, so onboarding means acquiring new **mental models**. Again, Glitch supported this by providing a tangible sense of developer workflows and implementation context. It's always a good idea to reach into **ecosystem topics** when you teach developer skills, but when your tech is part of the infrastructure it's essential.

When Glitch shut down, we had to find alternative paths both for Fastly users onboarding via Glitch, and any Glitch users whose apps we could transition to Fastly Compute. Combined with the threat of losing the best teaching environment for web development I've ever had access to, this led me to build in-editor supports into GitHub Codespaces container configurations to create a similar experience to Glitch.

> 📖 [Enabling developers in GitHub Codespaces](https://dev.to/fastly/enabling-developers-in-github-codespaces-1l3a) _– October 2025_

I've begun the process of extending this to support new developers coming from vibe coding platforms, who want to learn web development by starting from an existing codebase they've exported. I believe LLM-generated code can act as a strong entry pathway for learning developer skills, given the right tooling and support.

<h2 id="postman-learning-framework"> Postman learning framework</h2>

At Postman, I developed a framework for transforming API responses into **dynamically generated** tutorials inside the product. This was one of many learning systems in which I used Glitch – designing APIs that taught the learner about themselves by returning structured metadata that Postman's HTML visualisation tooling rendered as interactive guides inside the HTTP client UI. I defined a standard format for these so that we could extend and coauthor similar experiences for customers and with partners.

> 📖 [Blog post about the framework](https://blog.postman.com/how-we-build-learning-experiences-inside-postman/) _– March 2021_

![api 101 collection](api101.jpg)

We used my training framework for many guided community, customer, and employee workshops – I discovered the benefit of leveraging the same foundation of learning resources to power training in different settings. 

> 📖 [Using Glitch for Postman learning](https://blog.postman.com/learn-api-basics-postman-glitch/) _– June 2020_

<h2 id="language-models-for-learning"> Language models for learning</h2>

In 2026 I'm working on IDE extensions using LLMs to help developers understand and interact with codebases. I believe code comprehension is going to become more challenging and important than ever, and that we need much better tooling for it, so that's where I'm focusing. 

⏳ _I have a few other experiments in the works, stay tuned for more!_
